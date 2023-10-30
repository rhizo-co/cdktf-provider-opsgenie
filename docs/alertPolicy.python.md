# `opsgenie_alert_policy`

Refer to the Terraform Registory for docs: [`opsgenie_alert_policy`](https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy).

# `alertPolicy` Submodule <a name="`alertPolicy` Submodule" id="rhizo-co-terraform-provider-opsgenie.alertPolicy"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### AlertPolicy <a name="AlertPolicy" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy"></a>

Represents a {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy opsgenie_alert_policy}.

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import alert_policy

alertPolicy.AlertPolicy(
  scope: Construct,
  id: str,
  connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection] = None,
  count: typing.Union[typing.Union[int, float], TerraformCount] = None,
  depends_on: typing.List[ITerraformDependable] = None,
  for_each: ITerraformIterator = None,
  lifecycle: TerraformResourceLifecycle = None,
  provider: TerraformProvider = None,
  provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]] = None,
  message: str,
  name: str,
  actions: typing.List[str] = None,
  alert_description: str = None,
  alias: str = None,
  continue_policy: typing.Union[bool, IResolvable] = None,
  enabled: typing.Union[bool, IResolvable] = None,
  entity: str = None,
  filter: typing.Union[IResolvable, typing.List[AlertPolicyFilter]] = None,
  id: str = None,
  ignore_original_actions: typing.Union[bool, IResolvable] = None,
  ignore_original_details: typing.Union[bool, IResolvable] = None,
  ignore_original_responders: typing.Union[bool, IResolvable] = None,
  ignore_original_tags: typing.Union[bool, IResolvable] = None,
  policy_description: str = None,
  priority: str = None,
  responders: typing.Union[IResolvable, typing.List[AlertPolicyResponders]] = None,
  source: str = None,
  tags: typing.List[str] = None,
  team_id: str = None,
  time_restriction: typing.Union[IResolvable, typing.List[AlertPolicyTimeRestriction]] = None
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.id">id</a></code> | <code>str</code> | The scoped construct ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.connection">connection</a></code> | <code>typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.dependsOn">depends_on</a></code> | <code>typing.List[cdktf.ITerraformDependable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.provisioners">provisioners</a></code> | <code>typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.message">message</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#message AlertPolicy#message}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.name">name</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#name AlertPolicy#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.actions">actions</a></code> | <code>typing.List[str]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#actions AlertPolicy#actions}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.alertDescription">alert_description</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#alert_description AlertPolicy#alert_description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.alias">alias</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#alias AlertPolicy#alias}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.continuePolicy">continue_policy</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#continue_policy AlertPolicy#continue_policy}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.enabled">enabled</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#enabled AlertPolicy#enabled}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.entity">entity</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#entity AlertPolicy#entity}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.filter">filter</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilter">AlertPolicyFilter</a>]]</code> | filter block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.id">id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#id AlertPolicy#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.ignoreOriginalActions">ignore_original_actions</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#ignore_original_actions AlertPolicy#ignore_original_actions}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.ignoreOriginalDetails">ignore_original_details</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#ignore_original_details AlertPolicy#ignore_original_details}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.ignoreOriginalResponders">ignore_original_responders</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#ignore_original_responders AlertPolicy#ignore_original_responders}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.ignoreOriginalTags">ignore_original_tags</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#ignore_original_tags AlertPolicy#ignore_original_tags}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.policyDescription">policy_description</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#policy_description AlertPolicy#policy_description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.priority">priority</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#priority AlertPolicy#priority}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.responders">responders</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders">AlertPolicyResponders</a>]]</code> | responders block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.source">source</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#source AlertPolicy#source}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.tags">tags</a></code> | <code>typing.List[str]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#tags AlertPolicy#tags}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.teamId">team_id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#team_id AlertPolicy#team_id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.timeRestriction">time_restriction</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction">AlertPolicyTimeRestriction</a>]]</code> | time_restriction block. |

---

##### `scope`<sup>Required</sup> <a name="scope" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.id"></a>

- *Type:* str

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.connection"></a>

- *Type:* typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.count"></a>

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.dependsOn"></a>

- *Type:* typing.List[cdktf.ITerraformDependable]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.forEach"></a>

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.lifecycle"></a>

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.provider"></a>

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.provisioners"></a>

- *Type:* typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]

---

##### `message`<sup>Required</sup> <a name="message" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.message"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#message AlertPolicy#message}.

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.name"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#name AlertPolicy#name}.

---

##### `actions`<sup>Optional</sup> <a name="actions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.actions"></a>

- *Type:* typing.List[str]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#actions AlertPolicy#actions}.

---

##### `alert_description`<sup>Optional</sup> <a name="alert_description" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.alertDescription"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#alert_description AlertPolicy#alert_description}.

---

##### `alias`<sup>Optional</sup> <a name="alias" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.alias"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#alias AlertPolicy#alias}.

---

##### `continue_policy`<sup>Optional</sup> <a name="continue_policy" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.continuePolicy"></a>

- *Type:* typing.Union[bool, cdktf.IResolvable]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#continue_policy AlertPolicy#continue_policy}.

---

##### `enabled`<sup>Optional</sup> <a name="enabled" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.enabled"></a>

- *Type:* typing.Union[bool, cdktf.IResolvable]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#enabled AlertPolicy#enabled}.

---

##### `entity`<sup>Optional</sup> <a name="entity" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.entity"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#entity AlertPolicy#entity}.

---

##### `filter`<sup>Optional</sup> <a name="filter" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.filter"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilter">AlertPolicyFilter</a>]]

filter block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#filter AlertPolicy#filter}

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.id"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#id AlertPolicy#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `ignore_original_actions`<sup>Optional</sup> <a name="ignore_original_actions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.ignoreOriginalActions"></a>

- *Type:* typing.Union[bool, cdktf.IResolvable]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#ignore_original_actions AlertPolicy#ignore_original_actions}.

---

##### `ignore_original_details`<sup>Optional</sup> <a name="ignore_original_details" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.ignoreOriginalDetails"></a>

- *Type:* typing.Union[bool, cdktf.IResolvable]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#ignore_original_details AlertPolicy#ignore_original_details}.

---

##### `ignore_original_responders`<sup>Optional</sup> <a name="ignore_original_responders" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.ignoreOriginalResponders"></a>

- *Type:* typing.Union[bool, cdktf.IResolvable]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#ignore_original_responders AlertPolicy#ignore_original_responders}.

---

##### `ignore_original_tags`<sup>Optional</sup> <a name="ignore_original_tags" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.ignoreOriginalTags"></a>

- *Type:* typing.Union[bool, cdktf.IResolvable]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#ignore_original_tags AlertPolicy#ignore_original_tags}.

---

##### `policy_description`<sup>Optional</sup> <a name="policy_description" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.policyDescription"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#policy_description AlertPolicy#policy_description}.

---

