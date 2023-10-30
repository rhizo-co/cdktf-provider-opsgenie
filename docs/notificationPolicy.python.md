# `opsgenie_notification_policy`

Refer to the Terraform Registory for docs: [`opsgenie_notification_policy`](https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy).

# `notificationPolicy` Submodule <a name="`notificationPolicy` Submodule" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### NotificationPolicy <a name="NotificationPolicy" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy"></a>

Represents a {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy opsgenie_notification_policy}.

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicy(
  scope: Construct,
  id: str,
  connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection] = None,
  count: typing.Union[typing.Union[int, float], TerraformCount] = None,
  depends_on: typing.List[ITerraformDependable] = None,
  for_each: ITerraformIterator = None,
  lifecycle: TerraformResourceLifecycle = None,
  provider: TerraformProvider = None,
  provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]] = None,
  filter: typing.Union[IResolvable, typing.List[NotificationPolicyFilter]],
  name: str,
  team_id: str,
  auto_close_action: typing.Union[IResolvable, typing.List[NotificationPolicyAutoCloseAction]] = None,
  auto_restart_action: typing.Union[IResolvable, typing.List[NotificationPolicyAutoRestartAction]] = None,
  de_duplication_action: typing.Union[IResolvable, typing.List[NotificationPolicyDeDuplicationAction]] = None,
  delay_action: typing.Union[IResolvable, typing.List[NotificationPolicyDelayAction]] = None,
  enabled: typing.Union[bool, IResolvable] = None,
  id: str = None,
  policy_description: str = None,
  suppress: typing.Union[bool, IResolvable] = None,
  time_restriction: typing.Union[IResolvable, typing.List[NotificationPolicyTimeRestriction]] = None
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.id">id</a></code> | <code>str</code> | The scoped construct ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.connection">connection</a></code> | <code>typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.dependsOn">depends_on</a></code> | <code>typing.List[cdktf.ITerraformDependable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.provisioners">provisioners</a></code> | <code>typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.filter">filter</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter">NotificationPolicyFilter</a>]]</code> | filter block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.name">name</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#name NotificationPolicy#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.teamId">team_id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#team_id NotificationPolicy#team_id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.autoCloseAction">auto_close_action</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction">NotificationPolicyAutoCloseAction</a>]]</code> | auto_close_action block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.autoRestartAction">auto_restart_action</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction">NotificationPolicyAutoRestartAction</a>]]</code> | auto_restart_action block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.deDuplicationAction">de_duplication_action</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction">NotificationPolicyDeDuplicationAction</a>]]</code> | de_duplication_action block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.delayAction">delay_action</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction">NotificationPolicyDelayAction</a>]]</code> | delay_action block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.enabled">enabled</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#enabled NotificationPolicy#enabled}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.id">id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#id NotificationPolicy#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.policyDescription">policy_description</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#policy_description NotificationPolicy#policy_description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.suppress">suppress</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#suppress NotificationPolicy#suppress}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.timeRestriction">time_restriction</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction">NotificationPolicyTimeRestriction</a>]]</code> | time_restriction block. |

---

##### `scope`<sup>Required</sup> <a name="scope" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.id"></a>

- *Type:* str

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.connection"></a>

- *Type:* typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.count"></a>

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.dependsOn"></a>

- *Type:* typing.List[cdktf.ITerraformDependable]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.forEach"></a>

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.lifecycle"></a>

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.provider"></a>

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.provisioners"></a>

- *Type:* typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]

---

##### `filter`<sup>Required</sup> <a name="filter" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.filter"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter">NotificationPolicyFilter</a>]]

filter block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#filter NotificationPolicy#filter}

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.name"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#name NotificationPolicy#name}.

---

##### `team_id`<sup>Required</sup> <a name="team_id" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.teamId"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#team_id NotificationPolicy#team_id}.

---

##### `auto_close_action`<sup>Optional</sup> <a name="auto_close_action" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.autoCloseAction"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction">NotificationPolicyAutoCloseAction</a>]]

auto_close_action block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#auto_close_action NotificationPolicy#auto_close_action}

---

##### `auto_restart_action`<sup>Optional</sup> <a name="auto_restart_action" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.autoRestartAction"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction">NotificationPolicyAutoRestartAction</a>]]

auto_restart_action block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#auto_restart_action NotificationPolicy#auto_restart_action}

---

##### `de_duplication_action`<sup>Optional</sup> <a name="de_duplication_action" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.deDuplicationAction"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction">NotificationPolicyDeDuplicationAction</a>]]

de_duplication_action block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#de_duplication_action NotificationPolicy#de_duplication_action}

---

##### `delay_action`<sup>Optional</sup> <a name="delay_action" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.delayAction"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction">NotificationPolicyDelayAction</a>]]

delay_action block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#delay_action NotificationPolicy#delay_action}

---

##### `enabled`<sup>Optional</sup> <a name="enabled" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.enabled"></a>

- *Type:* typing.Union[bool, cdktf.IResolvable]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#enabled NotificationPolicy#enabled}.

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.id"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#id NotificationPolicy#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `policy_description`<sup>Optional</sup> <a name="policy_description" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.policyDescription"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#policy_description NotificationPolicy#policy_description}.

---

##### `suppress`<sup>Optional</sup> <a name="suppress" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.suppress"></a>

- *Type:* typing.Union[bool, cdktf.IResolvable]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#suppress NotificationPolicy#suppress}.

---

##### `time_restriction`<sup>Optional</sup> <a name="time_restriction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.timeRestriction"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction">NotificationPolicyTimeRestriction</a>]]

time_restriction block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_restriction NotificationPolicy#time_restriction}

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.toString">to_string</a></code> | Returns a string representation of this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.addOverride">add_override</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.overrideLogicalId">override_logical_id</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetOverrideLogicalId">reset_override_logical_id</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.toMetadata">to_metadata</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.toTerraform">to_terraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putAutoCloseAction">put_auto_close_action</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putAutoRestartAction">put_auto_restart_action</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putDeDuplicationAction">put_de_duplication_action</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putDelayAction">put_delay_action</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putFilter">put_filter</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putTimeRestriction">put_time_restriction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetAutoCloseAction">reset_auto_close_action</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetAutoRestartAction">reset_auto_restart_action</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetDeDuplicationAction">reset_de_duplication_action</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetDelayAction">reset_delay_action</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetEnabled">reset_enabled</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetId">reset_id</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetPolicyDescription">reset_policy_description</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetSuppress">reset_suppress</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetTimeRestriction">reset_time_restriction</a></code> | *No description.* |

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.toString"></a>

```python
def to_string() -> str
```

Returns a string representation of this construct.

##### `add_override` <a name="add_override" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.addOverride"></a>

```python
def add_override(
  path: str,
  value: typing.Any
) -> None
```

###### `path`<sup>Required</sup> <a name="path" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.addOverride.parameter.path"></a>

- *Type:* str

---

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.addOverride.parameter.value"></a>

- *Type:* typing.Any

---

##### `override_logical_id` <a name="override_logical_id" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.overrideLogicalId"></a>

```python
def override_logical_id(
  new_logical_id: str
) -> None
```

Overrides the auto-generated logical ID with a specific ID.

###### `new_logical_id`<sup>Required</sup> <a name="new_logical_id" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* str

The new logical ID to use for this stack element.

---

##### `reset_override_logical_id` <a name="reset_override_logical_id" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetOverrideLogicalId"></a>

