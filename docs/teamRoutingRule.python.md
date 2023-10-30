# `opsgenie_team_routing_rule`

Refer to the Terraform Registory for docs: [`opsgenie_team_routing_rule`](https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule).

# `teamRoutingRule` Submodule <a name="`teamRoutingRule` Submodule" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### TeamRoutingRule <a name="TeamRoutingRule" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule"></a>

Represents a {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule opsgenie_team_routing_rule}.

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import team_routing_rule

teamRoutingRule.TeamRoutingRule(
  scope: Construct,
  id: str,
  connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection] = None,
  count: typing.Union[typing.Union[int, float], TerraformCount] = None,
  depends_on: typing.List[ITerraformDependable] = None,
  for_each: ITerraformIterator = None,
  lifecycle: TerraformResourceLifecycle = None,
  provider: TerraformProvider = None,
  provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]] = None,
  notify: typing.Union[IResolvable, typing.List[TeamRoutingRuleNotify]],
  team_id: str,
  criteria: typing.Union[IResolvable, typing.List[TeamRoutingRuleCriteria]] = None,
  id: str = None,
  is_default: typing.Union[bool, IResolvable] = None,
  name: str = None,
  order: typing.Union[int, float] = None,
  time_restriction: typing.Union[IResolvable, typing.List[TeamRoutingRuleTimeRestriction]] = None,
  timezone: str = None
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.id">id</a></code> | <code>str</code> | The scoped construct ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.connection">connection</a></code> | <code>typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.dependsOn">depends_on</a></code> | <code>typing.List[cdktf.ITerraformDependable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.provisioners">provisioners</a></code> | <code>typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.notify">notify</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify">TeamRoutingRuleNotify</a>]]</code> | notify block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.teamId">team_id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#team_id TeamRoutingRule#team_id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.criteria">criteria</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria">TeamRoutingRuleCriteria</a>]]</code> | criteria block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.id">id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#id TeamRoutingRule#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.isDefault">is_default</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#is_default TeamRoutingRule#is_default}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.name">name</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#name TeamRoutingRule#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.order">order</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#order TeamRoutingRule#order}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.timeRestriction">time_restriction</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction">TeamRoutingRuleTimeRestriction</a>]]</code> | time_restriction block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.timezone">timezone</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#timezone TeamRoutingRule#timezone}. |

---

##### `scope`<sup>Required</sup> <a name="scope" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.id"></a>

- *Type:* str

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.connection"></a>

- *Type:* typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.count"></a>

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.dependsOn"></a>

- *Type:* typing.List[cdktf.ITerraformDependable]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.forEach"></a>

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.lifecycle"></a>

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.provider"></a>

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.provisioners"></a>

- *Type:* typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]

---

##### `notify`<sup>Required</sup> <a name="notify" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.notify"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify">TeamRoutingRuleNotify</a>]]

notify block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#notify TeamRoutingRule#notify}

---

##### `team_id`<sup>Required</sup> <a name="team_id" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.teamId"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#team_id TeamRoutingRule#team_id}.

---

##### `criteria`<sup>Optional</sup> <a name="criteria" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.criteria"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria">TeamRoutingRuleCriteria</a>]]

criteria block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#criteria TeamRoutingRule#criteria}

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.id"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#id TeamRoutingRule#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `is_default`<sup>Optional</sup> <a name="is_default" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.isDefault"></a>

- *Type:* typing.Union[bool, cdktf.IResolvable]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#is_default TeamRoutingRule#is_default}.

---

##### `name`<sup>Optional</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.name"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#name TeamRoutingRule#name}.

---

##### `order`<sup>Optional</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.order"></a>

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#order TeamRoutingRule#order}.

---

##### `time_restriction`<sup>Optional</sup> <a name="time_restriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.timeRestriction"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction">TeamRoutingRuleTimeRestriction</a>]]

time_restriction block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#time_restriction TeamRoutingRule#time_restriction}

---

##### `timezone`<sup>Optional</sup> <a name="timezone" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.timezone"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#timezone TeamRoutingRule#timezone}.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.toString">to_string</a></code> | Returns a string representation of this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.addOverride">add_override</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.overrideLogicalId">override_logical_id</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetOverrideLogicalId">reset_override_logical_id</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.toMetadata">to_metadata</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.toTerraform">to_terraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putCriteria">put_criteria</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putNotify">put_notify</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putTimeRestriction">put_time_restriction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetCriteria">reset_criteria</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetId">reset_id</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetIsDefault">reset_is_default</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetName">reset_name</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetOrder">reset_order</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetTimeRestriction">reset_time_restriction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetTimezone">reset_timezone</a></code> | *No description.* |

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.toString"></a>

```python
def to_string() -> str
```

Returns a string representation of this construct.

##### `add_override` <a name="add_override" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.addOverride"></a>

```python
def add_override(
  path: str,
  value: typing.Any
) -> None
```

###### `path`<sup>Required</sup> <a name="path" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.addOverride.parameter.path"></a>

- *Type:* str

---

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.addOverride.parameter.value"></a>

- *Type:* typing.Any

---

##### `override_logical_id` <a name="override_logical_id" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.overrideLogicalId"></a>