##### `priority`<sup>Optional</sup> <a name="priority" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.priority"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#priority AlertPolicy#priority}.

---

##### `responders`<sup>Optional</sup> <a name="responders" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.responders"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders">AlertPolicyResponders</a>]]

responders block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#responders AlertPolicy#responders}

---

##### `source`<sup>Optional</sup> <a name="source" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.source"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#source AlertPolicy#source}.

---

##### `tags`<sup>Optional</sup> <a name="tags" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.tags"></a>

- *Type:* typing.List[str]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#tags AlertPolicy#tags}.

---

##### `team_id`<sup>Optional</sup> <a name="team_id" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.teamId"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#team_id AlertPolicy#team_id}.

---

##### `time_restriction`<sup>Optional</sup> <a name="time_restriction" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.timeRestriction"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction">AlertPolicyTimeRestriction</a>]]

time_restriction block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#time_restriction AlertPolicy#time_restriction}

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.toString">to_string</a></code> | Returns a string representation of this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.addOverride">add_override</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.overrideLogicalId">override_logical_id</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetOverrideLogicalId">reset_override_logical_id</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.toMetadata">to_metadata</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.toTerraform">to_terraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.putFilter">put_filter</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.putResponders">put_responders</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.putTimeRestriction">put_time_restriction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetActions">reset_actions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetAlertDescription">reset_alert_description</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetAlias">reset_alias</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetContinuePolicy">reset_continue_policy</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetEnabled">reset_enabled</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetEntity">reset_entity</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetFilter">reset_filter</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetId">reset_id</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetIgnoreOriginalActions">reset_ignore_original_actions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetIgnoreOriginalDetails">reset_ignore_original_details</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetIgnoreOriginalResponders">reset_ignore_original_responders</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetIgnoreOriginalTags">reset_ignore_original_tags</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetPolicyDescription">reset_policy_description</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetPriority">reset_priority</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetResponders">reset_responders</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetSource">reset_source</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetTags">reset_tags</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetTeamId">reset_team_id</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetTimeRestriction">reset_time_restriction</a></code> | *No description.* |

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.toString"></a>

```python
def to_string() -> str
```

Returns a string representation of this construct.

##### `add_override` <a name="add_override" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.addOverride"></a>

```python
def add_override(
  path: str,
  value: typing.Any
) -> None
```

###### `path`<sup>Required</sup> <a name="path" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.addOverride.parameter.path"></a>

- *Type:* str

---

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.addOverride.parameter.value"></a>

- *Type:* typing.Any

---

##### `override_logical_id` <a name="override_logical_id" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.overrideLogicalId"></a>

```python
def override_logical_id(
  new_logical_id: str
) -> None
```

Overrides the auto-generated logical ID with a specific ID.

###### `new_logical_id`<sup>Required</sup> <a name="new_logical_id" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* str

The new logical ID to use for this stack element.

---

##### `reset_override_logical_id` <a name="reset_override_logical_id" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetOverrideLogicalId"></a>