```python
def reset_override_logical_id() -> None
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `to_metadata` <a name="to_metadata" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.toMetadata"></a>

```python
def to_metadata() -> typing.Any
```

##### `to_terraform` <a name="to_terraform" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.toTerraform"></a>

```python
def to_terraform() -> typing.Any
```

Adds this resource to the terraform JSON output.

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `put_auto_close_action` <a name="put_auto_close_action" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putAutoCloseAction"></a>

```python
def put_auto_close_action(
  value: typing.Union[IResolvable, typing.List[NotificationPolicyAutoCloseAction]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putAutoCloseAction.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction">NotificationPolicyAutoCloseAction</a>]]

---

##### `put_auto_restart_action` <a name="put_auto_restart_action" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putAutoRestartAction"></a>

```python
def put_auto_restart_action(
  value: typing.Union[IResolvable, typing.List[NotificationPolicyAutoRestartAction]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putAutoRestartAction.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction">NotificationPolicyAutoRestartAction</a>]]

---

##### `put_de_duplication_action` <a name="put_de_duplication_action" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putDeDuplicationAction"></a>

```python
def put_de_duplication_action(
  value: typing.Union[IResolvable, typing.List[NotificationPolicyDeDuplicationAction]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putDeDuplicationAction.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction">NotificationPolicyDeDuplicationAction</a>]]

---

##### `put_delay_action` <a name="put_delay_action" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putDelayAction"></a>

```python
def put_delay_action(
  value: typing.Union[IResolvable, typing.List[NotificationPolicyDelayAction]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putDelayAction.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction">NotificationPolicyDelayAction</a>]]

---

##### `put_filter` <a name="put_filter" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putFilter"></a>

```python
def put_filter(
  value: typing.Union[IResolvable, typing.List[NotificationPolicyFilter]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putFilter.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter">NotificationPolicyFilter</a>]]

---

##### `put_time_restriction` <a name="put_time_restriction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putTimeRestriction"></a>

```python
def put_time_restriction(
  value: typing.Union[IResolvable, typing.List[NotificationPolicyTimeRestriction]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putTimeRestriction.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction">NotificationPolicyTimeRestriction</a>]]

---

##### `reset_auto_close_action` <a name="reset_auto_close_action" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetAutoCloseAction"></a>

```python
def reset_auto_close_action() -> None
```

##### `reset_auto_restart_action` <a name="reset_auto_restart_action" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetAutoRestartAction"></a>

```python
def reset_auto_restart_action() -> None
```

##### `reset_de_duplication_action` <a name="reset_de_duplication_action" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetDeDuplicationAction"></a>

```python
def reset_de_duplication_action() -> None
```

##### `reset_delay_action` <a name="reset_delay_action" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetDelayAction"></a>

```python
def reset_delay_action() -> None
```

##### `reset_enabled` <a name="reset_enabled" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetEnabled"></a>

```python
def reset_enabled() -> None
```

##### `reset_id` <a name="reset_id" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetId"></a>

```python
def reset_id() -> None
```

##### `reset_policy_description` <a name="reset_policy_description" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetPolicyDescription"></a>

```python
def reset_policy_description() -> None
```

##### `reset_suppress` <a name="reset_suppress" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetSuppress"></a>

```python
def reset_suppress() -> None
```

##### `reset_time_restriction` <a name="reset_time_restriction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetTimeRestriction"></a>

```python
def reset_time_restriction() -> None
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.isConstruct">is_construct</a></code> | Checks if `x` is a construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.isTerraformElement">is_terraform_element</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.isTerraformResource">is_terraform_resource</a></code> | *No description.* |

---

##### `is_construct` <a name="is_construct" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.isConstruct"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicy.is_construct(
  x: typing.Any
)
```

Checks if `x` is a construct.

Use this method instead of `instanceof` to properly detect `Construct`
instances, even when the construct library is symlinked.

Explanation: in JavaScript, multiple copies of the `constructs` library on
disk are seen as independent, completely different libraries. As a
consequence, the class `Construct` in each copy of the `constructs` library
is seen as a different class, and an instance of one class will not test as
`instanceof` the other class. `npm install` will not create installations
like this, but users may manually symlink construct libraries together or
use a monorepo tool: in those cases, multiple copies of the `constructs`
library can be accidentally installed, and `instanceof` will behave
unpredictably. It is safest to avoid using `instanceof`, and using
this type-testing method instead.

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.isConstruct.parameter.x"></a>

- *Type:* typing.Any

Any object.

---

##### `is_terraform_element` <a name="is_terraform_element" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.isTerraformElement"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicy.is_terraform_element(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.isTerraformElement.parameter.x"></a>

- *Type:* typing.Any

---

##### `is_terraform_resource` <a name="is_terraform_resource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.isTerraformResource"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicy.is_terraform_resource(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.isTerraformResource.parameter.x"></a>

- *Type:* typing.Any

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.node">node</a></code> | <code>constructs.Node</code> | The tree node. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.cdktfStack">cdktf_stack</a></code> | <code>cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.friendlyUniqueId">friendly_unique_id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.terraformMetaArguments">terraform_meta_arguments</a></code> | <code>typing.Mapping[typing.Any]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.terraformResourceType">terraform_resource_type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.terraformGeneratorMetadata">terraform_generator_metadata</a></code> | <code>cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.connection">connection</a></code> | <code>typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.dependsOn">depends_on</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.provisioners">provisioners</a></code> | <code>typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.autoCloseAction">auto_close_action</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList">NotificationPolicyAutoCloseActionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.autoRestartAction">auto_restart_action</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList">NotificationPolicyAutoRestartActionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.deDuplicationAction">de_duplication_action</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList">NotificationPolicyDeDuplicationActionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.delayAction">delay_action</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList">NotificationPolicyDelayActionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.filter">filter</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList">NotificationPolicyFilterList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.timeRestriction">time_restriction</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList">NotificationPolicyTimeRestrictionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.autoCloseActionInput">auto_close_action_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction">NotificationPolicyAutoCloseAction</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.autoRestartActionInput">auto_restart_action_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction">NotificationPolicyAutoRestartAction</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.deDuplicationActionInput">de_duplication_action_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction">NotificationPolicyDeDuplicationAction</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.delayActionInput">delay_action_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction">NotificationPolicyDelayAction</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.enabledInput">enabled_input</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.filterInput">filter_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter">NotificationPolicyFilter</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.idInput">id_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.nameInput">name_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.policyDescriptionInput">policy_description_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.suppressInput">suppress_input</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.teamIdInput">team_id_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.timeRestrictionInput">time_restriction_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction">NotificationPolicyTimeRestriction</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.enabled">enabled</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.id">id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.name">name</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.policyDescription">policy_description</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.suppress">suppress</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.teamId">team_id</a></code> | <code>str</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.node"></a>

```python
node: Node
```

- *Type:* constructs.Node

The tree node.

---

##### `cdktf_stack`<sup>Required</sup> <a name="cdktf_stack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.cdktfStack"></a>

```python
cdktf_stack: TerraformStack
```

- *Type:* cdktf.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `friendly_unique_id`<sup>Required</sup> <a name="friendly_unique_id" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.friendlyUniqueId"></a>

```python
friendly_unique_id: str
```

- *Type:* str

---

##### `terraform_meta_arguments`<sup>Required</sup> <a name="terraform_meta_arguments" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.terraformMetaArguments"></a>

```python
terraform_meta_arguments: typing.Mapping[typing.Any]
```

- *Type:* typing.Mapping[typing.Any]

---

##### `terraform_resource_type`<sup>Required</sup> <a name="terraform_resource_type" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.terraformResourceType"></a>

```python
terraform_resource_type: str
```

- *Type:* str

---

##### `terraform_generator_metadata`<sup>Optional</sup> <a name="terraform_generator_metadata" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.terraformGeneratorMetadata"></a>

```python
terraform_generator_metadata: TerraformProviderGeneratorMetadata
```

- *Type:* cdktf.TerraformProviderGeneratorMetadata

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.connection"></a>

```python
connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection]
```

- *Type:* typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.count"></a>

```python
count: typing.Union[typing.Union[int, float], TerraformCount]
```

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.dependsOn"></a>

```python
depends_on: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.forEach"></a>

```python
for_each: ITerraformIterator
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.lifecycle"></a>

```python
lifecycle: TerraformResourceLifecycle
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.provider"></a>

```python
provider: TerraformProvider
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.provisioners"></a>

```python
provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]]
```

- *Type:* typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]

---

##### `auto_close_action`<sup>Required</sup> <a name="auto_close_action" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.autoCloseAction"></a>

```python
auto_close_action: NotificationPolicyAutoCloseActionList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList">NotificationPolicyAutoCloseActionList</a>

---

##### `auto_restart_action`<sup>Required</sup> <a name="auto_restart_action" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.autoRestartAction"></a>

```python
auto_restart_action: NotificationPolicyAutoRestartActionList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList">NotificationPolicyAutoRestartActionList</a>

---

##### `de_duplication_action`<sup>Required</sup> <a name="de_duplication_action" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.deDuplicationAction"></a>

```python
de_duplication_action: NotificationPolicyDeDuplicationActionList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList">NotificationPolicyDeDuplicationActionList</a>

---

##### `delay_action`<sup>Required</sup> <a name="delay_action" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.delayAction"></a>

```python
delay_action: NotificationPolicyDelayActionList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList">NotificationPolicyDelayActionList</a>

---

##### `filter`<sup>Required</sup> <a name="filter" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.filter"></a>

```python
filter: NotificationPolicyFilterList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList">NotificationPolicyFilterList</a>

---

##### `time_restriction`<sup>Required</sup> <a name="time_restriction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.timeRestriction"></a>

```python
time_restriction: NotificationPolicyTimeRestrictionList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList">NotificationPolicyTimeRestrictionList</a>

---

##### `auto_close_action_input`<sup>Optional</sup> <a name="auto_close_action_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.autoCloseActionInput"></a>

```python
auto_close_action_input: typing.Union[IResolvable, typing.List[NotificationPolicyAutoCloseAction]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction">NotificationPolicyAutoCloseAction</a>]]

---

##### `auto_restart_action_input`<sup>Optional</sup> <a name="auto_restart_action_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.autoRestartActionInput"></a>

```python
auto_restart_action_input: typing.Union[IResolvable, typing.List[NotificationPolicyAutoRestartAction]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction">NotificationPolicyAutoRestartAction</a>]]

---

##### `de_duplication_action_input`<sup>Optional</sup> <a name="de_duplication_action_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.deDuplicationActionInput"></a>

```python
de_duplication_action_input: typing.Union[IResolvable, typing.List[NotificationPolicyDeDuplicationAction]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction">NotificationPolicyDeDuplicationAction</a>]]

---

##### `delay_action_input`<sup>Optional</sup> <a name="delay_action_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.delayActionInput"></a>

```python
delay_action_input: typing.Union[IResolvable, typing.List[NotificationPolicyDelayAction]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction">NotificationPolicyDelayAction</a>]]

---

##### `enabled_input`<sup>Optional</sup> <a name="enabled_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.enabledInput"></a>

```python
enabled_input: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `filter_input`<sup>Optional</sup> <a name="filter_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.filterInput"></a>

```python
filter_input: typing.Union[IResolvable, typing.List[NotificationPolicyFilter]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter">NotificationPolicyFilter</a>]]

---

##### `id_input`<sup>Optional</sup> <a name="id_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.idInput"></a>

```python
id_input: str
```

- *Type:* str

---

##### `name_input`<sup>Optional</sup> <a name="name_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.nameInput"></a>

```python
name_input: str
```

- *Type:* str

---

##### `policy_description_input`<sup>Optional</sup> <a name="policy_description_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.policyDescriptionInput"></a>

```python
policy_description_input: str
```

- *Type:* str

---

##### `suppress_input`<sup>Optional</sup> <a name="suppress_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.suppressInput"></a>

```python
suppress_input: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `team_id_input`<sup>Optional</sup> <a name="team_id_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.teamIdInput"></a>

```python
team_id_input: str
```

- *Type:* str

---

##### `time_restriction_input`<sup>Optional</sup> <a name="time_restriction_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.timeRestrictionInput"></a>

```python
time_restriction_input: typing.Union[IResolvable, typing.List[NotificationPolicyTimeRestriction]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction">NotificationPolicyTimeRestriction</a>]]

---

##### `enabled`<sup>Required</sup> <a name="enabled" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.enabled"></a>

```python
enabled: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.id"></a>

```python
id: str
```

- *Type:* str

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.name"></a>

```python
name: str
```

- *Type:* str

---

##### `policy_description`<sup>Required</sup> <a name="policy_description" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.policyDescription"></a>

```python
policy_description: str
```

- *Type:* str

---

##### `suppress`<sup>Required</sup> <a name="suppress" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.suppress"></a>

```python
suppress: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `team_id`<sup>Required</sup> <a name="team_id" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.teamId"></a>

```python
team_id: str
```

- *Type:* str

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.tfResourceType">tfResourceType</a></code> | <code>str</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.tfResourceType"></a>

```python
tfResourceType: str
```

- *Type:* str

---

## Structs <a name="Structs" id="Structs"></a>

### NotificationPolicyAutoCloseAction <a name="NotificationPolicyAutoCloseAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyAutoCloseAction(
  duration: typing.Union[IResolvable, typing.List[NotificationPolicyAutoCloseActionDuration]]
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction.property.duration">duration</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration">NotificationPolicyAutoCloseActionDuration</a>]]</code> | duration block. |

---

##### `duration`<sup>Required</sup> <a name="duration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction.property.duration"></a>

```python
duration: typing.Union[IResolvable, typing.List[NotificationPolicyAutoCloseActionDuration]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration">NotificationPolicyAutoCloseActionDuration</a>]]

duration block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#duration NotificationPolicy#duration}

---

### NotificationPolicyAutoCloseActionDuration <a name="NotificationPolicyAutoCloseActionDuration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyAutoCloseActionDuration(
  time_amount: typing.Union[int, float],
  time_unit: str = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration.property.timeAmount">time_amount</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_amount NotificationPolicy#time_amount}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration.property.timeUnit">time_unit</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_unit NotificationPolicy#time_unit}. |

---

##### `time_amount`<sup>Required</sup> <a name="time_amount" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration.property.timeAmount"></a>

```python
time_amount: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_amount NotificationPolicy#time_amount}.

---

##### `time_unit`<sup>Optional</sup> <a name="time_unit" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration.property.timeUnit"></a>

```python
time_unit: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_unit NotificationPolicy#time_unit}.

---

### NotificationPolicyAutoRestartAction <a name="NotificationPolicyAutoRestartAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyAutoRestartAction(
  duration: typing.Union[IResolvable, typing.List[NotificationPolicyAutoRestartActionDuration]],
  max_repeat_count: typing.Union[int, float]
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction.property.duration">duration</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration">NotificationPolicyAutoRestartActionDuration</a>]]</code> | duration block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction.property.maxRepeatCount">max_repeat_count</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#max_repeat_count NotificationPolicy#max_repeat_count}. |

---

##### `duration`<sup>Required</sup> <a name="duration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction.property.duration"></a>

```python
duration: typing.Union[IResolvable, typing.List[NotificationPolicyAutoRestartActionDuration]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration">NotificationPolicyAutoRestartActionDuration</a>]]

duration block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#duration NotificationPolicy#duration}

---

##### `max_repeat_count`<sup>Required</sup> <a name="max_repeat_count" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction.property.maxRepeatCount"></a>

```python
max_repeat_count: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#max_repeat_count NotificationPolicy#max_repeat_count}.

---

### NotificationPolicyAutoRestartActionDuration <a name="NotificationPolicyAutoRestartActionDuration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyAutoRestartActionDuration(
  time_amount: typing.Union[int, float],
  time_unit: str = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration.property.timeAmount">time_amount</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_amount NotificationPolicy#time_amount}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration.property.timeUnit">time_unit</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_unit NotificationPolicy#time_unit}. |

---

##### `time_amount`<sup>Required</sup> <a name="time_amount" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration.property.timeAmount"></a>

```python
time_amount: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_amount NotificationPolicy#time_amount}.

---

##### `time_unit`<sup>Optional</sup> <a name="time_unit" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration.property.timeUnit"></a>

```python
time_unit: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_unit NotificationPolicy#time_unit}.

---

### NotificationPolicyConfig <a name="NotificationPolicyConfig" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyConfig(
  connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection] = None,
  count: typing.Union[typing.Union[int, float], TerraformCount] = None,
  depends_on: typing.List[ITerraformDependable] = None,
  for_each: ITerraformIterator = None,
  lifecycle: TerraformResourceLifecycle = None,
  provider: TerraformProvider = None,
  provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]] = None,
  filter: typing.Union[IResolvable, typing.List[NotificationPolicyFilter]],
  name: str,
  team_id: str,
  auto_close_action: typing.Union[IResolvable, typing.List[NotificationPolicyAutoCloseAction]] = None,
  auto_restart_action: typing.Union[IResolvable, typing.List[NotificationPolicyAutoRestartAction]] = None,
  de_duplication_action: typing.Union[IResolvable, typing.List[NotificationPolicyDeDuplicationAction]] = None,
  delay_action: typing.Union[IResolvable, typing.List[NotificationPolicyDelayAction]] = None,
  enabled: typing.Union[bool, IResolvable] = None,
  id: str = None,
  policy_description: str = None,
  suppress: typing.Union[bool, IResolvable] = None,
  time_restriction: typing.Union[IResolvable, typing.List[NotificationPolicyTimeRestriction]] = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.connection">connection</a></code> | <code>typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.dependsOn">depends_on</a></code> | <code>typing.List[cdktf.ITerraformDependable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.provisioners">provisioners</a></code> | <code>typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.filter">filter</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter">NotificationPolicyFilter</a>]]</code> | filter block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.name">name</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#name NotificationPolicy#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.teamId">team_id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#team_id NotificationPolicy#team_id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.autoCloseAction">auto_close_action</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction">NotificationPolicyAutoCloseAction</a>]]</code> | auto_close_action block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.autoRestartAction">auto_restart_action</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction">NotificationPolicyAutoRestartAction</a>]]</code> | auto_restart_action block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.deDuplicationAction">de_duplication_action</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction">NotificationPolicyDeDuplicationAction</a>]]</code> | de_duplication_action block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.delayAction">delay_action</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction">NotificationPolicyDelayAction</a>]]</code> | delay_action block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.enabled">enabled</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#enabled NotificationPolicy#enabled}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.id">id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#id NotificationPolicy#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.policyDescription">policy_description</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#policy_description NotificationPolicy#policy_description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.suppress">suppress</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#suppress NotificationPolicy#suppress}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.timeRestriction">time_restriction</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction">NotificationPolicyTimeRestriction</a>]]</code> | time_restriction block. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.connection"></a>

```python
connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection]
```

- *Type:* typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.count"></a>

```python
count: typing.Union[typing.Union[int, float], TerraformCount]
```

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.dependsOn"></a>

```python
depends_on: typing.List[ITerraformDependable]
```

- *Type:* typing.List[cdktf.ITerraformDependable]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.forEach"></a>

```python
for_each: ITerraformIterator
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.lifecycle"></a>

```python
lifecycle: TerraformResourceLifecycle
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.provider"></a>

```python
provider: TerraformProvider
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.provisioners"></a>

```python
provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]]
```

- *Type:* typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]

---

##### `filter`<sup>Required</sup> <a name="filter" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.filter"></a>

```python
filter: typing.Union[IResolvable, typing.List[NotificationPolicyFilter]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter">NotificationPolicyFilter</a>]]

filter block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#filter NotificationPolicy#filter}

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.name"></a>

```python
name: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#name NotificationPolicy#name}.

---

##### `team_id`<sup>Required</sup> <a name="team_id" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.teamId"></a>

```python
team_id: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#team_id NotificationPolicy#team_id}.

---

##### `auto_close_action`<sup>Optional</sup> <a name="auto_close_action" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.autoCloseAction"></a>

```python
auto_close_action: typing.Union[IResolvable, typing.List[NotificationPolicyAutoCloseAction]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction">NotificationPolicyAutoCloseAction</a>]]

auto_close_action block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#auto_close_action NotificationPolicy#auto_close_action}

---

##### `auto_restart_action`<sup>Optional</sup> <a name="auto_restart_action" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.autoRestartAction"></a>

```python
auto_restart_action: typing.Union[IResolvable, typing.List[NotificationPolicyAutoRestartAction]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction">NotificationPolicyAutoRestartAction</a>]]

auto_restart_action block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#auto_restart_action NotificationPolicy#auto_restart_action}

---

##### `de_duplication_action`<sup>Optional</sup> <a name="de_duplication_action" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.deDuplicationAction"></a>

```python
de_duplication_action: typing.Union[IResolvable, typing.List[NotificationPolicyDeDuplicationAction]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction">NotificationPolicyDeDuplicationAction</a>]]

de_duplication_action block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#de_duplication_action NotificationPolicy#de_duplication_action}

---

##### `delay_action`<sup>Optional</sup> <a name="delay_action" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.delayAction"></a>

```python
delay_action: typing.Union[IResolvable, typing.List[NotificationPolicyDelayAction]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction">NotificationPolicyDelayAction</a>]]

delay_action block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#delay_action NotificationPolicy#delay_action}

---

##### `enabled`<sup>Optional</sup> <a name="enabled" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.enabled"></a>

```python
enabled: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#enabled NotificationPolicy#enabled}.

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.id"></a>

```python
id: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#id NotificationPolicy#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `policy_description`<sup>Optional</sup> <a name="policy_description" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.policyDescription"></a>

```python
policy_description: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#policy_description NotificationPolicy#policy_description}.

---

##### `suppress`<sup>Optional</sup> <a name="suppress" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.suppress"></a>

```python
suppress: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#suppress NotificationPolicy#suppress}.

---

##### `time_restriction`<sup>Optional</sup> <a name="time_restriction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.timeRestriction"></a>

```python
time_restriction: typing.Union[IResolvable, typing.List[NotificationPolicyTimeRestriction]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction">NotificationPolicyTimeRestriction</a>]]

time_restriction block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_restriction NotificationPolicy#time_restriction}

---

### NotificationPolicyDeDuplicationAction <a name="NotificationPolicyDeDuplicationAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyDeDuplicationAction(
  count: typing.Union[int, float],
  de_duplication_action_type: str,
  duration: typing.Union[IResolvable, typing.List[NotificationPolicyDeDuplicationActionDuration]] = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction.property.count">count</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#count NotificationPolicy#count}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction.property.deDuplicationActionType">de_duplication_action_type</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#de_duplication_action_type NotificationPolicy#de_duplication_action_type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction.property.duration">duration</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration">NotificationPolicyDeDuplicationActionDuration</a>]]</code> | duration block. |

---

##### `count`<sup>Required</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction.property.count"></a>

```python
count: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#count NotificationPolicy#count}.

---

##### `de_duplication_action_type`<sup>Required</sup> <a name="de_duplication_action_type" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction.property.deDuplicationActionType"></a>

```python
de_duplication_action_type: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#de_duplication_action_type NotificationPolicy#de_duplication_action_type}.

---

##### `duration`<sup>Optional</sup> <a name="duration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction.property.duration"></a>

```python
duration: typing.Union[IResolvable, typing.List[NotificationPolicyDeDuplicationActionDuration]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration">NotificationPolicyDeDuplicationActionDuration</a>]]

duration block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#duration NotificationPolicy#duration}

---

### NotificationPolicyDeDuplicationActionDuration <a name="NotificationPolicyDeDuplicationActionDuration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyDeDuplicationActionDuration(
  time_amount: typing.Union[int, float],
  time_unit: str = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration.property.timeAmount">time_amount</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_amount NotificationPolicy#time_amount}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration.property.timeUnit">time_unit</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_unit NotificationPolicy#time_unit}. |

---

##### `time_amount`<sup>Required</sup> <a name="time_amount" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration.property.timeAmount"></a>

```python
time_amount: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_amount NotificationPolicy#time_amount}.

---

##### `time_unit`<sup>Optional</sup> <a name="time_unit" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration.property.timeUnit"></a>

```python
time_unit: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_unit NotificationPolicy#time_unit}.

---

### NotificationPolicyDelayAction <a name="NotificationPolicyDelayAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyDelayAction(
  delay_option: str,
  duration: typing.Union[IResolvable, typing.List[NotificationPolicyDelayActionDuration]] = None,
  until_hour: typing.Union[int, float] = None,
  until_minute: typing.Union[int, float] = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction.property.delayOption">delay_option</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#delay_option NotificationPolicy#delay_option}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction.property.duration">duration</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration">NotificationPolicyDelayActionDuration</a>]]</code> | duration block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction.property.untilHour">until_hour</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#until_hour NotificationPolicy#until_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction.property.untilMinute">until_minute</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#until_minute NotificationPolicy#until_minute}. |

---

##### `delay_option`<sup>Required</sup> <a name="delay_option" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction.property.delayOption"></a>

```python
delay_option: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#delay_option NotificationPolicy#delay_option}.

---

##### `duration`<sup>Optional</sup> <a name="duration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction.property.duration"></a>

```python
duration: typing.Union[IResolvable, typing.List[NotificationPolicyDelayActionDuration]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration">NotificationPolicyDelayActionDuration</a>]]

duration block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#duration NotificationPolicy#duration}

---

##### `until_hour`<sup>Optional</sup> <a name="until_hour" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction.property.untilHour"></a>

```python
until_hour: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#until_hour NotificationPolicy#until_hour}.

---

##### `until_minute`<sup>Optional</sup> <a name="until_minute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction.property.untilMinute"></a>

```python
until_minute: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#until_minute NotificationPolicy#until_minute}.

---

### NotificationPolicyDelayActionDuration <a name="NotificationPolicyDelayActionDuration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyDelayActionDuration(
  time_amount: typing.Union[int, float],
  time_unit: str = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration.property.timeAmount">time_amount</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_amount NotificationPolicy#time_amount}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration.property.timeUnit">time_unit</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_unit NotificationPolicy#time_unit}. |

---

##### `time_amount`<sup>Required</sup> <a name="time_amount" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration.property.timeAmount"></a>

```python
time_amount: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_amount NotificationPolicy#time_amount}.

---

##### `time_unit`<sup>Optional</sup> <a name="time_unit" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration.property.timeUnit"></a>

```python
time_unit: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_unit NotificationPolicy#time_unit}.

---

### NotificationPolicyFilter <a name="NotificationPolicyFilter" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyFilter(
  conditions: typing.Union[IResolvable, typing.List[NotificationPolicyFilterConditions]] = None,
  type: str = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter.property.conditions">conditions</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions">NotificationPolicyFilterConditions</a>]]</code> | conditions block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter.property.type">type</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#type NotificationPolicy#type}. |

---

##### `conditions`<sup>Optional</sup> <a name="conditions" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter.property.conditions"></a>

```python
conditions: typing.Union[IResolvable, typing.List[NotificationPolicyFilterConditions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions">NotificationPolicyFilterConditions</a>]]

conditions block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#conditions NotificationPolicy#conditions}

---

##### `type`<sup>Optional</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter.property.type"></a>

```python
type: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#type NotificationPolicy#type}.

---

### NotificationPolicyFilterConditions <a name="NotificationPolicyFilterConditions" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyFilterConditions(
  field: str,
  operation: str,
  expected_value: str = None,
  key: str = None,
  not: typing.Union[bool, IResolvable] = None,
  order: typing.Union[int, float] = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.property.field">field</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#field NotificationPolicy#field}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.property.operation">operation</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#operation NotificationPolicy#operation}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.property.expectedValue">expected_value</a></code> | <code>str</code> | User defined value that will be compared with alert field according to the operation. Default value is empty string. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.property.key">key</a></code> | <code>str</code> | If 'field' is set as 'extra-properties', key could be used for key-value pair. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.property.not">not</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Indicates behaviour of the given operation. Default value is false. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.property.order">order</a></code> | <code>typing.Union[int, float]</code> | Order of the condition in conditions list. |

---

##### `field`<sup>Required</sup> <a name="field" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.property.field"></a>

```python
field: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#field NotificationPolicy#field}.

---

##### `operation`<sup>Required</sup> <a name="operation" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.property.operation"></a>

```python
operation: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#operation NotificationPolicy#operation}.

---

##### `expected_value`<sup>Optional</sup> <a name="expected_value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.property.expectedValue"></a>

```python
expected_value: str
```

- *Type:* str

User defined value that will be compared with alert field according to the operation. Default value is empty string.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#expected_value NotificationPolicy#expected_value}

---

##### `key`<sup>Optional</sup> <a name="key" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.property.key"></a>

```python
key: str
```

- *Type:* str

If 'field' is set as 'extra-properties', key could be used for key-value pair.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#key NotificationPolicy#key}

---

##### `not`<sup>Optional</sup> <a name="not" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.property.not"></a>

```python
not: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

Indicates behaviour of the given operation. Default value is false.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#not NotificationPolicy#not}

---

##### `order`<sup>Optional</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.property.order"></a>

```python
order: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Order of the condition in conditions list.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#order NotificationPolicy#order}

---

### NotificationPolicyTimeRestriction <a name="NotificationPolicyTimeRestriction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyTimeRestriction(
  type: str,
  restriction: typing.Union[IResolvable, typing.List[NotificationPolicyTimeRestrictionRestriction]] = None,
  restrictions: typing.Union[IResolvable, typing.List[NotificationPolicyTimeRestrictionRestrictions]] = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction.property.type">type</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#type NotificationPolicy#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction.property.restriction">restriction</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction">NotificationPolicyTimeRestrictionRestriction</a>]]</code> | restriction block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction.property.restrictions">restrictions</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions">NotificationPolicyTimeRestrictionRestrictions</a>]]</code> | restrictions block. |

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction.property.type"></a>

```python
type: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#type NotificationPolicy#type}.

---

##### `restriction`<sup>Optional</sup> <a name="restriction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction.property.restriction"></a>

```python
restriction: typing.Union[IResolvable, typing.List[NotificationPolicyTimeRestrictionRestriction]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction">NotificationPolicyTimeRestrictionRestriction</a>]]

restriction block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#restriction NotificationPolicy#restriction}

---

##### `restrictions`<sup>Optional</sup> <a name="restrictions" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction.property.restrictions"></a>

```python
restrictions: typing.Union[IResolvable, typing.List[NotificationPolicyTimeRestrictionRestrictions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions">NotificationPolicyTimeRestrictionRestrictions</a>]]

restrictions block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#restrictions NotificationPolicy#restrictions}

---

### NotificationPolicyTimeRestrictionRestriction <a name="NotificationPolicyTimeRestrictionRestriction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyTimeRestrictionRestriction(
  end_hour: typing.Union[int, float],
  end_min: typing.Union[int, float],
  start_hour: typing.Union[int, float],
  start_min: typing.Union[int, float]
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction.property.endHour">end_hour</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#end_hour NotificationPolicy#end_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction.property.endMin">end_min</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#end_min NotificationPolicy#end_min}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction.property.startHour">start_hour</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#start_hour NotificationPolicy#start_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction.property.startMin">start_min</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#start_min NotificationPolicy#start_min}. |

---

##### `end_hour`<sup>Required</sup> <a name="end_hour" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction.property.endHour"></a>

```python
end_hour: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#end_hour NotificationPolicy#end_hour}.

---

##### `end_min`<sup>Required</sup> <a name="end_min" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction.property.endMin"></a>

```python
end_min: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#end_min NotificationPolicy#end_min}.

---

##### `start_hour`<sup>Required</sup> <a name="start_hour" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction.property.startHour"></a>

```python
start_hour: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#start_hour NotificationPolicy#start_hour}.

---

##### `start_min`<sup>Required</sup> <a name="start_min" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction.property.startMin"></a>

```python
start_min: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#start_min NotificationPolicy#start_min}.

---

### NotificationPolicyTimeRestrictionRestrictions <a name="NotificationPolicyTimeRestrictionRestrictions" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyTimeRestrictionRestrictions(
  end_day: str,
  end_hour: typing.Union[int, float],
  end_min: typing.Union[int, float],
  start_day: str,
  start_hour: typing.Union[int, float],
  start_min: typing.Union[int, float]
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.property.endDay">end_day</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#end_day NotificationPolicy#end_day}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.property.endHour">end_hour</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#end_hour NotificationPolicy#end_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.property.endMin">end_min</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#end_min NotificationPolicy#end_min}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.property.startDay">start_day</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#start_day NotificationPolicy#start_day}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.property.startHour">start_hour</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#start_hour NotificationPolicy#start_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.property.startMin">start_min</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#start_min NotificationPolicy#start_min}. |

---

##### `end_day`<sup>Required</sup> <a name="end_day" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.property.endDay"></a>

```python
end_day: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#end_day NotificationPolicy#end_day}.

---

##### `end_hour`<sup>Required</sup> <a name="end_hour" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.property.endHour"></a>

```python
end_hour: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#end_hour NotificationPolicy#end_hour}.

---

##### `end_min`<sup>Required</sup> <a name="end_min" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.property.endMin"></a>

```python
end_min: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#end_min NotificationPolicy#end_min}.

---

##### `start_day`<sup>Required</sup> <a name="start_day" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.property.startDay"></a>

```python
start_day: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#start_day NotificationPolicy#start_day}.

---

##### `start_hour`<sup>Required</sup> <a name="start_hour" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.property.startHour"></a>

```python
start_hour: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#start_hour NotificationPolicy#start_hour}.

---

##### `start_min`<sup>Required</sup> <a name="start_min" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.property.startMin"></a>

```python
start_min: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#start_min NotificationPolicy#start_min}.

---

## Classes <a name="Classes" id="Classes"></a>

### NotificationPolicyAutoCloseActionDurationList <a name="NotificationPolicyAutoCloseActionDurationList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyAutoCloseActionDurationList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> NotificationPolicyAutoCloseActionDurationOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration">NotificationPolicyAutoCloseActionDuration</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[NotificationPolicyAutoCloseActionDuration]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration">NotificationPolicyAutoCloseActionDuration</a>]]

---


### NotificationPolicyAutoCloseActionDurationOutputReference <a name="NotificationPolicyAutoCloseActionDurationOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.resetTimeUnit">reset_time_unit</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `reset_time_unit` <a name="reset_time_unit" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.resetTimeUnit"></a>

```python
def reset_time_unit() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.timeAmountInput">time_amount_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.timeUnitInput">time_unit_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.timeAmount">time_amount</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.timeUnit">time_unit</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration">NotificationPolicyAutoCloseActionDuration</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `time_amount_input`<sup>Optional</sup> <a name="time_amount_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.timeAmountInput"></a>

```python
time_amount_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `time_unit_input`<sup>Optional</sup> <a name="time_unit_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.timeUnitInput"></a>

```python
time_unit_input: str
```

- *Type:* str

---

##### `time_amount`<sup>Required</sup> <a name="time_amount" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.timeAmount"></a>

```python
time_amount: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `time_unit`<sup>Required</sup> <a name="time_unit" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.timeUnit"></a>

```python
time_unit: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, NotificationPolicyAutoCloseActionDuration]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration">NotificationPolicyAutoCloseActionDuration</a>]

---


### NotificationPolicyAutoCloseActionList <a name="NotificationPolicyAutoCloseActionList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyAutoCloseActionList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> NotificationPolicyAutoCloseActionOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction">NotificationPolicyAutoCloseAction</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[NotificationPolicyAutoCloseAction]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction">NotificationPolicyAutoCloseAction</a>]]

---


### NotificationPolicyAutoCloseActionOutputReference <a name="NotificationPolicyAutoCloseActionOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyAutoCloseActionOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.putDuration">put_duration</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `put_duration` <a name="put_duration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.putDuration"></a>

```python
def put_duration(
  value: typing.Union[IResolvable, typing.List[NotificationPolicyAutoCloseActionDuration]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.putDuration.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration">NotificationPolicyAutoCloseActionDuration</a>]]

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.property.duration">duration</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList">NotificationPolicyAutoCloseActionDurationList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.property.durationInput">duration_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration">NotificationPolicyAutoCloseActionDuration</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction">NotificationPolicyAutoCloseAction</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `duration`<sup>Required</sup> <a name="duration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.property.duration"></a>

```python
duration: NotificationPolicyAutoCloseActionDurationList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList">NotificationPolicyAutoCloseActionDurationList</a>

---

##### `duration_input`<sup>Optional</sup> <a name="duration_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.property.durationInput"></a>

```python
duration_input: typing.Union[IResolvable, typing.List[NotificationPolicyAutoCloseActionDuration]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration">NotificationPolicyAutoCloseActionDuration</a>]]

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, NotificationPolicyAutoCloseAction]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction">NotificationPolicyAutoCloseAction</a>]

---


### NotificationPolicyAutoRestartActionDurationList <a name="NotificationPolicyAutoRestartActionDurationList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyAutoRestartActionDurationList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> NotificationPolicyAutoRestartActionDurationOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration">NotificationPolicyAutoRestartActionDuration</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[NotificationPolicyAutoRestartActionDuration]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration">NotificationPolicyAutoRestartActionDuration</a>]]

---


### NotificationPolicyAutoRestartActionDurationOutputReference <a name="NotificationPolicyAutoRestartActionDurationOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.resetTimeUnit">reset_time_unit</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `reset_time_unit` <a name="reset_time_unit" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.resetTimeUnit"></a>

```python
def reset_time_unit() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.timeAmountInput">time_amount_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.timeUnitInput">time_unit_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.timeAmount">time_amount</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.timeUnit">time_unit</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration">NotificationPolicyAutoRestartActionDuration</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `time_amount_input`<sup>Optional</sup> <a name="time_amount_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.timeAmountInput"></a>

```python
time_amount_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `time_unit_input`<sup>Optional</sup> <a name="time_unit_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.timeUnitInput"></a>

```python
time_unit_input: str
```

- *Type:* str

---

##### `time_amount`<sup>Required</sup> <a name="time_amount" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.timeAmount"></a>

```python
time_amount: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `time_unit`<sup>Required</sup> <a name="time_unit" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.timeUnit"></a>

```python
time_unit: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, NotificationPolicyAutoRestartActionDuration]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration">NotificationPolicyAutoRestartActionDuration</a>]

---


### NotificationPolicyAutoRestartActionList <a name="NotificationPolicyAutoRestartActionList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyAutoRestartActionList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> NotificationPolicyAutoRestartActionOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction">NotificationPolicyAutoRestartAction</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[NotificationPolicyAutoRestartAction]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction">NotificationPolicyAutoRestartAction</a>]]

---


### NotificationPolicyAutoRestartActionOutputReference <a name="NotificationPolicyAutoRestartActionOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyAutoRestartActionOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.putDuration">put_duration</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `put_duration` <a name="put_duration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.putDuration"></a>

```python
def put_duration(
  value: typing.Union[IResolvable, typing.List[NotificationPolicyAutoRestartActionDuration]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.putDuration.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration">NotificationPolicyAutoRestartActionDuration</a>]]

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.duration">duration</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList">NotificationPolicyAutoRestartActionDurationList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.durationInput">duration_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration">NotificationPolicyAutoRestartActionDuration</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.maxRepeatCountInput">max_repeat_count_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.maxRepeatCount">max_repeat_count</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction">NotificationPolicyAutoRestartAction</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `duration`<sup>Required</sup> <a name="duration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.duration"></a>

```python
duration: NotificationPolicyAutoRestartActionDurationList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList">NotificationPolicyAutoRestartActionDurationList</a>

---

##### `duration_input`<sup>Optional</sup> <a name="duration_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.durationInput"></a>

```python
duration_input: typing.Union[IResolvable, typing.List[NotificationPolicyAutoRestartActionDuration]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration">NotificationPolicyAutoRestartActionDuration</a>]]

---

##### `max_repeat_count_input`<sup>Optional</sup> <a name="max_repeat_count_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.maxRepeatCountInput"></a>

```python
max_repeat_count_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `max_repeat_count`<sup>Required</sup> <a name="max_repeat_count" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.maxRepeatCount"></a>

```python
max_repeat_count: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, NotificationPolicyAutoRestartAction]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction">NotificationPolicyAutoRestartAction</a>]

---


### NotificationPolicyDeDuplicationActionDurationList <a name="NotificationPolicyDeDuplicationActionDurationList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyDeDuplicationActionDurationList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> NotificationPolicyDeDuplicationActionDurationOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration">NotificationPolicyDeDuplicationActionDuration</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[NotificationPolicyDeDuplicationActionDuration]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration">NotificationPolicyDeDuplicationActionDuration</a>]]

---


### NotificationPolicyDeDuplicationActionDurationOutputReference <a name="NotificationPolicyDeDuplicationActionDurationOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.resetTimeUnit">reset_time_unit</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `reset_time_unit` <a name="reset_time_unit" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.resetTimeUnit"></a>

```python
def reset_time_unit() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.timeAmountInput">time_amount_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.timeUnitInput">time_unit_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.timeAmount">time_amount</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.timeUnit">time_unit</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration">NotificationPolicyDeDuplicationActionDuration</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `time_amount_input`<sup>Optional</sup> <a name="time_amount_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.timeAmountInput"></a>

```python
time_amount_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `time_unit_input`<sup>Optional</sup> <a name="time_unit_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.timeUnitInput"></a>

```python
time_unit_input: str
```

- *Type:* str

---

##### `time_amount`<sup>Required</sup> <a name="time_amount" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.timeAmount"></a>

```python
time_amount: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `time_unit`<sup>Required</sup> <a name="time_unit" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.timeUnit"></a>

```python
time_unit: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, NotificationPolicyDeDuplicationActionDuration]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration">NotificationPolicyDeDuplicationActionDuration</a>]

---


### NotificationPolicyDeDuplicationActionList <a name="NotificationPolicyDeDuplicationActionList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyDeDuplicationActionList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> NotificationPolicyDeDuplicationActionOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction">NotificationPolicyDeDuplicationAction</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[NotificationPolicyDeDuplicationAction]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction">NotificationPolicyDeDuplicationAction</a>]]

---


### NotificationPolicyDeDuplicationActionOutputReference <a name="NotificationPolicyDeDuplicationActionOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.putDuration">put_duration</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.resetDuration">reset_duration</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `put_duration` <a name="put_duration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.putDuration"></a>

```python
def put_duration(
  value: typing.Union[IResolvable, typing.List[NotificationPolicyDeDuplicationActionDuration]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.putDuration.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration">NotificationPolicyDeDuplicationActionDuration</a>]]

---

##### `reset_duration` <a name="reset_duration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.resetDuration"></a>

```python
def reset_duration() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.duration">duration</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList">NotificationPolicyDeDuplicationActionDurationList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.countInput">count_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.deDuplicationActionTypeInput">de_duplication_action_type_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.durationInput">duration_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration">NotificationPolicyDeDuplicationActionDuration</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.count">count</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.deDuplicationActionType">de_duplication_action_type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction">NotificationPolicyDeDuplicationAction</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `duration`<sup>Required</sup> <a name="duration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.duration"></a>

```python
duration: NotificationPolicyDeDuplicationActionDurationList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList">NotificationPolicyDeDuplicationActionDurationList</a>

---

##### `count_input`<sup>Optional</sup> <a name="count_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.countInput"></a>

```python
count_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `de_duplication_action_type_input`<sup>Optional</sup> <a name="de_duplication_action_type_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.deDuplicationActionTypeInput"></a>

```python
de_duplication_action_type_input: str
```

- *Type:* str

---

##### `duration_input`<sup>Optional</sup> <a name="duration_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.durationInput"></a>

```python
duration_input: typing.Union[IResolvable, typing.List[NotificationPolicyDeDuplicationActionDuration]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration">NotificationPolicyDeDuplicationActionDuration</a>]]

---

##### `count`<sup>Required</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.count"></a>

```python
count: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `de_duplication_action_type`<sup>Required</sup> <a name="de_duplication_action_type" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.deDuplicationActionType"></a>

```python
de_duplication_action_type: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, NotificationPolicyDeDuplicationAction]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction">NotificationPolicyDeDuplicationAction</a>]

---


### NotificationPolicyDelayActionDurationList <a name="NotificationPolicyDelayActionDurationList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyDelayActionDurationList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> NotificationPolicyDelayActionDurationOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration">NotificationPolicyDelayActionDuration</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[NotificationPolicyDelayActionDuration]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration">NotificationPolicyDelayActionDuration</a>]]

---


### NotificationPolicyDelayActionDurationOutputReference <a name="NotificationPolicyDelayActionDurationOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyDelayActionDurationOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.resetTimeUnit">reset_time_unit</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `reset_time_unit` <a name="reset_time_unit" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.resetTimeUnit"></a>

```python
def reset_time_unit() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.timeAmountInput">time_amount_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.timeUnitInput">time_unit_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.timeAmount">time_amount</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.timeUnit">time_unit</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration">NotificationPolicyDelayActionDuration</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `time_amount_input`<sup>Optional</sup> <a name="time_amount_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.timeAmountInput"></a>

```python
time_amount_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `time_unit_input`<sup>Optional</sup> <a name="time_unit_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.timeUnitInput"></a>

```python
time_unit_input: str
```

- *Type:* str

---

##### `time_amount`<sup>Required</sup> <a name="time_amount" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.timeAmount"></a>

```python
time_amount: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `time_unit`<sup>Required</sup> <a name="time_unit" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.timeUnit"></a>

```python
time_unit: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, NotificationPolicyDelayActionDuration]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration">NotificationPolicyDelayActionDuration</a>]

---


### NotificationPolicyDelayActionList <a name="NotificationPolicyDelayActionList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyDelayActionList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> NotificationPolicyDelayActionOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction">NotificationPolicyDelayAction</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[NotificationPolicyDelayAction]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction">NotificationPolicyDelayAction</a>]]

---


### NotificationPolicyDelayActionOutputReference <a name="NotificationPolicyDelayActionOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyDelayActionOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.putDuration">put_duration</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.resetDuration">reset_duration</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.resetUntilHour">reset_until_hour</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.resetUntilMinute">reset_until_minute</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `put_duration` <a name="put_duration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.putDuration"></a>

```python
def put_duration(
  value: typing.Union[IResolvable, typing.List[NotificationPolicyDelayActionDuration]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.putDuration.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration">NotificationPolicyDelayActionDuration</a>]]

---

##### `reset_duration` <a name="reset_duration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.resetDuration"></a>

```python
def reset_duration() -> None
```

##### `reset_until_hour` <a name="reset_until_hour" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.resetUntilHour"></a>

```python
def reset_until_hour() -> None
```

##### `reset_until_minute` <a name="reset_until_minute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.resetUntilMinute"></a>

```python
def reset_until_minute() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.duration">duration</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList">NotificationPolicyDelayActionDurationList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.delayOptionInput">delay_option_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.durationInput">duration_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration">NotificationPolicyDelayActionDuration</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.untilHourInput">until_hour_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.untilMinuteInput">until_minute_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.delayOption">delay_option</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.untilHour">until_hour</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.untilMinute">until_minute</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction">NotificationPolicyDelayAction</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `duration`<sup>Required</sup> <a name="duration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.duration"></a>

```python
duration: NotificationPolicyDelayActionDurationList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList">NotificationPolicyDelayActionDurationList</a>

---

##### `delay_option_input`<sup>Optional</sup> <a name="delay_option_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.delayOptionInput"></a>

```python
delay_option_input: str
```

- *Type:* str

---

##### `duration_input`<sup>Optional</sup> <a name="duration_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.durationInput"></a>

```python
duration_input: typing.Union[IResolvable, typing.List[NotificationPolicyDelayActionDuration]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration">NotificationPolicyDelayActionDuration</a>]]

---

##### `until_hour_input`<sup>Optional</sup> <a name="until_hour_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.untilHourInput"></a>

```python
until_hour_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `until_minute_input`<sup>Optional</sup> <a name="until_minute_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.untilMinuteInput"></a>

```python
until_minute_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `delay_option`<sup>Required</sup> <a name="delay_option" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.delayOption"></a>

```python
delay_option: str
```

- *Type:* str

---

##### `until_hour`<sup>Required</sup> <a name="until_hour" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.untilHour"></a>

```python
until_hour: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `until_minute`<sup>Required</sup> <a name="until_minute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.untilMinute"></a>

```python
until_minute: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, NotificationPolicyDelayAction]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction">NotificationPolicyDelayAction</a>]

---


### NotificationPolicyFilterConditionsList <a name="NotificationPolicyFilterConditionsList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyFilterConditionsList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> NotificationPolicyFilterConditionsOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions">NotificationPolicyFilterConditions</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[NotificationPolicyFilterConditions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions">NotificationPolicyFilterConditions</a>]]

---


### NotificationPolicyFilterConditionsOutputReference <a name="NotificationPolicyFilterConditionsOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyFilterConditionsOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.resetExpectedValue">reset_expected_value</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.resetKey">reset_key</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.resetNot">reset_not</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.resetOrder">reset_order</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `reset_expected_value` <a name="reset_expected_value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.resetExpectedValue"></a>

```python
def reset_expected_value() -> None
```

##### `reset_key` <a name="reset_key" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.resetKey"></a>

```python
def reset_key() -> None
```

##### `reset_not` <a name="reset_not" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.resetNot"></a>

```python
def reset_not() -> None
```

##### `reset_order` <a name="reset_order" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.resetOrder"></a>

```python
def reset_order() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.expectedValueInput">expected_value_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.fieldInput">field_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.keyInput">key_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.notInput">not_input</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.operationInput">operation_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.orderInput">order_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.expectedValue">expected_value</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.field">field</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.key">key</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.not">not</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.operation">operation</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.order">order</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions">NotificationPolicyFilterConditions</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `expected_value_input`<sup>Optional</sup> <a name="expected_value_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.expectedValueInput"></a>

```python
expected_value_input: str
```

- *Type:* str

---

##### `field_input`<sup>Optional</sup> <a name="field_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.fieldInput"></a>

```python
field_input: str
```

- *Type:* str

---

##### `key_input`<sup>Optional</sup> <a name="key_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.keyInput"></a>

```python
key_input: str
```

- *Type:* str

---

##### `not_input`<sup>Optional</sup> <a name="not_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.notInput"></a>

```python
not_input: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `operation_input`<sup>Optional</sup> <a name="operation_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.operationInput"></a>

```python
operation_input: str
```

- *Type:* str

---

##### `order_input`<sup>Optional</sup> <a name="order_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.orderInput"></a>

```python
order_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `expected_value`<sup>Required</sup> <a name="expected_value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.expectedValue"></a>

```python
expected_value: str
```

- *Type:* str

---

##### `field`<sup>Required</sup> <a name="field" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.field"></a>

```python
field: str
```

- *Type:* str

---

##### `key`<sup>Required</sup> <a name="key" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.key"></a>

```python
key: str
```

- *Type:* str

---

##### `not`<sup>Required</sup> <a name="not" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.not"></a>

```python
not: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `operation`<sup>Required</sup> <a name="operation" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.operation"></a>

```python
operation: str
```

- *Type:* str

---

##### `order`<sup>Required</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.order"></a>

```python
order: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, NotificationPolicyFilterConditions]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions">NotificationPolicyFilterConditions</a>]

---


### NotificationPolicyFilterList <a name="NotificationPolicyFilterList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyFilterList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> NotificationPolicyFilterOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter">NotificationPolicyFilter</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[NotificationPolicyFilter]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter">NotificationPolicyFilter</a>]]

---


### NotificationPolicyFilterOutputReference <a name="NotificationPolicyFilterOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyFilterOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.putConditions">put_conditions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.resetConditions">reset_conditions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.resetType">reset_type</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `put_conditions` <a name="put_conditions" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.putConditions"></a>

```python
def put_conditions(
  value: typing.Union[IResolvable, typing.List[NotificationPolicyFilterConditions]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.putConditions.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions">NotificationPolicyFilterConditions</a>]]

---

##### `reset_conditions` <a name="reset_conditions" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.resetConditions"></a>

```python
def reset_conditions() -> None
```

##### `reset_type` <a name="reset_type" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.resetType"></a>

```python
def reset_type() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.conditions">conditions</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList">NotificationPolicyFilterConditionsList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.conditionsInput">conditions_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions">NotificationPolicyFilterConditions</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.typeInput">type_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.type">type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter">NotificationPolicyFilter</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `conditions`<sup>Required</sup> <a name="conditions" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.conditions"></a>

```python
conditions: NotificationPolicyFilterConditionsList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList">NotificationPolicyFilterConditionsList</a>

---

##### `conditions_input`<sup>Optional</sup> <a name="conditions_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.conditionsInput"></a>

```python
conditions_input: typing.Union[IResolvable, typing.List[NotificationPolicyFilterConditions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions">NotificationPolicyFilterConditions</a>]]

---

##### `type_input`<sup>Optional</sup> <a name="type_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.typeInput"></a>

```python
type_input: str
```

- *Type:* str

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.type"></a>

```python
type: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, NotificationPolicyFilter]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter">NotificationPolicyFilter</a>]

---


### NotificationPolicyTimeRestrictionList <a name="NotificationPolicyTimeRestrictionList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyTimeRestrictionList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> NotificationPolicyTimeRestrictionOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction">NotificationPolicyTimeRestriction</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[NotificationPolicyTimeRestriction]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction">NotificationPolicyTimeRestriction</a>]]

---


### NotificationPolicyTimeRestrictionOutputReference <a name="NotificationPolicyTimeRestrictionOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyTimeRestrictionOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.putRestriction">put_restriction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.putRestrictions">put_restrictions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.resetRestriction">reset_restriction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.resetRestrictions">reset_restrictions</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `put_restriction` <a name="put_restriction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.putRestriction"></a>

```python
def put_restriction(
  value: typing.Union[IResolvable, typing.List[NotificationPolicyTimeRestrictionRestriction]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.putRestriction.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction">NotificationPolicyTimeRestrictionRestriction</a>]]

---

##### `put_restrictions` <a name="put_restrictions" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.putRestrictions"></a>

```python
def put_restrictions(
  value: typing.Union[IResolvable, typing.List[NotificationPolicyTimeRestrictionRestrictions]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.putRestrictions.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions">NotificationPolicyTimeRestrictionRestrictions</a>]]

---

##### `reset_restriction` <a name="reset_restriction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.resetRestriction"></a>

```python
def reset_restriction() -> None
```

##### `reset_restrictions` <a name="reset_restrictions" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.resetRestrictions"></a>

```python
def reset_restrictions() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.restriction">restriction</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList">NotificationPolicyTimeRestrictionRestrictionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.restrictions">restrictions</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList">NotificationPolicyTimeRestrictionRestrictionsList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.restrictionInput">restriction_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction">NotificationPolicyTimeRestrictionRestriction</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.restrictionsInput">restrictions_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions">NotificationPolicyTimeRestrictionRestrictions</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.typeInput">type_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.type">type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction">NotificationPolicyTimeRestriction</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `restriction`<sup>Required</sup> <a name="restriction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.restriction"></a>

```python
restriction: NotificationPolicyTimeRestrictionRestrictionList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList">NotificationPolicyTimeRestrictionRestrictionList</a>

---

##### `restrictions`<sup>Required</sup> <a name="restrictions" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.restrictions"></a>

```python
restrictions: NotificationPolicyTimeRestrictionRestrictionsList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList">NotificationPolicyTimeRestrictionRestrictionsList</a>

---

##### `restriction_input`<sup>Optional</sup> <a name="restriction_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.restrictionInput"></a>

```python
restriction_input: typing.Union[IResolvable, typing.List[NotificationPolicyTimeRestrictionRestriction]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction">NotificationPolicyTimeRestrictionRestriction</a>]]

---

##### `restrictions_input`<sup>Optional</sup> <a name="restrictions_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.restrictionsInput"></a>

```python
restrictions_input: typing.Union[IResolvable, typing.List[NotificationPolicyTimeRestrictionRestrictions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions">NotificationPolicyTimeRestrictionRestrictions</a>]]

---

##### `type_input`<sup>Optional</sup> <a name="type_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.typeInput"></a>

```python
type_input: str
```

- *Type:* str

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.type"></a>

```python
type: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, NotificationPolicyTimeRestriction]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction">NotificationPolicyTimeRestriction</a>]

---


### NotificationPolicyTimeRestrictionRestrictionList <a name="NotificationPolicyTimeRestrictionRestrictionList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> NotificationPolicyTimeRestrictionRestrictionOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction">NotificationPolicyTimeRestrictionRestriction</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[NotificationPolicyTimeRestrictionRestriction]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction">NotificationPolicyTimeRestrictionRestriction</a>]]

---


### NotificationPolicyTimeRestrictionRestrictionOutputReference <a name="NotificationPolicyTimeRestrictionRestrictionOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.endHourInput">end_hour_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.endMinInput">end_min_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.startHourInput">start_hour_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.startMinInput">start_min_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.endHour">end_hour</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.endMin">end_min</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.startHour">start_hour</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.startMin">start_min</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction">NotificationPolicyTimeRestrictionRestriction</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `end_hour_input`<sup>Optional</sup> <a name="end_hour_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.endHourInput"></a>

```python
end_hour_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `end_min_input`<sup>Optional</sup> <a name="end_min_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.endMinInput"></a>

```python
end_min_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `start_hour_input`<sup>Optional</sup> <a name="start_hour_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.startHourInput"></a>

```python
start_hour_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `start_min_input`<sup>Optional</sup> <a name="start_min_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.startMinInput"></a>

```python
start_min_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `end_hour`<sup>Required</sup> <a name="end_hour" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.endHour"></a>

```python
end_hour: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `end_min`<sup>Required</sup> <a name="end_min" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.endMin"></a>

```python
end_min: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `start_hour`<sup>Required</sup> <a name="start_hour" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.startHour"></a>

```python
start_hour: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `start_min`<sup>Required</sup> <a name="start_min" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.startMin"></a>

```python
start_min: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, NotificationPolicyTimeRestrictionRestriction]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction">NotificationPolicyTimeRestrictionRestriction</a>]

---


### NotificationPolicyTimeRestrictionRestrictionsList <a name="NotificationPolicyTimeRestrictionRestrictionsList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> NotificationPolicyTimeRestrictionRestrictionsOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions">NotificationPolicyTimeRestrictionRestrictions</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[NotificationPolicyTimeRestrictionRestrictions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions">NotificationPolicyTimeRestrictionRestrictions</a>]]

---


### NotificationPolicyTimeRestrictionRestrictionsOutputReference <a name="NotificationPolicyTimeRestrictionRestrictionsOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import notification_policy

notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.endDayInput">end_day_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.endHourInput">end_hour_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.endMinInput">end_min_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.startDayInput">start_day_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.startHourInput">start_hour_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.startMinInput">start_min_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.endDay">end_day</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.endHour">end_hour</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.endMin">end_min</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.startDay">start_day</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.startHour">start_hour</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.startMin">start_min</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions">NotificationPolicyTimeRestrictionRestrictions</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `end_day_input`<sup>Optional</sup> <a name="end_day_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.endDayInput"></a>

```python
end_day_input: str
```

- *Type:* str

---

##### `end_hour_input`<sup>Optional</sup> <a name="end_hour_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.endHourInput"></a>

```python
end_hour_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `end_min_input`<sup>Optional</sup> <a name="end_min_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.endMinInput"></a>

```python
end_min_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `start_day_input`<sup>Optional</sup> <a name="start_day_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.startDayInput"></a>

```python
start_day_input: str
```

- *Type:* str

---

##### `start_hour_input`<sup>Optional</sup> <a name="start_hour_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.startHourInput"></a>

```python
start_hour_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `start_min_input`<sup>Optional</sup> <a name="start_min_input" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.startMinInput"></a>

```python
start_min_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `end_day`<sup>Required</sup> <a name="end_day" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.endDay"></a>

```python
end_day: str
```

- *Type:* str

---

##### `end_hour`<sup>Required</sup> <a name="end_hour" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.endHour"></a>

```python
end_hour: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `end_min`<sup>Required</sup> <a name="end_min" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.endMin"></a>

```python
end_min: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `start_day`<sup>Required</sup> <a name="start_day" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.startDay"></a>

```python
start_day: str
```

- *Type:* str

---

##### `start_hour`<sup>Required</sup> <a name="start_hour" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.startHour"></a>

```python
start_hour: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `start_min`<sup>Required</sup> <a name="start_min" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.startMin"></a>

```python
start_min: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, NotificationPolicyTimeRestrictionRestrictions]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions">NotificationPolicyTimeRestrictionRestrictions</a>]

---



