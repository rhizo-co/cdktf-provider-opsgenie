# `data_opsgenie_heartbeat`

Refer to the Terraform Registory for docs: [`data_opsgenie_heartbeat`](https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat).

# `dataOpsgenieHeartbeat` Submodule <a name="`dataOpsgenieHeartbeat` Submodule" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### DataOpsgenieHeartbeat <a name="DataOpsgenieHeartbeat" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat"></a>

Represents a {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat opsgenie_heartbeat}.

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import data_opsgenie_heartbeat

dataOpsgenieHeartbeat.DataOpsgenieHeartbeat(
  scope: Construct,
  id: str,
  connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection] = None,
  count: typing.Union[typing.Union[int, float], TerraformCount] = None,
  depends_on: typing.List[ITerraformDependable] = None,
  for_each: ITerraformIterator = None,
  lifecycle: TerraformResourceLifecycle = None,
  provider: TerraformProvider = None,
  provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]] = None,
  name: str,
  alert_message: str = None,
  alert_priority: str = None,
  alert_tags: typing.List[str] = None,
  description: str = None,
  enabled: typing.Union[bool, IResolvable] = None,
  id: str = None,
  interval: typing.Union[int, float] = None,
  interval_unit: str = None,
  owner_team_id: str = None
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.id">id</a></code> | <code>str</code> | The scoped construct ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.connection">connection</a></code> | <code>typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.dependsOn">depends_on</a></code> | <code>typing.List[cdktf.ITerraformDependable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.provisioners">provisioners</a></code> | <code>typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.name">name</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#name DataOpsgenieHeartbeat#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.alertMessage">alert_message</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_message DataOpsgenieHeartbeat#alert_message}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.alertPriority">alert_priority</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_priority DataOpsgenieHeartbeat#alert_priority}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.alertTags">alert_tags</a></code> | <code>typing.List[str]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_tags DataOpsgenieHeartbeat#alert_tags}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.description">description</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#description DataOpsgenieHeartbeat#description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.enabled">enabled</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#enabled DataOpsgenieHeartbeat#enabled}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.id">id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#id DataOpsgenieHeartbeat#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.interval">interval</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#interval DataOpsgenieHeartbeat#interval}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.intervalUnit">interval_unit</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#interval_unit DataOpsgenieHeartbeat#interval_unit}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.ownerTeamId">owner_team_id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#owner_team_id DataOpsgenieHeartbeat#owner_team_id}. |

---

##### `scope`<sup>Required</sup> <a name="scope" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.id"></a>

- *Type:* str

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.connection"></a>

- *Type:* typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.count"></a>

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.dependsOn"></a>

- *Type:* typing.List[cdktf.ITerraformDependable]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.forEach"></a>

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.lifecycle"></a>

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.provider"></a>

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.provisioners"></a>

- *Type:* typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.name"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#name DataOpsgenieHeartbeat#name}.

---

##### `alert_message`<sup>Optional</sup> <a name="alert_message" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.alertMessage"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_message DataOpsgenieHeartbeat#alert_message}.

---

##### `alert_priority`<sup>Optional</sup> <a name="alert_priority" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.alertPriority"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_priority DataOpsgenieHeartbeat#alert_priority}.

---

##### `alert_tags`<sup>Optional</sup> <a name="alert_tags" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.alertTags"></a>

- *Type:* typing.List[str]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_tags DataOpsgenieHeartbeat#alert_tags}.

---

##### `description`<sup>Optional</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.description"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#description DataOpsgenieHeartbeat#description}.

---

##### `enabled`<sup>Optional</sup> <a name="enabled" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.enabled"></a>

- *Type:* typing.Union[bool, cdktf.IResolvable]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#enabled DataOpsgenieHeartbeat#enabled}.

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.id"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#id DataOpsgenieHeartbeat#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `interval`<sup>Optional</sup> <a name="interval" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.interval"></a>

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#interval DataOpsgenieHeartbeat#interval}.

---

##### `interval_unit`<sup>Optional</sup> <a name="interval_unit" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.intervalUnit"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#interval_unit DataOpsgenieHeartbeat#interval_unit}.

---