```python
def reset_override_logical_id() -> None
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `to_metadata` <a name="to_metadata" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.toMetadata"></a>

```python
def to_metadata() -> typing.Any
```

##### `to_terraform` <a name="to_terraform" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.toTerraform"></a>

```python
def to_terraform() -> typing.Any
```

Adds this resource to the terraform JSON output.

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `put_filter` <a name="put_filter" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.putFilter"></a>

```python
def put_filter(
  value: typing.Union[IResolvable, typing.List[AlertPolicyFilter]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.putFilter.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilter">AlertPolicyFilter</a>]]

---

##### `put_responders` <a name="put_responders" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.putResponders"></a>

```python
def put_responders(
  value: typing.Union[IResolvable, typing.List[AlertPolicyResponders]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.putResponders.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders">AlertPolicyResponders</a>]]

---

##### `put_time_restriction` <a name="put_time_restriction" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.putTimeRestriction"></a>

```python
def put_time_restriction(
  value: typing.Union[IResolvable, typing.List[AlertPolicyTimeRestriction]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.putTimeRestriction.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction">AlertPolicyTimeRestriction</a>]]

---

##### `reset_actions` <a name="reset_actions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetActions"></a>

```python
def reset_actions() -> None
```

##### `reset_alert_description` <a name="reset_alert_description" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetAlertDescription"></a>

```python
def reset_alert_description() -> None
```

##### `reset_alias` <a name="reset_alias" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetAlias"></a>

```python
def reset_alias() -> None
```

##### `reset_continue_policy` <a name="reset_continue_policy" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetContinuePolicy"></a>

```python
def reset_continue_policy() -> None
```

##### `reset_enabled` <a name="reset_enabled" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetEnabled"></a>

```python
def reset_enabled() -> None
```

##### `reset_entity` <a name="reset_entity" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetEntity"></a>

```python
def reset_entity() -> None
```

##### `reset_filter` <a name="reset_filter" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetFilter"></a>

```python
def reset_filter() -> None
```

##### `reset_id` <a name="reset_id" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetId"></a>

```python
def reset_id() -> None
```

##### `reset_ignore_original_actions` <a name="reset_ignore_original_actions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetIgnoreOriginalActions"></a>

```python
def reset_ignore_original_actions() -> None
```

##### `reset_ignore_original_details` <a name="reset_ignore_original_details" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetIgnoreOriginalDetails"></a>

```python
def reset_ignore_original_details() -> None
```

##### `reset_ignore_original_responders` <a name="reset_ignore_original_responders" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetIgnoreOriginalResponders"></a>

```python
def reset_ignore_original_responders() -> None
```

##### `reset_ignore_original_tags` <a name="reset_ignore_original_tags" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetIgnoreOriginalTags"></a>

```python
def reset_ignore_original_tags() -> None
```

##### `reset_policy_description` <a name="reset_policy_description" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetPolicyDescription"></a>

```python
def reset_policy_description() -> None
```

##### `reset_priority` <a name="reset_priority" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetPriority"></a>

```python
def reset_priority() -> None
```

##### `reset_responders` <a name="reset_responders" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetResponders"></a>

```python
def reset_responders() -> None
```

##### `reset_source` <a name="reset_source" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetSource"></a>

```python
def reset_source() -> None
```

##### `reset_tags` <a name="reset_tags" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetTags"></a>

```python
def reset_tags() -> None
```

##### `reset_team_id` <a name="reset_team_id" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetTeamId"></a>

```python
def reset_team_id() -> None
```

##### `reset_time_restriction` <a name="reset_time_restriction" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetTimeRestriction"></a>

```python
def reset_time_restriction() -> None
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.isConstruct">is_construct</a></code> | Checks if `x` is a construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.isTerraformElement">is_terraform_element</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.isTerraformResource">is_terraform_resource</a></code> | *No description.* |

---

##### `is_construct` <a name="is_construct" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.isConstruct"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import alert_policy

alertPolicy.AlertPolicy.is_construct(
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

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.isConstruct.parameter.x"></a>

- *Type:* typing.Any

Any object.

---

##### `is_terraform_element` <a name="is_terraform_element" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.isTerraformElement"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import alert_policy

alertPolicy.AlertPolicy.is_terraform_element(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.isTerraformElement.parameter.x"></a>

- *Type:* typing.Any

---

##### `is_terraform_resource` <a name="is_terraform_resource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.isTerraformResource"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import alert_policy

alertPolicy.AlertPolicy.is_terraform_resource(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.isTerraformResource.parameter.x"></a>

- *Type:* typing.Any

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.node">node</a></code> | <code>constructs.Node</code> | The tree node. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.cdktfStack">cdktf_stack</a></code> | <code>cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.friendlyUniqueId">friendly_unique_id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.terraformMetaArguments">terraform_meta_arguments</a></code> | <code>typing.Mapping[typing.Any]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.terraformResourceType">terraform_resource_type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.terraformGeneratorMetadata">terraform_generator_metadata</a></code> | <code>cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.connection">connection</a></code> | <code>typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.dependsOn">depends_on</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.provisioners">provisioners</a></code> | <code>typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.filter">filter</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList">AlertPolicyFilterList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.responders">responders</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList">AlertPolicyRespondersList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.timeRestriction">time_restriction</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList">AlertPolicyTimeRestrictionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.actionsInput">actions_input</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.alertDescriptionInput">alert_description_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.aliasInput">alias_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.continuePolicyInput">continue_policy_input</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.enabledInput">enabled_input</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.entityInput">entity_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.filterInput">filter_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilter">AlertPolicyFilter</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.idInput">id_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalActionsInput">ignore_original_actions_input</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalDetailsInput">ignore_original_details_input</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalRespondersInput">ignore_original_responders_input</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalTagsInput">ignore_original_tags_input</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.messageInput">message_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.nameInput">name_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.policyDescriptionInput">policy_description_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.priorityInput">priority_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.respondersInput">responders_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders">AlertPolicyResponders</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.sourceInput">source_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.tagsInput">tags_input</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.teamIdInput">team_id_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.timeRestrictionInput">time_restriction_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction">AlertPolicyTimeRestriction</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.actions">actions</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.alertDescription">alert_description</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.alias">alias</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.continuePolicy">continue_policy</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.enabled">enabled</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.entity">entity</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.id">id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalActions">ignore_original_actions</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalDetails">ignore_original_details</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalResponders">ignore_original_responders</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalTags">ignore_original_tags</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.message">message</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.name">name</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.policyDescription">policy_description</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.priority">priority</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.source">source</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.tags">tags</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.teamId">team_id</a></code> | <code>str</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.node"></a>

```python
node: Node
```

- *Type:* constructs.Node

The tree node.

---

##### `cdktf_stack`<sup>Required</sup> <a name="cdktf_stack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.cdktfStack"></a>

```python
cdktf_stack: TerraformStack
```

- *Type:* cdktf.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `friendly_unique_id`<sup>Required</sup> <a name="friendly_unique_id" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.friendlyUniqueId"></a>

```python
friendly_unique_id: str
```

- *Type:* str

---

##### `terraform_meta_arguments`<sup>Required</sup> <a name="terraform_meta_arguments" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.terraformMetaArguments"></a>

```python
terraform_meta_arguments: typing.Mapping[typing.Any]
```

- *Type:* typing.Mapping[typing.Any]

---

##### `terraform_resource_type`<sup>Required</sup> <a name="terraform_resource_type" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.terraformResourceType"></a>

```python
terraform_resource_type: str
```

- *Type:* str

---

##### `terraform_generator_metadata`<sup>Optional</sup> <a name="terraform_generator_metadata" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.terraformGeneratorMetadata"></a>

```python
terraform_generator_metadata: TerraformProviderGeneratorMetadata
```

- *Type:* cdktf.TerraformProviderGeneratorMetadata

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.connection"></a>

```python
connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection]
```

- *Type:* typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.count"></a>

```python
count: typing.Union[typing.Union[int, float], TerraformCount]
```

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.dependsOn"></a>

```python
depends_on: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.forEach"></a>

```python
for_each: ITerraformIterator
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.lifecycle"></a>

```python
lifecycle: TerraformResourceLifecycle
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.provider"></a>

```python
provider: TerraformProvider
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.provisioners"></a>

```python
provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]]
```

- *Type:* typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]

---

##### `filter`<sup>Required</sup> <a name="filter" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.filter"></a>

```python
filter: AlertPolicyFilterList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList">AlertPolicyFilterList</a>

---

##### `responders`<sup>Required</sup> <a name="responders" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.responders"></a>

```python
responders: AlertPolicyRespondersList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList">AlertPolicyRespondersList</a>

---

##### `time_restriction`<sup>Required</sup> <a name="time_restriction" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.timeRestriction"></a>

```python
time_restriction: AlertPolicyTimeRestrictionList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList">AlertPolicyTimeRestrictionList</a>

---

##### `actions_input`<sup>Optional</sup> <a name="actions_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.actionsInput"></a>

```python
actions_input: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `alert_description_input`<sup>Optional</sup> <a name="alert_description_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.alertDescriptionInput"></a>

```python
alert_description_input: str
```

- *Type:* str

---

##### `alias_input`<sup>Optional</sup> <a name="alias_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.aliasInput"></a>

```python
alias_input: str
```

- *Type:* str

---

##### `continue_policy_input`<sup>Optional</sup> <a name="continue_policy_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.continuePolicyInput"></a>

```python
continue_policy_input: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `enabled_input`<sup>Optional</sup> <a name="enabled_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.enabledInput"></a>

```python
enabled_input: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `entity_input`<sup>Optional</sup> <a name="entity_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.entityInput"></a>

```python
entity_input: str
```

- *Type:* str

---

##### `filter_input`<sup>Optional</sup> <a name="filter_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.filterInput"></a>

```python
filter_input: typing.Union[IResolvable, typing.List[AlertPolicyFilter]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilter">AlertPolicyFilter</a>]]

---

##### `id_input`<sup>Optional</sup> <a name="id_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.idInput"></a>

```python
id_input: str
```

- *Type:* str

---

##### `ignore_original_actions_input`<sup>Optional</sup> <a name="ignore_original_actions_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalActionsInput"></a>

```python
ignore_original_actions_input: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `ignore_original_details_input`<sup>Optional</sup> <a name="ignore_original_details_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalDetailsInput"></a>

```python
ignore_original_details_input: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `ignore_original_responders_input`<sup>Optional</sup> <a name="ignore_original_responders_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalRespondersInput"></a>

```python
ignore_original_responders_input: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `ignore_original_tags_input`<sup>Optional</sup> <a name="ignore_original_tags_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalTagsInput"></a>

```python
ignore_original_tags_input: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `message_input`<sup>Optional</sup> <a name="message_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.messageInput"></a>

```python
message_input: str
```

- *Type:* str

---

##### `name_input`<sup>Optional</sup> <a name="name_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.nameInput"></a>

```python
name_input: str
```

- *Type:* str

---

##### `policy_description_input`<sup>Optional</sup> <a name="policy_description_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.policyDescriptionInput"></a>

```python
policy_description_input: str
```

- *Type:* str

---

##### `priority_input`<sup>Optional</sup> <a name="priority_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.priorityInput"></a>

```python
priority_input: str
```

- *Type:* str

---

##### `responders_input`<sup>Optional</sup> <a name="responders_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.respondersInput"></a>

```python
responders_input: typing.Union[IResolvable, typing.List[AlertPolicyResponders]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders">AlertPolicyResponders</a>]]

---

##### `source_input`<sup>Optional</sup> <a name="source_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.sourceInput"></a>

```python
source_input: str
```

- *Type:* str

---

##### `tags_input`<sup>Optional</sup> <a name="tags_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.tagsInput"></a>

```python
tags_input: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `team_id_input`<sup>Optional</sup> <a name="team_id_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.teamIdInput"></a>

```python
team_id_input: str
```

- *Type:* str

---

##### `time_restriction_input`<sup>Optional</sup> <a name="time_restriction_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.timeRestrictionInput"></a>

```python
time_restriction_input: typing.Union[IResolvable, typing.List[AlertPolicyTimeRestriction]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction">AlertPolicyTimeRestriction</a>]]

---

##### `actions`<sup>Required</sup> <a name="actions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.actions"></a>

```python
actions: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `alert_description`<sup>Required</sup> <a name="alert_description" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.alertDescription"></a>

```python
alert_description: str
```

- *Type:* str

---

##### `alias`<sup>Required</sup> <a name="alias" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.alias"></a>

```python
alias: str
```

- *Type:* str

---

##### `continue_policy`<sup>Required</sup> <a name="continue_policy" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.continuePolicy"></a>

```python
continue_policy: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `enabled`<sup>Required</sup> <a name="enabled" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.enabled"></a>

```python
enabled: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `entity`<sup>Required</sup> <a name="entity" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.entity"></a>

```python
entity: str
```

- *Type:* str

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.id"></a>

```python
id: str
```

- *Type:* str

---

##### `ignore_original_actions`<sup>Required</sup> <a name="ignore_original_actions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalActions"></a>

```python
ignore_original_actions: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `ignore_original_details`<sup>Required</sup> <a name="ignore_original_details" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalDetails"></a>

```python
ignore_original_details: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `ignore_original_responders`<sup>Required</sup> <a name="ignore_original_responders" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalResponders"></a>

```python
ignore_original_responders: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `ignore_original_tags`<sup>Required</sup> <a name="ignore_original_tags" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalTags"></a>

```python
ignore_original_tags: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `message`<sup>Required</sup> <a name="message" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.message"></a>

```python
message: str
```

- *Type:* str

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.name"></a>

```python
name: str
```

- *Type:* str

---

##### `policy_description`<sup>Required</sup> <a name="policy_description" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.policyDescription"></a>

```python
policy_description: str
```

- *Type:* str

---

##### `priority`<sup>Required</sup> <a name="priority" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.priority"></a>

```python
priority: str
```

- *Type:* str

---

##### `source`<sup>Required</sup> <a name="source" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.source"></a>

```python
source: str
```

- *Type:* str

---

##### `tags`<sup>Required</sup> <a name="tags" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.tags"></a>

```python
tags: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `team_id`<sup>Required</sup> <a name="team_id" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.teamId"></a>

```python
team_id: str
```

- *Type:* str

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.tfResourceType">tfResourceType</a></code> | <code>str</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.tfResourceType"></a>

```python
tfResourceType: str
```

- *Type:* str

---

## Structs <a name="Structs" id="Structs"></a>

### AlertPolicyConfig <a name="AlertPolicyConfig" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import alert_policy

alertPolicy.AlertPolicyConfig(
  connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection] = None,
  count: typing.Union[typing.Union[int, float], TerraformCount] = None,
  depends_on: typing.List[ITerraformDependable] = None,
  for_each: ITerraformIterator = None,
  lifecycle: TerraformResourceLifecycle = None,
  provider: TerraformProvider = None,
  provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]] = None,
  message: str,
  name: str,
  actions: typing.List[str] = None,
  alert_description: str = None,
  alias: str = None,
  continue_policy: typing.Union[bool, IResolvable] = None,
  enabled: typing.Union[bool, IResolvable] = None,
  entity: str = None,
  filter: typing.Union[IResolvable, typing.List[AlertPolicyFilter]] = None,
  id: str = None,
  ignore_original_actions: typing.Union[bool, IResolvable] = None,
  ignore_original_details: typing.Union[bool, IResolvable] = None,
  ignore_original_responders: typing.Union[bool, IResolvable] = None,
  ignore_original_tags: typing.Union[bool, IResolvable] = None,
  policy_description: str = None,
  priority: str = None,
  responders: typing.Union[IResolvable, typing.List[AlertPolicyResponders]] = None,
  source: str = None,
  tags: typing.List[str] = None,
  team_id: str = None,
  time_restriction: typing.Union[IResolvable, typing.List[AlertPolicyTimeRestriction]] = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.connection">connection</a></code> | <code>typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.dependsOn">depends_on</a></code> | <code>typing.List[cdktf.ITerraformDependable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.provisioners">provisioners</a></code> | <code>typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.message">message</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#message AlertPolicy#message}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.name">name</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#name AlertPolicy#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.actions">actions</a></code> | <code>typing.List[str]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#actions AlertPolicy#actions}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.alertDescription">alert_description</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#alert_description AlertPolicy#alert_description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.alias">alias</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#alias AlertPolicy#alias}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.continuePolicy">continue_policy</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#continue_policy AlertPolicy#continue_policy}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.enabled">enabled</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#enabled AlertPolicy#enabled}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.entity">entity</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#entity AlertPolicy#entity}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.filter">filter</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilter">AlertPolicyFilter</a>]]</code> | filter block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.id">id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#id AlertPolicy#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.ignoreOriginalActions">ignore_original_actions</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#ignore_original_actions AlertPolicy#ignore_original_actions}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.ignoreOriginalDetails">ignore_original_details</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#ignore_original_details AlertPolicy#ignore_original_details}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.ignoreOriginalResponders">ignore_original_responders</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#ignore_original_responders AlertPolicy#ignore_original_responders}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.ignoreOriginalTags">ignore_original_tags</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#ignore_original_tags AlertPolicy#ignore_original_tags}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.policyDescription">policy_description</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#policy_description AlertPolicy#policy_description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.priority">priority</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#priority AlertPolicy#priority}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.responders">responders</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders">AlertPolicyResponders</a>]]</code> | responders block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.source">source</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#source AlertPolicy#source}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.tags">tags</a></code> | <code>typing.List[str]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#tags AlertPolicy#tags}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.teamId">team_id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#team_id AlertPolicy#team_id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.timeRestriction">time_restriction</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction">AlertPolicyTimeRestriction</a>]]</code> | time_restriction block. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.connection"></a>

```python
connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection]
```

- *Type:* typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.count"></a>

```python
count: typing.Union[typing.Union[int, float], TerraformCount]
```

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.dependsOn"></a>

```python
depends_on: typing.List[ITerraformDependable]
```

- *Type:* typing.List[cdktf.ITerraformDependable]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.forEach"></a>

```python
for_each: ITerraformIterator
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.lifecycle"></a>

```python
lifecycle: TerraformResourceLifecycle
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.provider"></a>

```python
provider: TerraformProvider
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.provisioners"></a>

```python
provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]]
```

- *Type:* typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]