```python
def override_logical_id(
  new_logical_id: str
) -> None
```

Overrides the auto-generated logical ID with a specific ID.

###### `new_logical_id`<sup>Required</sup> <a name="new_logical_id" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* str

The new logical ID to use for this stack element.

---

##### `reset_override_logical_id` <a name="reset_override_logical_id" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetOverrideLogicalId"></a>

```python
def reset_override_logical_id() -> None
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `to_metadata` <a name="to_metadata" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.toMetadata"></a>

```python
def to_metadata() -> typing.Any
```

##### `to_terraform` <a name="to_terraform" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.toTerraform"></a>

```python
def to_terraform() -> typing.Any
```

Adds this resource to the terraform JSON output.

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `put_criteria` <a name="put_criteria" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putCriteria"></a>

```python
def put_criteria(
  value: typing.Union[IResolvable, typing.List[TeamRoutingRuleCriteria]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putCriteria.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria">TeamRoutingRuleCriteria</a>]]

---

##### `put_notify` <a name="put_notify" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putNotify"></a>

```python
def put_notify(
  value: typing.Union[IResolvable, typing.List[TeamRoutingRuleNotify]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putNotify.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify">TeamRoutingRuleNotify</a>]]

---

##### `put_time_restriction` <a name="put_time_restriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putTimeRestriction"></a>

```python
def put_time_restriction(
  value: typing.Union[IResolvable, typing.List[TeamRoutingRuleTimeRestriction]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putTimeRestriction.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction">TeamRoutingRuleTimeRestriction</a>]]

---

##### `reset_criteria` <a name="reset_criteria" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetCriteria"></a>

```python
def reset_criteria() -> None
```

##### `reset_id` <a name="reset_id" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetId"></a>

```python
def reset_id() -> None
```

##### `reset_is_default` <a name="reset_is_default" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetIsDefault"></a>

```python
def reset_is_default() -> None
```

##### `reset_name` <a name="reset_name" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetName"></a>

```python
def reset_name() -> None
```

##### `reset_order` <a name="reset_order" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetOrder"></a>

```python
def reset_order() -> None
```

##### `reset_time_restriction` <a name="reset_time_restriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetTimeRestriction"></a>

```python
def reset_time_restriction() -> None
```

##### `reset_timezone` <a name="reset_timezone" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetTimezone"></a>

```python
def reset_timezone() -> None
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isConstruct">is_construct</a></code> | Checks if `x` is a construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isTerraformElement">is_terraform_element</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isTerraformResource">is_terraform_resource</a></code> | *No description.* |

---

##### `is_construct` <a name="is_construct" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isConstruct"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import team_routing_rule

teamRoutingRule.TeamRoutingRule.is_construct(
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

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isConstruct.parameter.x"></a>

- *Type:* typing.Any

Any object.

---

##### `is_terraform_element` <a name="is_terraform_element" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isTerraformElement"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import team_routing_rule

teamRoutingRule.TeamRoutingRule.is_terraform_element(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isTerraformElement.parameter.x"></a>

- *Type:* typing.Any

---

##### `is_terraform_resource` <a name="is_terraform_resource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isTerraformResource"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import team_routing_rule

teamRoutingRule.TeamRoutingRule.is_terraform_resource(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isTerraformResource.parameter.x"></a>

- *Type:* typing.Any

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.node">node</a></code> | <code>constructs.Node</code> | The tree node. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.cdktfStack">cdktf_stack</a></code> | <code>cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.friendlyUniqueId">friendly_unique_id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.terraformMetaArguments">terraform_meta_arguments</a></code> | <code>typing.Mapping[typing.Any]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.terraformResourceType">terraform_resource_type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.terraformGeneratorMetadata">terraform_generator_metadata</a></code> | <code>cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.connection">connection</a></code> | <code>typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.dependsOn">depends_on</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.provisioners">provisioners</a></code> | <code>typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.criteria">criteria</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList">TeamRoutingRuleCriteriaList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.notify">notify</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList">TeamRoutingRuleNotifyList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timeRestriction">time_restriction</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList">TeamRoutingRuleTimeRestrictionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.criteriaInput">criteria_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria">TeamRoutingRuleCriteria</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.idInput">id_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.isDefaultInput">is_default_input</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.nameInput">name_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.notifyInput">notify_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify">TeamRoutingRuleNotify</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.orderInput">order_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.teamIdInput">team_id_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timeRestrictionInput">time_restriction_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction">TeamRoutingRuleTimeRestriction</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timezoneInput">timezone_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.id">id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.isDefault">is_default</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.name">name</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.order">order</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.teamId">team_id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timezone">timezone</a></code> | <code>str</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.node"></a>

```python
node: Node
```

- *Type:* constructs.Node

The tree node.

---

##### `cdktf_stack`<sup>Required</sup> <a name="cdktf_stack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.cdktfStack"></a>

```python
cdktf_stack: TerraformStack
```

- *Type:* cdktf.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `friendly_unique_id`<sup>Required</sup> <a name="friendly_unique_id" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.friendlyUniqueId"></a>

```python
friendly_unique_id: str
```

- *Type:* str

---

##### `terraform_meta_arguments`<sup>Required</sup> <a name="terraform_meta_arguments" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.terraformMetaArguments"></a>

```python
terraform_meta_arguments: typing.Mapping[typing.Any]
```

- *Type:* typing.Mapping[typing.Any]

---

##### `terraform_resource_type`<sup>Required</sup> <a name="terraform_resource_type" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.terraformResourceType"></a>

```python
terraform_resource_type: str
```

- *Type:* str

---

##### `terraform_generator_metadata`<sup>Optional</sup> <a name="terraform_generator_metadata" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.terraformGeneratorMetadata"></a>

```python
terraform_generator_metadata: TerraformProviderGeneratorMetadata
```

- *Type:* cdktf.TerraformProviderGeneratorMetadata

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.connection"></a>

```python
connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection]
```

- *Type:* typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.count"></a>

```python
count: typing.Union[typing.Union[int, float], TerraformCount]
```

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.dependsOn"></a>

```python
depends_on: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.forEach"></a>

```python
for_each: ITerraformIterator
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.lifecycle"></a>

```python
lifecycle: TerraformResourceLifecycle
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.provider"></a>

```python
provider: TerraformProvider
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.provisioners"></a>

```python
provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]]
```

- *Type:* typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]

---

##### `criteria`<sup>Required</sup> <a name="criteria" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.criteria"></a>

```python
criteria: TeamRoutingRuleCriteriaList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList">TeamRoutingRuleCriteriaList</a>

---

##### `notify`<sup>Required</sup> <a name="notify" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.notify"></a>

```python
notify: TeamRoutingRuleNotifyList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList">TeamRoutingRuleNotifyList</a>

---

##### `time_restriction`<sup>Required</sup> <a name="time_restriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timeRestriction"></a>

```python
time_restriction: TeamRoutingRuleTimeRestrictionList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList">TeamRoutingRuleTimeRestrictionList</a>

---

##### `criteria_input`<sup>Optional</sup> <a name="criteria_input" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.criteriaInput"></a>

```python
criteria_input: typing.Union[IResolvable, typing.List[TeamRoutingRuleCriteria]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria">TeamRoutingRuleCriteria</a>]]

---

##### `id_input`<sup>Optional</sup> <a name="id_input" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.idInput"></a>

```python
id_input: str
```

- *Type:* str

---

##### `is_default_input`<sup>Optional</sup> <a name="is_default_input" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.isDefaultInput"></a>

```python
is_default_input: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `name_input`<sup>Optional</sup> <a name="name_input" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.nameInput"></a>

```python
name_input: str
```

- *Type:* str

---

##### `notify_input`<sup>Optional</sup> <a name="notify_input" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.notifyInput"></a>

```python
notify_input: typing.Union[IResolvable, typing.List[TeamRoutingRuleNotify]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify">TeamRoutingRuleNotify</a>]]

---

##### `order_input`<sup>Optional</sup> <a name="order_input" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.orderInput"></a>

```python
order_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `team_id_input`<sup>Optional</sup> <a name="team_id_input" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.teamIdInput"></a>

```python
team_id_input: str
```

- *Type:* str

---

##### `time_restriction_input`<sup>Optional</sup> <a name="time_restriction_input" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timeRestrictionInput"></a>

```python
time_restriction_input: typing.Union[IResolvable, typing.List[TeamRoutingRuleTimeRestriction]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction">TeamRoutingRuleTimeRestriction</a>]]

---

##### `timezone_input`<sup>Optional</sup> <a name="timezone_input" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timezoneInput"></a>

```python
timezone_input: str
```

- *Type:* str

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.id"></a>

```python
id: str
```

- *Type:* str

---

##### `is_default`<sup>Required</sup> <a name="is_default" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.isDefault"></a>

```python
is_default: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.name"></a>

```python
name: str
```

- *Type:* str

---

##### `order`<sup>Required</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.order"></a>

```python
order: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `team_id`<sup>Required</sup> <a name="team_id" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.teamId"></a>

```python
team_id: str
```

- *Type:* str

---

##### `timezone`<sup>Required</sup> <a name="timezone" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timezone"></a>

```python
timezone: str
```

- *Type:* str

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.tfResourceType">tfResourceType</a></code> | <code>str</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.tfResourceType"></a>

```python
tfResourceType: str
```

- *Type:* str

---

## Structs <a name="Structs" id="Structs"></a>

### TeamRoutingRuleConfig <a name="TeamRoutingRuleConfig" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import team_routing_rule

teamRoutingRule.TeamRoutingRuleConfig(
  connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection] = None,
  count: typing.Union[typing.Union[int, float], TerraformCount] = None,
  depends_on: typing.List[ITerraformDependable] = None,
  for_each: ITerraformIterator = None,
  lifecycle: TerraformResourceLifecycle = None,
  provider: TerraformProvider = None,
  provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]] = None,
  notify: typing.Union[IResolvable, typing.List[TeamRoutingRuleNotify]],
  team_id: str,
  criteria: typing.Union[IResolvable, typing.List[TeamRoutingRuleCriteria]] = None,
  id: str = None,
  is_default: typing.Union[bool, IResolvable] = None,
  name: str = None,
  order: typing.Union[int, float] = None,
  time_restriction: typing.Union[IResolvable, typing.List[TeamRoutingRuleTimeRestriction]] = None,
  timezone: str = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.connection">connection</a></code> | <code>typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.dependsOn">depends_on</a></code> | <code>typing.List[cdktf.ITerraformDependable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.provisioners">provisioners</a></code> | <code>typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.notify">notify</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify">TeamRoutingRuleNotify</a>]]</code> | notify block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.teamId">team_id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#team_id TeamRoutingRule#team_id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.criteria">criteria</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria">TeamRoutingRuleCriteria</a>]]</code> | criteria block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.id">id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#id TeamRoutingRule#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.isDefault">is_default</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#is_default TeamRoutingRule#is_default}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.name">name</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#name TeamRoutingRule#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.order">order</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#order TeamRoutingRule#order}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.timeRestriction">time_restriction</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction">TeamRoutingRuleTimeRestriction</a>]]</code> | time_restriction block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.timezone">timezone</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#timezone TeamRoutingRule#timezone}. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.connection"></a>

```python
connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection]
```

- *Type:* typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.count"></a>

```python
count: typing.Union[typing.Union[int, float], TerraformCount]
```

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.dependsOn"></a>

```python
depends_on: typing.List[ITerraformDependable]
```

- *Type:* typing.List[cdktf.ITerraformDependable]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.forEach"></a>

```python
for_each: ITerraformIterator
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.lifecycle"></a>