##### `owner_team_id`<sup>Optional</sup> <a name="owner_team_id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.ownerTeamId"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#owner_team_id DataOpsgenieHeartbeat#owner_team_id}.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.toString">to_string</a></code> | Returns a string representation of this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.addOverride">add_override</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.overrideLogicalId">override_logical_id</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetOverrideLogicalId">reset_override_logical_id</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.toMetadata">to_metadata</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.toTerraform">to_terraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetAlertMessage">reset_alert_message</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetAlertPriority">reset_alert_priority</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetAlertTags">reset_alert_tags</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetDescription">reset_description</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetEnabled">reset_enabled</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetId">reset_id</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetInterval">reset_interval</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetIntervalUnit">reset_interval_unit</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetOwnerTeamId">reset_owner_team_id</a></code> | *No description.* |

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.toString"></a>

```python
def to_string() -> str
```

Returns a string representation of this construct.

##### `add_override` <a name="add_override" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.addOverride"></a>

```python
def add_override(
  path: str,
  value: typing.Any
) -> None
```

###### `path`<sup>Required</sup> <a name="path" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.addOverride.parameter.path"></a>

- *Type:* str

---

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.addOverride.parameter.value"></a>

- *Type:* typing.Any

---

##### `override_logical_id` <a name="override_logical_id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.overrideLogicalId"></a>

```python
def override_logical_id(
  new_logical_id: str
) -> None
```

Overrides the auto-generated logical ID with a specific ID.

###### `new_logical_id`<sup>Required</sup> <a name="new_logical_id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* str

The new logical ID to use for this stack element.

---

##### `reset_override_logical_id` <a name="reset_override_logical_id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetOverrideLogicalId"></a>

```python
def reset_override_logical_id() -> None
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `to_metadata` <a name="to_metadata" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.toMetadata"></a>

```python
def to_metadata() -> typing.Any
```

##### `to_terraform` <a name="to_terraform" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.toTerraform"></a>

```python
def to_terraform() -> typing.Any
```

Adds this resource to the terraform JSON output.

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `reset_alert_message` <a name="reset_alert_message" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetAlertMessage"></a>

```python
def reset_alert_message() -> None
```

##### `reset_alert_priority` <a name="reset_alert_priority" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetAlertPriority"></a>

```python
def reset_alert_priority() -> None
```

##### `reset_alert_tags` <a name="reset_alert_tags" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetAlertTags"></a>

```python
def reset_alert_tags() -> None
```

##### `reset_description` <a name="reset_description" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetDescription"></a>

```python
def reset_description() -> None
```

##### `reset_enabled` <a name="reset_enabled" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetEnabled"></a>

```python
def reset_enabled() -> None
```

##### `reset_id` <a name="reset_id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetId"></a>

```python
def reset_id() -> None
```

##### `reset_interval` <a name="reset_interval" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetInterval"></a>

```python
def reset_interval() -> None
```

##### `reset_interval_unit` <a name="reset_interval_unit" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetIntervalUnit"></a>

```python
def reset_interval_unit() -> None
```

##### `reset_owner_team_id` <a name="reset_owner_team_id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetOwnerTeamId"></a>

```python
def reset_owner_team_id() -> None
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isConstruct">is_construct</a></code> | Checks if `x` is a construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isTerraformElement">is_terraform_element</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isTerraformDataSource">is_terraform_data_source</a></code> | *No description.* |

---

##### `is_construct` <a name="is_construct" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isConstruct"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import data_opsgenie_heartbeat

dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.is_construct(
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

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isConstruct.parameter.x"></a>

- *Type:* typing.Any

Any object.

---

##### `is_terraform_element` <a name="is_terraform_element" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isTerraformElement"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import data_opsgenie_heartbeat

dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.is_terraform_element(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isTerraformElement.parameter.x"></a>

- *Type:* typing.Any

---

##### `is_terraform_data_source` <a name="is_terraform_data_source" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isTerraformDataSource"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import data_opsgenie_heartbeat

dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.is_terraform_data_source(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isTerraformDataSource.parameter.x"></a>

- *Type:* typing.Any

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.node">node</a></code> | <code>constructs.Node</code> | The tree node. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.cdktfStack">cdktf_stack</a></code> | <code>cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.friendlyUniqueId">friendly_unique_id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.terraformMetaArguments">terraform_meta_arguments</a></code> | <code>typing.Mapping[typing.Any]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.terraformResourceType">terraform_resource_type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.terraformGeneratorMetadata">terraform_generator_metadata</a></code> | <code>cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.dependsOn">depends_on</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertMessageInput">alert_message_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertPriorityInput">alert_priority_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertTagsInput">alert_tags_input</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.descriptionInput">description_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.enabledInput">enabled_input</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.idInput">id_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.intervalInput">interval_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.intervalUnitInput">interval_unit_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.nameInput">name_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.ownerTeamIdInput">owner_team_id_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertMessage">alert_message</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertPriority">alert_priority</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertTags">alert_tags</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.description">description</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.enabled">enabled</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.id">id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.interval">interval</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.intervalUnit">interval_unit</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.name">name</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.ownerTeamId">owner_team_id</a></code> | <code>str</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.node"></a>

```python
node: Node
```

- *Type:* constructs.Node

The tree node.

---

##### `cdktf_stack`<sup>Required</sup> <a name="cdktf_stack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.cdktfStack"></a>

```python
cdktf_stack: TerraformStack
```

- *Type:* cdktf.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `friendly_unique_id`<sup>Required</sup> <a name="friendly_unique_id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.friendlyUniqueId"></a>

```python
friendly_unique_id: str
```

- *Type:* str

---

##### `terraform_meta_arguments`<sup>Required</sup> <a name="terraform_meta_arguments" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.terraformMetaArguments"></a>

```python
terraform_meta_arguments: typing.Mapping[typing.Any]
```

- *Type:* typing.Mapping[typing.Any]

---

##### `terraform_resource_type`<sup>Required</sup> <a name="terraform_resource_type" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.terraformResourceType"></a>

```python
terraform_resource_type: str
```

- *Type:* str

---

##### `terraform_generator_metadata`<sup>Optional</sup> <a name="terraform_generator_metadata" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.terraformGeneratorMetadata"></a>

```python
terraform_generator_metadata: TerraformProviderGeneratorMetadata
```

- *Type:* cdktf.TerraformProviderGeneratorMetadata

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.count"></a>

```python
count: typing.Union[typing.Union[int, float], TerraformCount]
```

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.dependsOn"></a>

```python
depends_on: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.forEach"></a>

```python
for_each: ITerraformIterator
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.lifecycle"></a>

```python
lifecycle: TerraformResourceLifecycle
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.provider"></a>

```python
provider: TerraformProvider
```

- *Type:* cdktf.TerraformProvider

---

##### `alert_message_input`<sup>Optional</sup> <a name="alert_message_input" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertMessageInput"></a>

```python
alert_message_input: str
```

- *Type:* str

---

##### `alert_priority_input`<sup>Optional</sup> <a name="alert_priority_input" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertPriorityInput"></a>

```python
alert_priority_input: str
```

- *Type:* str

---

##### `alert_tags_input`<sup>Optional</sup> <a name="alert_tags_input" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertTagsInput"></a>

```python
alert_tags_input: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `description_input`<sup>Optional</sup> <a name="description_input" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.descriptionInput"></a>

```python
description_input: str
```

- *Type:* str

---

##### `enabled_input`<sup>Optional</sup> <a name="enabled_input" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.enabledInput"></a>

```python
enabled_input: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `id_input`<sup>Optional</sup> <a name="id_input" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.idInput"></a>

```python
id_input: str
```

- *Type:* str

---

##### `interval_input`<sup>Optional</sup> <a name="interval_input" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.intervalInput"></a>

```python
interval_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `interval_unit_input`<sup>Optional</sup> <a name="interval_unit_input" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.intervalUnitInput"></a>

```python
interval_unit_input: str
```

- *Type:* str

---

##### `name_input`<sup>Optional</sup> <a name="name_input" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.nameInput"></a>

```python
name_input: str
```

- *Type:* str

---

##### `owner_team_id_input`<sup>Optional</sup> <a name="owner_team_id_input" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.ownerTeamIdInput"></a>

```python
owner_team_id_input: str
```

- *Type:* str

---

##### `alert_message`<sup>Required</sup> <a name="alert_message" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertMessage"></a>

```python
alert_message: str
```

- *Type:* str

---

##### `alert_priority`<sup>Required</sup> <a name="alert_priority" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertPriority"></a>

```python
alert_priority: str
```

- *Type:* str

---

##### `alert_tags`<sup>Required</sup> <a name="alert_tags" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertTags"></a>

```python
alert_tags: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `description`<sup>Required</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.description"></a>

```python
description: str
```

- *Type:* str

---

##### `enabled`<sup>Required</sup> <a name="enabled" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.enabled"></a>

```python
enabled: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.id"></a>

```python
id: str
```

- *Type:* str

---

##### `interval`<sup>Required</sup> <a name="interval" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.interval"></a>

```python
interval: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `interval_unit`<sup>Required</sup> <a name="interval_unit" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.intervalUnit"></a>

```python
interval_unit: str
```

- *Type:* str

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.name"></a>

```python
name: str
```

- *Type:* str

---

##### `owner_team_id`<sup>Required</sup> <a name="owner_team_id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.ownerTeamId"></a>

```python
owner_team_id: str
```

- *Type:* str

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.tfResourceType">tfResourceType</a></code> | <code>str</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.tfResourceType"></a>

```python
tfResourceType: str
```

- *Type:* str

---

## Structs <a name="Structs" id="Structs"></a>

### DataOpsgenieHeartbeatConfig <a name="DataOpsgenieHeartbeatConfig" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import data_opsgenie_heartbeat

dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig(
  connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection] = None,
  count: typing.Union[typing.Union[int, float], TerraformCount] = None,
  depends_on: typing.List[ITerraformDependable] = None,
  for_each: ITerraformIterator = None,
  lifecycle: TerraformResourceLifecycle = None,
  provider: TerraformProvider = None,
  provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]] = None,
  name: str,
  alert_message: str = None,
  alert_priority: str = None,
  alert_tags: typing.List[str] = None,
  description: str = None,
  enabled: typing.Union[bool, IResolvable] = None,
  id: str = None,
  interval: typing.Union[int, float] = None,
  interval_unit: str = None,
  owner_team_id: str = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.connection">connection</a></code> | <code>typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.dependsOn">depends_on</a></code> | <code>typing.List[cdktf.ITerraformDependable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.provisioners">provisioners</a></code> | <code>typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.name">name</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#name DataOpsgenieHeartbeat#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.alertMessage">alert_message</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_message DataOpsgenieHeartbeat#alert_message}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.alertPriority">alert_priority</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_priority DataOpsgenieHeartbeat#alert_priority}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.alertTags">alert_tags</a></code> | <code>typing.List[str]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_tags DataOpsgenieHeartbeat#alert_tags}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.description">description</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#description DataOpsgenieHeartbeat#description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.enabled">enabled</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#enabled DataOpsgenieHeartbeat#enabled}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.id">id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#id DataOpsgenieHeartbeat#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.interval">interval</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#interval DataOpsgenieHeartbeat#interval}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.intervalUnit">interval_unit</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#interval_unit DataOpsgenieHeartbeat#interval_unit}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.ownerTeamId">owner_team_id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#owner_team_id DataOpsgenieHeartbeat#owner_team_id}. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.connection"></a>

```python
connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection]
```

- *Type:* typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.count"></a>

```python
count: typing.Union[typing.Union[int, float], TerraformCount]
```

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.dependsOn"></a>

```python
depends_on: typing.List[ITerraformDependable]
```

- *Type:* typing.List[cdktf.ITerraformDependable]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.forEach"></a>

```python
for_each: ITerraformIterator
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.lifecycle"></a>

```python
lifecycle: TerraformResourceLifecycle
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.provider"></a>

```python
provider: TerraformProvider
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.provisioners"></a>

```python
provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]]
```

- *Type:* typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.name"></a>

```python
name: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#name DataOpsgenieHeartbeat#name}.

---

##### `alert_message`<sup>Optional</sup> <a name="alert_message" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.alertMessage"></a>

```python
alert_message: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_message DataOpsgenieHeartbeat#alert_message}.

---

##### `alert_priority`<sup>Optional</sup> <a name="alert_priority" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.alertPriority"></a>

```python
alert_priority: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_priority DataOpsgenieHeartbeat#alert_priority}.

---

##### `alert_tags`<sup>Optional</sup> <a name="alert_tags" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.alertTags"></a>

```python
alert_tags: typing.List[str]
```

- *Type:* typing.List[str]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_tags DataOpsgenieHeartbeat#alert_tags}.

---

##### `description`<sup>Optional</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.description"></a>

```python
description: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#description DataOpsgenieHeartbeat#description}.

---

##### `enabled`<sup>Optional</sup> <a name="enabled" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.enabled"></a>

```python
enabled: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#enabled DataOpsgenieHeartbeat#enabled}.

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.id"></a>

```python
id: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#id DataOpsgenieHeartbeat#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `interval`<sup>Optional</sup> <a name="interval" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.interval"></a>

```python
interval: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#interval DataOpsgenieHeartbeat#interval}.

---

##### `interval_unit`<sup>Optional</sup> <a name="interval_unit" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.intervalUnit"></a>

```python
interval_unit: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#interval_unit DataOpsgenieHeartbeat#interval_unit}.

---

##### `owner_team_id`<sup>Optional</sup> <a name="owner_team_id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.ownerTeamId"></a>

```python
owner_team_id: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#owner_team_id DataOpsgenieHeartbeat#owner_team_id}.

---