---

##### `message`<sup>Required</sup> <a name="message" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.message"></a>

```python
message: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#message AlertPolicy#message}.

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.name"></a>

```python
name: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#name AlertPolicy#name}.

---

##### `actions`<sup>Optional</sup> <a name="actions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.actions"></a>

```python
actions: typing.List[str]
```

- *Type:* typing.List[str]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#actions AlertPolicy#actions}.

---

##### `alert_description`<sup>Optional</sup> <a name="alert_description" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.alertDescription"></a>

```python
alert_description: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#alert_description AlertPolicy#alert_description}.

---

##### `alias`<sup>Optional</sup> <a name="alias" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.alias"></a>

```python
alias: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#alias AlertPolicy#alias}.

---

##### `continue_policy`<sup>Optional</sup> <a name="continue_policy" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.continuePolicy"></a>

```python
continue_policy: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#continue_policy AlertPolicy#continue_policy}.

---

##### `enabled`<sup>Optional</sup> <a name="enabled" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.enabled"></a>

```python
enabled: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#enabled AlertPolicy#enabled}.

---

##### `entity`<sup>Optional</sup> <a name="entity" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.entity"></a>

```python
entity: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#entity AlertPolicy#entity}.

---

##### `filter`<sup>Optional</sup> <a name="filter" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.filter"></a>

```python
filter: typing.Union[IResolvable, typing.List[AlertPolicyFilter]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilter">AlertPolicyFilter</a>]]

filter block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#filter AlertPolicy#filter}

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.id"></a>

```python
id: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#id AlertPolicy#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `ignore_original_actions`<sup>Optional</sup> <a name="ignore_original_actions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.ignoreOriginalActions"></a>

```python
ignore_original_actions: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#ignore_original_actions AlertPolicy#ignore_original_actions}.

---

##### `ignore_original_details`<sup>Optional</sup> <a name="ignore_original_details" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.ignoreOriginalDetails"></a>

```python
ignore_original_details: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#ignore_original_details AlertPolicy#ignore_original_details}.

---

##### `ignore_original_responders`<sup>Optional</sup> <a name="ignore_original_responders" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.ignoreOriginalResponders"></a>

```python
ignore_original_responders: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#ignore_original_responders AlertPolicy#ignore_original_responders}.

---

##### `ignore_original_tags`<sup>Optional</sup> <a name="ignore_original_tags" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.ignoreOriginalTags"></a>

```python
ignore_original_tags: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#ignore_original_tags AlertPolicy#ignore_original_tags}.

---

##### `policy_description`<sup>Optional</sup> <a name="policy_description" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.policyDescription"></a>

```python
policy_description: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#policy_description AlertPolicy#policy_description}.

---

##### `priority`<sup>Optional</sup> <a name="priority" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.priority"></a>

```python
priority: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#priority AlertPolicy#priority}.

---

##### `responders`<sup>Optional</sup> <a name="responders" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.responders"></a>

```python
responders: typing.Union[IResolvable, typing.List[AlertPolicyResponders]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders">AlertPolicyResponders</a>]]

responders block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#responders AlertPolicy#responders}

---

##### `source`<sup>Optional</sup> <a name="source" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.source"></a>

```python
source: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#source AlertPolicy#source}.

---

##### `tags`<sup>Optional</sup> <a name="tags" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.tags"></a>

```python
tags: typing.List[str]
```

- *Type:* typing.List[str]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#tags AlertPolicy#tags}.

---

##### `team_id`<sup>Optional</sup> <a name="team_id" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.teamId"></a>

```python
team_id: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#team_id AlertPolicy#team_id}.

---

##### `time_restriction`<sup>Optional</sup> <a name="time_restriction" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.timeRestriction"></a>

```python
time_restriction: typing.Union[IResolvable, typing.List[AlertPolicyTimeRestriction]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction">AlertPolicyTimeRestriction</a>]]

time_restriction block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#time_restriction AlertPolicy#time_restriction}

---

### AlertPolicyFilter <a name="AlertPolicyFilter" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilter"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilter.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import alert_policy

alertPolicy.AlertPolicyFilter(
  conditions: typing.Union[IResolvable, typing.List[AlertPolicyFilterConditions]] = None,
  type: str = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilter.property.conditions">conditions</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions">AlertPolicyFilterConditions</a>]]</code> | conditions block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilter.property.type">type</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#type AlertPolicy#type}. |

---

##### `conditions`<sup>Optional</sup> <a name="conditions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilter.property.conditions"></a>

```python
conditions: typing.Union[IResolvable, typing.List[AlertPolicyFilterConditions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions">AlertPolicyFilterConditions</a>]]

conditions block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#conditions AlertPolicy#conditions}

---

##### `type`<sup>Optional</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilter.property.type"></a>

```python
type: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#type AlertPolicy#type}.

---

### AlertPolicyFilterConditions <a name="AlertPolicyFilterConditions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import alert_policy

alertPolicy.AlertPolicyFilterConditions(
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
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.property.field">field</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#field AlertPolicy#field}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.property.operation">operation</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#operation AlertPolicy#operation}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.property.expectedValue">expected_value</a></code> | <code>str</code> | User defined value that will be compared with alert field according to the operation. Default value is empty string. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.property.key">key</a></code> | <code>str</code> | If 'field' is set as 'extra-properties', key could be used for key-value pair. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.property.not">not</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Indicates behaviour of the given operation. Default value is false. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.property.order">order</a></code> | <code>typing.Union[int, float]</code> | Order of the condition in conditions list. |

---

##### `field`<sup>Required</sup> <a name="field" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.property.field"></a>

```python
field: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#field AlertPolicy#field}.

---

##### `operation`<sup>Required</sup> <a name="operation" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.property.operation"></a>

```python
operation: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#operation AlertPolicy#operation}.

---

##### `expected_value`<sup>Optional</sup> <a name="expected_value" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.property.expectedValue"></a>

```python
expected_value: str
```

- *Type:* str

User defined value that will be compared with alert field according to the operation. Default value is empty string.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#expected_value AlertPolicy#expected_value}

---

##### `key`<sup>Optional</sup> <a name="key" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.property.key"></a>

```python
key: str
```

- *Type:* str

If 'field' is set as 'extra-properties', key could be used for key-value pair.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#key AlertPolicy#key}

---

##### `not`<sup>Optional</sup> <a name="not" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.property.not"></a>

```python
not: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

Indicates behaviour of the given operation. Default value is false.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#not AlertPolicy#not}

---

##### `order`<sup>Optional</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.property.order"></a>

```python
order: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Order of the condition in conditions list.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#order AlertPolicy#order}

---

### AlertPolicyResponders <a name="AlertPolicyResponders" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import alert_policy

alertPolicy.AlertPolicyResponders(
  id: str,
  type: str,
  name: str = None,
  username: str = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders.property.id">id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#id AlertPolicy#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders.property.type">type</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#type AlertPolicy#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders.property.name">name</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#name AlertPolicy#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders.property.username">username</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#username AlertPolicy#username}. |

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders.property.id"></a>

```python
id: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#id AlertPolicy#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders.property.type"></a>

```python
type: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#type AlertPolicy#type}.

---

##### `name`<sup>Optional</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders.property.name"></a>

```python
name: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#name AlertPolicy#name}.

---

##### `username`<sup>Optional</sup> <a name="username" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders.property.username"></a>

```python
username: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#username AlertPolicy#username}.

---

### AlertPolicyTimeRestriction <a name="AlertPolicyTimeRestriction" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import alert_policy

alertPolicy.AlertPolicyTimeRestriction(
  type: str,
  restriction: typing.Union[IResolvable, typing.List[AlertPolicyTimeRestrictionRestriction]] = None,
  restrictions: typing.Union[IResolvable, typing.List[AlertPolicyTimeRestrictionRestrictions]] = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction.property.type">type</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#type AlertPolicy#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction.property.restriction">restriction</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction">AlertPolicyTimeRestrictionRestriction</a>]]</code> | restriction block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction.property.restrictions">restrictions</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions">AlertPolicyTimeRestrictionRestrictions</a>]]</code> | restrictions block. |

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction.property.type"></a>

```python
type: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#type AlertPolicy#type}.

---

##### `restriction`<sup>Optional</sup> <a name="restriction" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction.property.restriction"></a>

```python
restriction: typing.Union[IResolvable, typing.List[AlertPolicyTimeRestrictionRestriction]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction">AlertPolicyTimeRestrictionRestriction</a>]]

restriction block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#restriction AlertPolicy#restriction}

---

##### `restrictions`<sup>Optional</sup> <a name="restrictions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction.property.restrictions"></a>

```python
restrictions: typing.Union[IResolvable, typing.List[AlertPolicyTimeRestrictionRestrictions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions">AlertPolicyTimeRestrictionRestrictions</a>]]

restrictions block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#restrictions AlertPolicy#restrictions}

---

### AlertPolicyTimeRestrictionRestriction <a name="AlertPolicyTimeRestrictionRestriction" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import alert_policy

alertPolicy.AlertPolicyTimeRestrictionRestriction(
  end_hour: typing.Union[int, float],
  end_min: typing.Union[int, float],
  start_hour: typing.Union[int, float],
  start_min: typing.Union[int, float]
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction.property.endHour">end_hour</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#end_hour AlertPolicy#end_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction.property.endMin">end_min</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#end_min AlertPolicy#end_min}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction.property.startHour">start_hour</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#start_hour AlertPolicy#start_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction.property.startMin">start_min</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#start_min AlertPolicy#start_min}. |

---

##### `end_hour`<sup>Required</sup> <a name="end_hour" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction.property.endHour"></a>

```python
end_hour: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#end_hour AlertPolicy#end_hour}.

---

##### `end_min`<sup>Required</sup> <a name="end_min" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction.property.endMin"></a>

```python
end_min: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#end_min AlertPolicy#end_min}.

---

##### `start_hour`<sup>Required</sup> <a name="start_hour" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction.property.startHour"></a>

```python
start_hour: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#start_hour AlertPolicy#start_hour}.

---

##### `start_min`<sup>Required</sup> <a name="start_min" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction.property.startMin"></a>

```python
start_min: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#start_min AlertPolicy#start_min}.

---

### AlertPolicyTimeRestrictionRestrictions <a name="AlertPolicyTimeRestrictionRestrictions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import alert_policy

alertPolicy.AlertPolicyTimeRestrictionRestrictions(
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
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.property.endDay">end_day</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#end_day AlertPolicy#end_day}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.property.endHour">end_hour</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#end_hour AlertPolicy#end_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.property.endMin">end_min</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#end_min AlertPolicy#end_min}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.property.startDay">start_day</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#start_day AlertPolicy#start_day}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.property.startHour">start_hour</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#start_hour AlertPolicy#start_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.property.startMin">start_min</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#start_min AlertPolicy#start_min}. |

---

##### `end_day`<sup>Required</sup> <a name="end_day" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.property.endDay"></a>

```python
end_day: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#end_day AlertPolicy#end_day}.

---

##### `end_hour`<sup>Required</sup> <a name="end_hour" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.property.endHour"></a>

```python
end_hour: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#end_hour AlertPolicy#end_hour}.

---

##### `end_min`<sup>Required</sup> <a name="end_min" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.property.endMin"></a>

```python
end_min: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#end_min AlertPolicy#end_min}.

---

##### `start_day`<sup>Required</sup> <a name="start_day" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.property.startDay"></a>

```python
start_day: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#start_day AlertPolicy#start_day}.

---

##### `start_hour`<sup>Required</sup> <a name="start_hour" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.property.startHour"></a>

```python
start_hour: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#start_hour AlertPolicy#start_hour}.

---

##### `start_min`<sup>Required</sup> <a name="start_min" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.property.startMin"></a>

```python
start_min: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#start_min AlertPolicy#start_min}.

---

## Classes <a name="Classes" id="Classes"></a>

### AlertPolicyFilterConditionsList <a name="AlertPolicyFilterConditionsList" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import alert_policy

alertPolicy.AlertPolicyFilterConditionsList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> AlertPolicyFilterConditionsOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions">AlertPolicyFilterConditions</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[AlertPolicyFilterConditions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions">AlertPolicyFilterConditions</a>]]

---


### AlertPolicyFilterConditionsOutputReference <a name="AlertPolicyFilterConditionsOutputReference" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import alert_policy

alertPolicy.AlertPolicyFilterConditionsOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.resetExpectedValue">reset_expected_value</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.resetKey">reset_key</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.resetNot">reset_not</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.resetOrder">reset_order</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `reset_expected_value` <a name="reset_expected_value" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.resetExpectedValue"></a>

```python
def reset_expected_value() -> None
```

##### `reset_key` <a name="reset_key" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.resetKey"></a>

```python
def reset_key() -> None
```

##### `reset_not` <a name="reset_not" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.resetNot"></a>

```python
def reset_not() -> None
```

##### `reset_order` <a name="reset_order" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.resetOrder"></a>

```python
def reset_order() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.expectedValueInput">expected_value_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.fieldInput">field_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.keyInput">key_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.notInput">not_input</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.operationInput">operation_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.orderInput">order_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.expectedValue">expected_value</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.field">field</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.key">key</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.not">not</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.operation">operation</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.order">order</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions">AlertPolicyFilterConditions</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `expected_value_input`<sup>Optional</sup> <a name="expected_value_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.expectedValueInput"></a>

```python
expected_value_input: str
```

- *Type:* str

---

##### `field_input`<sup>Optional</sup> <a name="field_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.fieldInput"></a>

```python
field_input: str
```

- *Type:* str

---

##### `key_input`<sup>Optional</sup> <a name="key_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.keyInput"></a>

```python
key_input: str
```

- *Type:* str

---

##### `not_input`<sup>Optional</sup> <a name="not_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.notInput"></a>

```python
not_input: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `operation_input`<sup>Optional</sup> <a name="operation_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.operationInput"></a>

```python
operation_input: str
```

- *Type:* str

---

##### `order_input`<sup>Optional</sup> <a name="order_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.orderInput"></a>

```python
order_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `expected_value`<sup>Required</sup> <a name="expected_value" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.expectedValue"></a>

```python
expected_value: str
```

- *Type:* str

---

##### `field`<sup>Required</sup> <a name="field" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.field"></a>

```python
field: str
```

- *Type:* str

---

##### `key`<sup>Required</sup> <a name="key" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.key"></a>

```python
key: str
```

- *Type:* str

---

##### `not`<sup>Required</sup> <a name="not" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.not"></a>

```python
not: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `operation`<sup>Required</sup> <a name="operation" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.operation"></a>

```python
operation: str
```

- *Type:* str

---

##### `order`<sup>Required</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.order"></a>

```python
order: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, AlertPolicyFilterConditions]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions">AlertPolicyFilterConditions</a>]

---


### AlertPolicyFilterList <a name="AlertPolicyFilterList" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import alert_policy

alertPolicy.AlertPolicyFilterList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> AlertPolicyFilterOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilter">AlertPolicyFilter</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[AlertPolicyFilter]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilter">AlertPolicyFilter</a>]]

---


### AlertPolicyFilterOutputReference <a name="AlertPolicyFilterOutputReference" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import alert_policy

alertPolicy.AlertPolicyFilterOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.putConditions">put_conditions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.resetConditions">reset_conditions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.resetType">reset_type</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `put_conditions` <a name="put_conditions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.putConditions"></a>

```python
def put_conditions(
  value: typing.Union[IResolvable, typing.List[AlertPolicyFilterConditions]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.putConditions.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions">AlertPolicyFilterConditions</a>]]

---

##### `reset_conditions` <a name="reset_conditions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.resetConditions"></a>

```python
def reset_conditions() -> None
```

##### `reset_type` <a name="reset_type" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.resetType"></a>

```python
def reset_type() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.conditions">conditions</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList">AlertPolicyFilterConditionsList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.conditionsInput">conditions_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions">AlertPolicyFilterConditions</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.typeInput">type_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.type">type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilter">AlertPolicyFilter</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `conditions`<sup>Required</sup> <a name="conditions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.conditions"></a>

```python
conditions: AlertPolicyFilterConditionsList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList">AlertPolicyFilterConditionsList</a>

---

##### `conditions_input`<sup>Optional</sup> <a name="conditions_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.conditionsInput"></a>

```python
conditions_input: typing.Union[IResolvable, typing.List[AlertPolicyFilterConditions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions">AlertPolicyFilterConditions</a>]]

---

##### `type_input`<sup>Optional</sup> <a name="type_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.typeInput"></a>

```python
type_input: str
```

- *Type:* str

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.type"></a>

```python
type: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, AlertPolicyFilter]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilter">AlertPolicyFilter</a>]

---


### AlertPolicyRespondersList <a name="AlertPolicyRespondersList" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import alert_policy

alertPolicy.AlertPolicyRespondersList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> AlertPolicyRespondersOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders">AlertPolicyResponders</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[AlertPolicyResponders]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders">AlertPolicyResponders</a>]]

---


### AlertPolicyRespondersOutputReference <a name="AlertPolicyRespondersOutputReference" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import alert_policy

alertPolicy.AlertPolicyRespondersOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.resetName">reset_name</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.resetUsername">reset_username</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `reset_name` <a name="reset_name" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.resetName"></a>

```python
def reset_name() -> None
```

##### `reset_username` <a name="reset_username" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.resetUsername"></a>

```python
def reset_username() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.idInput">id_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.nameInput">name_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.typeInput">type_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.usernameInput">username_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.id">id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.name">name</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.type">type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.username">username</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders">AlertPolicyResponders</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `id_input`<sup>Optional</sup> <a name="id_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.idInput"></a>

```python
id_input: str
```

- *Type:* str

---

##### `name_input`<sup>Optional</sup> <a name="name_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.nameInput"></a>

```python
name_input: str
```

- *Type:* str

---

##### `type_input`<sup>Optional</sup> <a name="type_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.typeInput"></a>

```python
type_input: str
```

- *Type:* str

---

##### `username_input`<sup>Optional</sup> <a name="username_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.usernameInput"></a>

```python
username_input: str
```

- *Type:* str

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.id"></a>

```python
id: str
```

- *Type:* str

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.name"></a>

```python
name: str
```

- *Type:* str

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.type"></a>

```python
type: str
```

- *Type:* str

---

##### `username`<sup>Required</sup> <a name="username" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.username"></a>

```python
username: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, AlertPolicyResponders]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders">AlertPolicyResponders</a>]

---


### AlertPolicyTimeRestrictionList <a name="AlertPolicyTimeRestrictionList" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import alert_policy

alertPolicy.AlertPolicyTimeRestrictionList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> AlertPolicyTimeRestrictionOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction">AlertPolicyTimeRestriction</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[AlertPolicyTimeRestriction]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction">AlertPolicyTimeRestriction</a>]]

---


### AlertPolicyTimeRestrictionOutputReference <a name="AlertPolicyTimeRestrictionOutputReference" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import alert_policy

alertPolicy.AlertPolicyTimeRestrictionOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.putRestriction">put_restriction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.putRestrictions">put_restrictions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.resetRestriction">reset_restriction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.resetRestrictions">reset_restrictions</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `put_restriction` <a name="put_restriction" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.putRestriction"></a>

```python
def put_restriction(
  value: typing.Union[IResolvable, typing.List[AlertPolicyTimeRestrictionRestriction]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.putRestriction.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction">AlertPolicyTimeRestrictionRestriction</a>]]

---

##### `put_restrictions` <a name="put_restrictions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.putRestrictions"></a>

```python
def put_restrictions(
  value: typing.Union[IResolvable, typing.List[AlertPolicyTimeRestrictionRestrictions]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.putRestrictions.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions">AlertPolicyTimeRestrictionRestrictions</a>]]

---

##### `reset_restriction` <a name="reset_restriction" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.resetRestriction"></a>

```python
def reset_restriction() -> None
```

##### `reset_restrictions` <a name="reset_restrictions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.resetRestrictions"></a>

```python
def reset_restrictions() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.restriction">restriction</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList">AlertPolicyTimeRestrictionRestrictionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.restrictions">restrictions</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList">AlertPolicyTimeRestrictionRestrictionsList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.restrictionInput">restriction_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction">AlertPolicyTimeRestrictionRestriction</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.restrictionsInput">restrictions_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions">AlertPolicyTimeRestrictionRestrictions</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.typeInput">type_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.type">type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction">AlertPolicyTimeRestriction</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `restriction`<sup>Required</sup> <a name="restriction" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.restriction"></a>

```python
restriction: AlertPolicyTimeRestrictionRestrictionList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList">AlertPolicyTimeRestrictionRestrictionList</a>

---

##### `restrictions`<sup>Required</sup> <a name="restrictions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.restrictions"></a>

```python
restrictions: AlertPolicyTimeRestrictionRestrictionsList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList">AlertPolicyTimeRestrictionRestrictionsList</a>

---

##### `restriction_input`<sup>Optional</sup> <a name="restriction_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.restrictionInput"></a>

```python
restriction_input: typing.Union[IResolvable, typing.List[AlertPolicyTimeRestrictionRestriction]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction">AlertPolicyTimeRestrictionRestriction</a>]]

---

##### `restrictions_input`<sup>Optional</sup> <a name="restrictions_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.restrictionsInput"></a>

```python
restrictions_input: typing.Union[IResolvable, typing.List[AlertPolicyTimeRestrictionRestrictions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions">AlertPolicyTimeRestrictionRestrictions</a>]]

---

##### `type_input`<sup>Optional</sup> <a name="type_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.typeInput"></a>

```python
type_input: str
```

- *Type:* str

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.type"></a>

```python
type: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, AlertPolicyTimeRestriction]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction">AlertPolicyTimeRestriction</a>]

---


### AlertPolicyTimeRestrictionRestrictionList <a name="AlertPolicyTimeRestrictionRestrictionList" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import alert_policy

alertPolicy.AlertPolicyTimeRestrictionRestrictionList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> AlertPolicyTimeRestrictionRestrictionOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction">AlertPolicyTimeRestrictionRestriction</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[AlertPolicyTimeRestrictionRestriction]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction">AlertPolicyTimeRestrictionRestriction</a>]]

---


### AlertPolicyTimeRestrictionRestrictionOutputReference <a name="AlertPolicyTimeRestrictionRestrictionOutputReference" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import alert_policy

alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.endHourInput">end_hour_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.endMinInput">end_min_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.startHourInput">start_hour_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.startMinInput">start_min_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.endHour">end_hour</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.endMin">end_min</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.startHour">start_hour</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.startMin">start_min</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction">AlertPolicyTimeRestrictionRestriction</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `end_hour_input`<sup>Optional</sup> <a name="end_hour_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.endHourInput"></a>

```python
end_hour_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `end_min_input`<sup>Optional</sup> <a name="end_min_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.endMinInput"></a>

```python
end_min_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `start_hour_input`<sup>Optional</sup> <a name="start_hour_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.startHourInput"></a>

```python
start_hour_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `start_min_input`<sup>Optional</sup> <a name="start_min_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.startMinInput"></a>

```python
start_min_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `end_hour`<sup>Required</sup> <a name="end_hour" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.endHour"></a>

```python
end_hour: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `end_min`<sup>Required</sup> <a name="end_min" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.endMin"></a>

```python
end_min: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `start_hour`<sup>Required</sup> <a name="start_hour" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.startHour"></a>

```python
start_hour: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `start_min`<sup>Required</sup> <a name="start_min" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.startMin"></a>

```python
start_min: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, AlertPolicyTimeRestrictionRestriction]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction">AlertPolicyTimeRestrictionRestriction</a>]

---


### AlertPolicyTimeRestrictionRestrictionsList <a name="AlertPolicyTimeRestrictionRestrictionsList" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import alert_policy

alertPolicy.AlertPolicyTimeRestrictionRestrictionsList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> AlertPolicyTimeRestrictionRestrictionsOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions">AlertPolicyTimeRestrictionRestrictions</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[AlertPolicyTimeRestrictionRestrictions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions">AlertPolicyTimeRestrictionRestrictions</a>]]