```python
lifecycle: TerraformResourceLifecycle
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.provider"></a>

```python
provider: TerraformProvider
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.provisioners"></a>

```python
provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]]
```

- *Type:* typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]

---

##### `notify`<sup>Required</sup> <a name="notify" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.notify"></a>

```python
notify: typing.Union[IResolvable, typing.List[TeamRoutingRuleNotify]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify">TeamRoutingRuleNotify</a>]]

notify block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#notify TeamRoutingRule#notify}

---

##### `team_id`<sup>Required</sup> <a name="team_id" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.teamId"></a>

```python
team_id: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#team_id TeamRoutingRule#team_id}.

---

##### `criteria`<sup>Optional</sup> <a name="criteria" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.criteria"></a>

```python
criteria: typing.Union[IResolvable, typing.List[TeamRoutingRuleCriteria]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria">TeamRoutingRuleCriteria</a>]]

criteria block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#criteria TeamRoutingRule#criteria}

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.id"></a>

```python
id: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#id TeamRoutingRule#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `is_default`<sup>Optional</sup> <a name="is_default" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.isDefault"></a>

```python
is_default: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#is_default TeamRoutingRule#is_default}.

---

##### `name`<sup>Optional</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.name"></a>

```python
name: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#name TeamRoutingRule#name}.

---

##### `order`<sup>Optional</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.order"></a>

```python
order: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#order TeamRoutingRule#order}.

---

##### `time_restriction`<sup>Optional</sup> <a name="time_restriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.timeRestriction"></a>

```python
time_restriction: typing.Union[IResolvable, typing.List[TeamRoutingRuleTimeRestriction]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction">TeamRoutingRuleTimeRestriction</a>]]

time_restriction block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#time_restriction TeamRoutingRule#time_restriction}

---

##### `timezone`<sup>Optional</sup> <a name="timezone" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.timezone"></a>

```python
timezone: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#timezone TeamRoutingRule#timezone}.

---

### TeamRoutingRuleCriteria <a name="TeamRoutingRuleCriteria" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import team_routing_rule

teamRoutingRule.TeamRoutingRuleCriteria(
  type: str,
  conditions: typing.Union[IResolvable, typing.List[TeamRoutingRuleCriteriaConditions]] = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria.property.type">type</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#type TeamRoutingRule#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria.property.conditions">conditions</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions">TeamRoutingRuleCriteriaConditions</a>]]</code> | conditions block. |

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria.property.type"></a>

```python
type: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#type TeamRoutingRule#type}.

---

##### `conditions`<sup>Optional</sup> <a name="conditions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria.property.conditions"></a>

```python
conditions: typing.Union[IResolvable, typing.List[TeamRoutingRuleCriteriaConditions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions">TeamRoutingRuleCriteriaConditions</a>]]

conditions block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#conditions TeamRoutingRule#conditions}

---

### TeamRoutingRuleCriteriaConditions <a name="TeamRoutingRuleCriteriaConditions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import team_routing_rule

teamRoutingRule.TeamRoutingRuleCriteriaConditions(
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
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.field">field</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#field TeamRoutingRule#field}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.operation">operation</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#operation TeamRoutingRule#operation}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.expectedValue">expected_value</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#expected_value TeamRoutingRule#expected_value}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.key">key</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#key TeamRoutingRule#key}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.not">not</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#not TeamRoutingRule#not}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.order">order</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#order TeamRoutingRule#order}. |

---

##### `field`<sup>Required</sup> <a name="field" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.field"></a>

```python
field: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#field TeamRoutingRule#field}.

---

##### `operation`<sup>Required</sup> <a name="operation" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.operation"></a>

```python
operation: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#operation TeamRoutingRule#operation}.

---

##### `expected_value`<sup>Optional</sup> <a name="expected_value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.expectedValue"></a>

```python
expected_value: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#expected_value TeamRoutingRule#expected_value}.

---

##### `key`<sup>Optional</sup> <a name="key" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.key"></a>

```python
key: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#key TeamRoutingRule#key}.

---

##### `not`<sup>Optional</sup> <a name="not" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.not"></a>

```python
not: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#not TeamRoutingRule#not}.

---

##### `order`<sup>Optional</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.order"></a>

```python
order: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#order TeamRoutingRule#order}.

---

### TeamRoutingRuleNotify <a name="TeamRoutingRuleNotify" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import team_routing_rule

teamRoutingRule.TeamRoutingRuleNotify(
  type: str,
  id: str = None,
  name: str = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify.property.type">type</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#type TeamRoutingRule#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify.property.id">id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#id TeamRoutingRule#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify.property.name">name</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#name TeamRoutingRule#name}. |

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify.property.type"></a>

```python
type: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#type TeamRoutingRule#type}.

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify.property.id"></a>

```python
id: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#id TeamRoutingRule#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `name`<sup>Optional</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify.property.name"></a>

```python
name: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#name TeamRoutingRule#name}.

---

### TeamRoutingRuleTimeRestriction <a name="TeamRoutingRuleTimeRestriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import team_routing_rule

teamRoutingRule.TeamRoutingRuleTimeRestriction(
  type: str,
  restriction: typing.Union[IResolvable, typing.List[TeamRoutingRuleTimeRestrictionRestriction]] = None,
  restrictions: typing.Union[IResolvable, typing.List[TeamRoutingRuleTimeRestrictionRestrictions]] = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction.property.type">type</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#type TeamRoutingRule#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction.property.restriction">restriction</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction">TeamRoutingRuleTimeRestrictionRestriction</a>]]</code> | restriction block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction.property.restrictions">restrictions</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions">TeamRoutingRuleTimeRestrictionRestrictions</a>]]</code> | restrictions block. |

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction.property.type"></a>

```python
type: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#type TeamRoutingRule#type}.

---

##### `restriction`<sup>Optional</sup> <a name="restriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction.property.restriction"></a>

```python
restriction: typing.Union[IResolvable, typing.List[TeamRoutingRuleTimeRestrictionRestriction]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction">TeamRoutingRuleTimeRestrictionRestriction</a>]]

restriction block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#restriction TeamRoutingRule#restriction}

---

##### `restrictions`<sup>Optional</sup> <a name="restrictions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction.property.restrictions"></a>

```python
restrictions: typing.Union[IResolvable, typing.List[TeamRoutingRuleTimeRestrictionRestrictions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions">TeamRoutingRuleTimeRestrictionRestrictions</a>]]

restrictions block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#restrictions TeamRoutingRule#restrictions}

---

### TeamRoutingRuleTimeRestrictionRestriction <a name="TeamRoutingRuleTimeRestrictionRestriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import team_routing_rule

teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction(
  end_hour: typing.Union[int, float],
  end_min: typing.Union[int, float],
  start_hour: typing.Union[int, float],
  start_min: typing.Union[int, float]
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.endHour">end_hour</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_hour TeamRoutingRule#end_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.endMin">end_min</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_min TeamRoutingRule#end_min}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.startHour">start_hour</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_hour TeamRoutingRule#start_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.startMin">start_min</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_min TeamRoutingRule#start_min}. |

---

##### `end_hour`<sup>Required</sup> <a name="end_hour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.endHour"></a>

```python
end_hour: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_hour TeamRoutingRule#end_hour}.

---

##### `end_min`<sup>Required</sup> <a name="end_min" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.endMin"></a>

```python
end_min: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_min TeamRoutingRule#end_min}.

---

##### `start_hour`<sup>Required</sup> <a name="start_hour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.startHour"></a>

```python
start_hour: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_hour TeamRoutingRule#start_hour}.

---

##### `start_min`<sup>Required</sup> <a name="start_min" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.startMin"></a>

```python
start_min: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_min TeamRoutingRule#start_min}.

---

### TeamRoutingRuleTimeRestrictionRestrictions <a name="TeamRoutingRuleTimeRestrictionRestrictions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import team_routing_rule

teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions(
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
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.endDay">end_day</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_day TeamRoutingRule#end_day}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.endHour">end_hour</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_hour TeamRoutingRule#end_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.endMin">end_min</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_min TeamRoutingRule#end_min}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.startDay">start_day</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_day TeamRoutingRule#start_day}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.startHour">start_hour</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_hour TeamRoutingRule#start_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.startMin">start_min</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_min TeamRoutingRule#start_min}. |

---

##### `end_day`<sup>Required</sup> <a name="end_day" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.endDay"></a>

```python
end_day: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_day TeamRoutingRule#end_day}.

---

##### `end_hour`<sup>Required</sup> <a name="end_hour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.endHour"></a>

```python
end_hour: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_hour TeamRoutingRule#end_hour}.

---

##### `end_min`<sup>Required</sup> <a name="end_min" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.endMin"></a>

```python
end_min: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_min TeamRoutingRule#end_min}.

---

##### `start_day`<sup>Required</sup> <a name="start_day" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.startDay"></a>

```python
start_day: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_day TeamRoutingRule#start_day}.

---

##### `start_hour`<sup>Required</sup> <a name="start_hour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.startHour"></a>

```python
start_hour: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_hour TeamRoutingRule#start_hour}.

---

##### `start_min`<sup>Required</sup> <a name="start_min" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.startMin"></a>

```python
start_min: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_min TeamRoutingRule#start_min}.

---

## Classes <a name="Classes" id="Classes"></a>

### TeamRoutingRuleCriteriaConditionsList <a name="TeamRoutingRuleCriteriaConditionsList" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import team_routing_rule

teamRoutingRule.TeamRoutingRuleCriteriaConditionsList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> TeamRoutingRuleCriteriaConditionsOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions">TeamRoutingRuleCriteriaConditions</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[TeamRoutingRuleCriteriaConditions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions">TeamRoutingRuleCriteriaConditions</a>]]

---


### TeamRoutingRuleCriteriaConditionsOutputReference <a name="TeamRoutingRuleCriteriaConditionsOutputReference" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import team_routing_rule

teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resetExpectedValue">reset_expected_value</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resetKey">reset_key</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resetNot">reset_not</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resetOrder">reset_order</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `reset_expected_value` <a name="reset_expected_value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resetExpectedValue"></a>

```python
def reset_expected_value() -> None
```

##### `reset_key` <a name="reset_key" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resetKey"></a>

```python
def reset_key() -> None
```

##### `reset_not` <a name="reset_not" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resetNot"></a>

```python
def reset_not() -> None
```

##### `reset_order` <a name="reset_order" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resetOrder"></a>

```python
def reset_order() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.expectedValueInput">expected_value_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.fieldInput">field_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.keyInput">key_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.notInput">not_input</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.operationInput">operation_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.orderInput">order_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.expectedValue">expected_value</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.field">field</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.key">key</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.not">not</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.operation">operation</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.order">order</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions">TeamRoutingRuleCriteriaConditions</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `expected_value_input`<sup>Optional</sup> <a name="expected_value_input" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.expectedValueInput"></a>

```python
expected_value_input: str
```

- *Type:* str

---

##### `field_input`<sup>Optional</sup> <a name="field_input" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.fieldInput"></a>

```python
field_input: str
```

- *Type:* str

---

##### `key_input`<sup>Optional</sup> <a name="key_input" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.keyInput"></a>

```python
key_input: str
```

- *Type:* str

---

##### `not_input`<sup>Optional</sup> <a name="not_input" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.notInput"></a>

```python
not_input: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `operation_input`<sup>Optional</sup> <a name="operation_input" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.operationInput"></a>

```python
operation_input: str
```

- *Type:* str

---

##### `order_input`<sup>Optional</sup> <a name="order_input" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.orderInput"></a>

```python
order_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `expected_value`<sup>Required</sup> <a name="expected_value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.expectedValue"></a>

```python
expected_value: str
```

- *Type:* str

---

##### `field`<sup>Required</sup> <a name="field" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.field"></a>

```python
field: str
```

- *Type:* str

---

##### `key`<sup>Required</sup> <a name="key" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.key"></a>

```python
key: str
```

- *Type:* str

---

##### `not`<sup>Required</sup> <a name="not" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.not"></a>

```python
not: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `operation`<sup>Required</sup> <a name="operation" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.operation"></a>

```python
operation: str
```

- *Type:* str

---

##### `order`<sup>Required</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.order"></a>

```python
order: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, TeamRoutingRuleCriteriaConditions]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions">TeamRoutingRuleCriteriaConditions</a>]

---


### TeamRoutingRuleCriteriaList <a name="TeamRoutingRuleCriteriaList" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import team_routing_rule

teamRoutingRule.TeamRoutingRuleCriteriaList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> TeamRoutingRuleCriteriaOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria">TeamRoutingRuleCriteria</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[TeamRoutingRuleCriteria]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria">TeamRoutingRuleCriteria</a>]]