---


### AlertPolicyTimeRestrictionRestrictionsOutputReference <a name="AlertPolicyTimeRestrictionRestrictionsOutputReference" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import alert_policy

alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.endDayInput">end_day_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.endHourInput">end_hour_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.endMinInput">end_min_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.startDayInput">start_day_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.startHourInput">start_hour_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.startMinInput">start_min_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.endDay">end_day</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.endHour">end_hour</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.endMin">end_min</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.startDay">start_day</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.startHour">start_hour</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.startMin">start_min</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions">AlertPolicyTimeRestrictionRestrictions</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `end_day_input`<sup>Optional</sup> <a name="end_day_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.endDayInput"></a>

```python
end_day_input: str
```

- *Type:* str

---

##### `end_hour_input`<sup>Optional</sup> <a name="end_hour_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.endHourInput"></a>

```python
end_hour_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `end_min_input`<sup>Optional</sup> <a name="end_min_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.endMinInput"></a>

```python
end_min_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `start_day_input`<sup>Optional</sup> <a name="start_day_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.startDayInput"></a>

```python
start_day_input: str
```

- *Type:* str

---

##### `start_hour_input`<sup>Optional</sup> <a name="start_hour_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.startHourInput"></a>

```python
start_hour_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `start_min_input`<sup>Optional</sup> <a name="start_min_input" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.startMinInput"></a>

```python
start_min_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `end_day`<sup>Required</sup> <a name="end_day" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.endDay"></a>

```python
end_day: str
```

- *Type:* str

---

##### `end_hour`<sup>Required</sup> <a name="end_hour" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.endHour"></a>

```python
end_hour: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `end_min`<sup>Required</sup> <a name="end_min" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.endMin"></a>

```python
end_min: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `start_day`<sup>Required</sup> <a name="start_day" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.startDay"></a>

```python
start_day: str
```

- *Type:* str

---

##### `start_hour`<sup>Required</sup> <a name="start_hour" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.startHour"></a>

```python
start_hour: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `start_min`<sup>Required</sup> <a name="start_min" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.startMin"></a>

```python
start_min: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, AlertPolicyTimeRestrictionRestrictions]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions">AlertPolicyTimeRestrictionRestrictions</a>]

---