---


### TeamRoutingRuleCriteriaOutputReference <a name="TeamRoutingRuleCriteriaOutputReference" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import team_routing_rule

teamRoutingRule.TeamRoutingRuleCriteriaOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.putConditions">put_conditions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.resetConditions">reset_conditions</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `put_conditions` <a name="put_conditions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.putConditions"></a>

```python
def put_conditions(
  value: typing.Union[IResolvable, typing.List[TeamRoutingRuleCriteriaConditions]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.putConditions.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions">TeamRoutingRuleCriteriaConditions</a>]]

---

##### `reset_conditions` <a name="reset_conditions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.resetConditions"></a>

```python
def reset_conditions() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.conditions">conditions</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList">TeamRoutingRuleCriteriaConditionsList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.conditionsInput">conditions_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions">TeamRoutingRuleCriteriaConditions</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.typeInput">type_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.type">type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria">TeamRoutingRuleCriteria</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `conditions`<sup>Required</sup> <a name="conditions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.conditions"></a>

```python
conditions: TeamRoutingRuleCriteriaConditionsList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList">TeamRoutingRuleCriteriaConditionsList</a>

---

##### `conditions_input`<sup>Optional</sup> <a name="conditions_input" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.conditionsInput"></a>

```python
conditions_input: typing.Union[IResolvable, typing.List[TeamRoutingRuleCriteriaConditions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions">TeamRoutingRuleCriteriaConditions</a>]]

---

##### `type_input`<sup>Optional</sup> <a name="type_input" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.typeInput"></a>

```python
type_input: str
```

- *Type:* str

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.type"></a>

```python
type: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, TeamRoutingRuleCriteria]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria">TeamRoutingRuleCriteria</a>]

---


### TeamRoutingRuleNotifyList <a name="TeamRoutingRuleNotifyList" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import team_routing_rule

teamRoutingRule.TeamRoutingRuleNotifyList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> TeamRoutingRuleNotifyOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify">TeamRoutingRuleNotify</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[TeamRoutingRuleNotify]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify">TeamRoutingRuleNotify</a>]]

---


### TeamRoutingRuleNotifyOutputReference <a name="TeamRoutingRuleNotifyOutputReference" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import team_routing_rule

teamRoutingRule.TeamRoutingRuleNotifyOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.resetId">reset_id</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.resetName">reset_name</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `reset_id` <a name="reset_id" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.resetId"></a>

```python
def reset_id() -> None
```

##### `reset_name` <a name="reset_name" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.resetName"></a>

```python
def reset_name() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.idInput">id_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.nameInput">name_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.typeInput">type_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.id">id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.name">name</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.type">type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify">TeamRoutingRuleNotify</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `id_input`<sup>Optional</sup> <a name="id_input" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.idInput"></a>

```python
id_input: str
```

- *Type:* str

---

##### `name_input`<sup>Optional</sup> <a name="name_input" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.nameInput"></a>

```python
name_input: str
```

- *Type:* str

---

##### `type_input`<sup>Optional</sup> <a name="type_input" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.typeInput"></a>

```python
type_input: str
```

- *Type:* str

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.id"></a>

```python
id: str
```

- *Type:* str

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.name"></a>

```python
name: str
```

- *Type:* str

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.type"></a>

```python
type: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, TeamRoutingRuleNotify]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify">TeamRoutingRuleNotify</a>]

---


### TeamRoutingRuleTimeRestrictionList <a name="TeamRoutingRuleTimeRestrictionList" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import team_routing_rule

teamRoutingRule.TeamRoutingRuleTimeRestrictionList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> TeamRoutingRuleTimeRestrictionOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction">TeamRoutingRuleTimeRestriction</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[TeamRoutingRuleTimeRestriction]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction">TeamRoutingRuleTimeRestriction</a>]]

---


### TeamRoutingRuleTimeRestrictionOutputReference <a name="TeamRoutingRuleTimeRestrictionOutputReference" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import team_routing_rule

teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.putRestriction">put_restriction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.putRestrictions">put_restrictions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.resetRestriction">reset_restriction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.resetRestrictions">reset_restrictions</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `put_restriction` <a name="put_restriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.putRestriction"></a>

```python
def put_restriction(
  value: typing.Union[IResolvable, typing.List[TeamRoutingRuleTimeRestrictionRestriction]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.putRestriction.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction">TeamRoutingRuleTimeRestrictionRestriction</a>]]

---

##### `put_restrictions` <a name="put_restrictions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.putRestrictions"></a>

```python
def put_restrictions(
  value: typing.Union[IResolvable, typing.List[TeamRoutingRuleTimeRestrictionRestrictions]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.putRestrictions.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions">TeamRoutingRuleTimeRestrictionRestrictions</a>]]

---

##### `reset_restriction` <a name="reset_restriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.resetRestriction"></a>

```python
def reset_restriction() -> None
```

##### `reset_restrictions` <a name="reset_restrictions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.resetRestrictions"></a>

```python
def reset_restrictions() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restriction">restriction</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList">TeamRoutingRuleTimeRestrictionRestrictionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restrictions">restrictions</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList">TeamRoutingRuleTimeRestrictionRestrictionsList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restrictionInput">restriction_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction">TeamRoutingRuleTimeRestrictionRestriction</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restrictionsInput">restrictions_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions">TeamRoutingRuleTimeRestrictionRestrictions</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.typeInput">type_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.type">type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction">TeamRoutingRuleTimeRestriction</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `restriction`<sup>Required</sup> <a name="restriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restriction"></a>

```python
restriction: TeamRoutingRuleTimeRestrictionRestrictionList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList">TeamRoutingRuleTimeRestrictionRestrictionList</a>

---

##### `restrictions`<sup>Required</sup> <a name="restrictions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restrictions"></a>

```python
restrictions: TeamRoutingRuleTimeRestrictionRestrictionsList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList">TeamRoutingRuleTimeRestrictionRestrictionsList</a>

---

##### `restriction_input`<sup>Optional</sup> <a name="restriction_input" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restrictionInput"></a>

```python
restriction_input: typing.Union[IResolvable, typing.List[TeamRoutingRuleTimeRestrictionRestriction]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction">TeamRoutingRuleTimeRestrictionRestriction</a>]]

---

##### `restrictions_input`<sup>Optional</sup> <a name="restrictions_input" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restrictionsInput"></a>

```python
restrictions_input: typing.Union[IResolvable, typing.List[TeamRoutingRuleTimeRestrictionRestrictions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions">TeamRoutingRuleTimeRestrictionRestrictions</a>]]

---

##### `type_input`<sup>Optional</sup> <a name="type_input" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.typeInput"></a>

```python
type_input: str
```

- *Type:* str

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.type"></a>

```python
type: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, TeamRoutingRuleTimeRestriction]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction">TeamRoutingRuleTimeRestriction</a>]

---


### TeamRoutingRuleTimeRestrictionRestrictionList <a name="TeamRoutingRuleTimeRestrictionRestrictionList" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import team_routing_rule

teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> TeamRoutingRuleTimeRestrictionRestrictionOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction">TeamRoutingRuleTimeRestrictionRestriction</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[TeamRoutingRuleTimeRestrictionRestriction]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction">TeamRoutingRuleTimeRestrictionRestriction</a>]]

---


### TeamRoutingRuleTimeRestrictionRestrictionOutputReference <a name="TeamRoutingRuleTimeRestrictionRestrictionOutputReference" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import team_routing_rule

teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endHourInput">end_hour_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endMinInput">end_min_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startHourInput">start_hour_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startMinInput">start_min_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endHour">end_hour</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endMin">end_min</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startHour">start_hour</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startMin">start_min</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction">TeamRoutingRuleTimeRestrictionRestriction</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `end_hour_input`<sup>Optional</sup> <a name="end_hour_input" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endHourInput"></a>

```python
end_hour_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `end_min_input`<sup>Optional</sup> <a name="end_min_input" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endMinInput"></a>

```python
end_min_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `start_hour_input`<sup>Optional</sup> <a name="start_hour_input" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startHourInput"></a>

```python
start_hour_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `start_min_input`<sup>Optional</sup> <a name="start_min_input" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startMinInput"></a>

```python
start_min_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `end_hour`<sup>Required</sup> <a name="end_hour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endHour"></a>

```python
end_hour: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `end_min`<sup>Required</sup> <a name="end_min" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endMin"></a>

```python
end_min: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `start_hour`<sup>Required</sup> <a name="start_hour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startHour"></a>

```python
start_hour: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `start_min`<sup>Required</sup> <a name="start_min" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startMin"></a>

```python
start_min: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, TeamRoutingRuleTimeRestrictionRestriction]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction">TeamRoutingRuleTimeRestrictionRestriction</a>]

---


### TeamRoutingRuleTimeRestrictionRestrictionsList <a name="TeamRoutingRuleTimeRestrictionRestrictionsList" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import team_routing_rule

teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> TeamRoutingRuleTimeRestrictionRestrictionsOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions">TeamRoutingRuleTimeRestrictionRestrictions</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[TeamRoutingRuleTimeRestrictionRestrictions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions">TeamRoutingRuleTimeRestrictionRestrictions</a>]]

---


### TeamRoutingRuleTimeRestrictionRestrictionsOutputReference <a name="TeamRoutingRuleTimeRestrictionRestrictionsOutputReference" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import team_routing_rule

teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endDayInput">end_day_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endHourInput">end_hour_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endMinInput">end_min_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startDayInput">start_day_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startHourInput">start_hour_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startMinInput">start_min_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endDay">end_day</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endHour">end_hour</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endMin">end_min</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startDay">start_day</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startHour">start_hour</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startMin">start_min</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions">TeamRoutingRuleTimeRestrictionRestrictions</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `end_day_input`<sup>Optional</sup> <a name="end_day_input" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endDayInput"></a>

```python
end_day_input: str
```

- *Type:* str

---

##### `end_hour_input`<sup>Optional</sup> <a name="end_hour_input" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endHourInput"></a>

```python
end_hour_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `end_min_input`<sup>Optional</sup> <a name="end_min_input" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endMinInput"></a>

```python
end_min_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `start_day_input`<sup>Optional</sup> <a name="start_day_input" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startDayInput"></a>

```python
start_day_input: str
```

- *Type:* str

---

##### `start_hour_input`<sup>Optional</sup> <a name="start_hour_input" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startHourInput"></a>

```python
start_hour_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `start_min_input`<sup>Optional</sup> <a name="start_min_input" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startMinInput"></a>

```python
start_min_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `end_day`<sup>Required</sup> <a name="end_day" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endDay"></a>

```python
end_day: str
```

- *Type:* str

---

##### `end_hour`<sup>Required</sup> <a name="end_hour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endHour"></a>

```python
end_hour: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `end_min`<sup>Required</sup> <a name="end_min" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endMin"></a>

```python
end_min: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `start_day`<sup>Required</sup> <a name="start_day" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startDay"></a>

```python
start_day: str
```

- *Type:* str

---

##### `start_hour`<sup>Required</sup> <a name="start_hour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startHour"></a>

```python
start_hour: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `start_min`<sup>Required</sup> <a name="start_min" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startMin"></a>

```python
start_min: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, TeamRoutingRuleTimeRestrictionRestrictions]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions">TeamRoutingRuleTimeRestrictionRestrictions</a>]

---



