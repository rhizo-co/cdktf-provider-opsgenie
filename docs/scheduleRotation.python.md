# `opsgenie_schedule_rotation`

Refer to the Terraform Registory for docs: [`opsgenie_schedule_rotation`](https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation).

# `scheduleRotation` Submodule <a name="`scheduleRotation` Submodule" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### ScheduleRotation <a name="ScheduleRotation" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation"></a>

Represents a {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation opsgenie_schedule_rotation}.

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import schedule_rotation

scheduleRotation.ScheduleRotation(
  scope: Construct,
  id: str,
  connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection] = None,
  count: typing.Union[typing.Union[int, float], TerraformCount] = None,
  depends_on: typing.List[ITerraformDependable] = None,
  for_each: ITerraformIterator = None,
  lifecycle: TerraformResourceLifecycle = None,
  provider: TerraformProvider = None,
  provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]] = None,
  participant: typing.Union[IResolvable, typing.List[ScheduleRotationParticipant]],
  schedule_id: str,
  start_date: str,
  type: str,
  end_date: str = None,
  id: str = None,
  length: typing.Union[int, float] = None,
  name: str = None,
  time_restriction: typing.Union[IResolvable, typing.List[ScheduleRotationTimeRestriction]] = None
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.id">id</a></code> | <code>str</code> | The scoped construct ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.connection">connection</a></code> | <code>typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.dependsOn">depends_on</a></code> | <code>typing.List[cdktf.ITerraformDependable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.provisioners">provisioners</a></code> | <code>typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.participant">participant</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipant">ScheduleRotationParticipant</a>]]</code> | participant block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.scheduleId">schedule_id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#schedule_id ScheduleRotation#schedule_id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.startDate">start_date</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#start_date ScheduleRotation#start_date}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.type">type</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#type ScheduleRotation#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.endDate">end_date</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#end_date ScheduleRotation#end_date}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.id">id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#id ScheduleRotation#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.length">length</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#length ScheduleRotation#length}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.name">name</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#name ScheduleRotation#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.timeRestriction">time_restriction</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestriction">ScheduleRotationTimeRestriction</a>]]</code> | time_restriction block. |

---

##### `scope`<sup>Required</sup> <a name="scope" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.id"></a>

- *Type:* str

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.connection"></a>

- *Type:* typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.count"></a>

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.dependsOn"></a>

- *Type:* typing.List[cdktf.ITerraformDependable]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.forEach"></a>

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.lifecycle"></a>

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.provider"></a>

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.provisioners"></a>

- *Type:* typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]

---

##### `participant`<sup>Required</sup> <a name="participant" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.participant"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipant">ScheduleRotationParticipant</a>]]

participant block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#participant ScheduleRotation#participant}

---

##### `schedule_id`<sup>Required</sup> <a name="schedule_id" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.scheduleId"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#schedule_id ScheduleRotation#schedule_id}.

---

##### `start_date`<sup>Required</sup> <a name="start_date" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.startDate"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#start_date ScheduleRotation#start_date}.

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.type"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#type ScheduleRotation#type}.

---

##### `end_date`<sup>Optional</sup> <a name="end_date" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.endDate"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#end_date ScheduleRotation#end_date}.

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.id"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#id ScheduleRotation#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `length`<sup>Optional</sup> <a name="length" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.length"></a>

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#length ScheduleRotation#length}.

---

##### `name`<sup>Optional</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.name"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#name ScheduleRotation#name}.

---

##### `time_restriction`<sup>Optional</sup> <a name="time_restriction" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.timeRestriction"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestriction">ScheduleRotationTimeRestriction</a>]]

time_restriction block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#time_restriction ScheduleRotation#time_restriction}

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.toString">to_string</a></code> | Returns a string representation of this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.addOverride">add_override</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.overrideLogicalId">override_logical_id</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.resetOverrideLogicalId">reset_override_logical_id</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.toMetadata">to_metadata</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.toTerraform">to_terraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.putParticipant">put_participant</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.putTimeRestriction">put_time_restriction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.resetEndDate">reset_end_date</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.resetId">reset_id</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.resetLength">reset_length</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.resetName">reset_name</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.resetTimeRestriction">reset_time_restriction</a></code> | *No description.* |

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.toString"></a>

```python
def to_string() -> str
```

Returns a string representation of this construct.

##### `add_override` <a name="add_override" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.addOverride"></a>

```python
def add_override(
  path: str,
  value: typing.Any
) -> None
```

###### `path`<sup>Required</sup> <a name="path" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.addOverride.parameter.path"></a>

- *Type:* str

---

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.addOverride.parameter.value"></a>

- *Type:* typing.Any

---

##### `override_logical_id` <a name="override_logical_id" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.overrideLogicalId"></a>

```python
def override_logical_id(
  new_logical_id: str
) -> None
```

Overrides the auto-generated logical ID with a specific ID.

###### `new_logical_id`<sup>Required</sup> <a name="new_logical_id" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* str

The new logical ID to use for this stack element.

---

##### `reset_override_logical_id` <a name="reset_override_logical_id" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.resetOverrideLogicalId"></a>

```python
def reset_override_logical_id() -> None
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `to_metadata` <a name="to_metadata" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.toMetadata"></a>

```python
def to_metadata() -> typing.Any
```

##### `to_terraform` <a name="to_terraform" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.toTerraform"></a>

```python
def to_terraform() -> typing.Any
```

Adds this resource to the terraform JSON output.

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `put_participant` <a name="put_participant" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.putParticipant"></a>

```python
def put_participant(
  value: typing.Union[IResolvable, typing.List[ScheduleRotationParticipant]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.putParticipant.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipant">ScheduleRotationParticipant</a>]]

---

##### `put_time_restriction` <a name="put_time_restriction" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.putTimeRestriction"></a>

```python
def put_time_restriction(
  value: typing.Union[IResolvable, typing.List[ScheduleRotationTimeRestriction]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.putTimeRestriction.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestriction">ScheduleRotationTimeRestriction</a>]]

---

##### `reset_end_date` <a name="reset_end_date" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.resetEndDate"></a>

```python
def reset_end_date() -> None
```

##### `reset_id` <a name="reset_id" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.resetId"></a>

```python
def reset_id() -> None
```

##### `reset_length` <a name="reset_length" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.resetLength"></a>

```python
def reset_length() -> None
```

##### `reset_name` <a name="reset_name" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.resetName"></a>

```python
def reset_name() -> None
```

##### `reset_time_restriction` <a name="reset_time_restriction" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.resetTimeRestriction"></a>

```python
def reset_time_restriction() -> None
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.isConstruct">is_construct</a></code> | Checks if `x` is a construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.isTerraformElement">is_terraform_element</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.isTerraformResource">is_terraform_resource</a></code> | *No description.* |

---

##### `is_construct` <a name="is_construct" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.isConstruct"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import schedule_rotation

scheduleRotation.ScheduleRotation.is_construct(
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

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.isConstruct.parameter.x"></a>

- *Type:* typing.Any

Any object.

---

##### `is_terraform_element` <a name="is_terraform_element" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.isTerraformElement"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import schedule_rotation

scheduleRotation.ScheduleRotation.is_terraform_element(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.isTerraformElement.parameter.x"></a>

- *Type:* typing.Any

---

##### `is_terraform_resource` <a name="is_terraform_resource" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.isTerraformResource"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import schedule_rotation

scheduleRotation.ScheduleRotation.is_terraform_resource(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.isTerraformResource.parameter.x"></a>

- *Type:* typing.Any

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.node">node</a></code> | <code>constructs.Node</code> | The tree node. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.cdktfStack">cdktf_stack</a></code> | <code>cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.friendlyUniqueId">friendly_unique_id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.terraformMetaArguments">terraform_meta_arguments</a></code> | <code>typing.Mapping[typing.Any]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.terraformResourceType">terraform_resource_type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.terraformGeneratorMetadata">terraform_generator_metadata</a></code> | <code>cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.connection">connection</a></code> | <code>typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.dependsOn">depends_on</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.provisioners">provisioners</a></code> | <code>typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.participant">participant</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList">ScheduleRotationParticipantList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.timeRestriction">time_restriction</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList">ScheduleRotationTimeRestrictionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.endDateInput">end_date_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.idInput">id_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.lengthInput">length_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.nameInput">name_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.participantInput">participant_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipant">ScheduleRotationParticipant</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.scheduleIdInput">schedule_id_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.startDateInput">start_date_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.timeRestrictionInput">time_restriction_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestriction">ScheduleRotationTimeRestriction</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.typeInput">type_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.endDate">end_date</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.id">id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.length">length</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.name">name</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.scheduleId">schedule_id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.startDate">start_date</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.type">type</a></code> | <code>str</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.node"></a>

```python
node: Node
```

- *Type:* constructs.Node

The tree node.

---

##### `cdktf_stack`<sup>Required</sup> <a name="cdktf_stack" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.cdktfStack"></a>

```python
cdktf_stack: TerraformStack
```

- *Type:* cdktf.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `friendly_unique_id`<sup>Required</sup> <a name="friendly_unique_id" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.friendlyUniqueId"></a>

```python
friendly_unique_id: str
```

- *Type:* str

---

##### `terraform_meta_arguments`<sup>Required</sup> <a name="terraform_meta_arguments" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.terraformMetaArguments"></a>

```python
terraform_meta_arguments: typing.Mapping[typing.Any]
```

- *Type:* typing.Mapping[typing.Any]

---

##### `terraform_resource_type`<sup>Required</sup> <a name="terraform_resource_type" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.terraformResourceType"></a>

```python
terraform_resource_type: str
```

- *Type:* str

---

##### `terraform_generator_metadata`<sup>Optional</sup> <a name="terraform_generator_metadata" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.terraformGeneratorMetadata"></a>

```python
terraform_generator_metadata: TerraformProviderGeneratorMetadata
```

- *Type:* cdktf.TerraformProviderGeneratorMetadata

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.connection"></a>

```python
connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection]
```

- *Type:* typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.count"></a>

```python
count: typing.Union[typing.Union[int, float], TerraformCount]
```

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.dependsOn"></a>

```python
depends_on: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.forEach"></a>

```python
for_each: ITerraformIterator
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.lifecycle"></a>

```python
lifecycle: TerraformResourceLifecycle
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.provider"></a>

```python
provider: TerraformProvider
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.provisioners"></a>

```python
provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]]
```

- *Type:* typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]

---

##### `participant`<sup>Required</sup> <a name="participant" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.participant"></a>

```python
participant: ScheduleRotationParticipantList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList">ScheduleRotationParticipantList</a>

---

##### `time_restriction`<sup>Required</sup> <a name="time_restriction" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.timeRestriction"></a>

```python
time_restriction: ScheduleRotationTimeRestrictionList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList">ScheduleRotationTimeRestrictionList</a>

---

##### `end_date_input`<sup>Optional</sup> <a name="end_date_input" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.endDateInput"></a>

```python
end_date_input: str
```

- *Type:* str

---

##### `id_input`<sup>Optional</sup> <a name="id_input" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.idInput"></a>

```python
id_input: str
```

- *Type:* str

---

##### `length_input`<sup>Optional</sup> <a name="length_input" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.lengthInput"></a>

```python
length_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `name_input`<sup>Optional</sup> <a name="name_input" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.nameInput"></a>

```python
name_input: str
```

- *Type:* str

---

##### `participant_input`<sup>Optional</sup> <a name="participant_input" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.participantInput"></a>

```python
participant_input: typing.Union[IResolvable, typing.List[ScheduleRotationParticipant]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipant">ScheduleRotationParticipant</a>]]

---

##### `schedule_id_input`<sup>Optional</sup> <a name="schedule_id_input" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.scheduleIdInput"></a>

```python
schedule_id_input: str
```

- *Type:* str

---

##### `start_date_input`<sup>Optional</sup> <a name="start_date_input" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.startDateInput"></a>

```python
start_date_input: str
```

- *Type:* str

---

##### `time_restriction_input`<sup>Optional</sup> <a name="time_restriction_input" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.timeRestrictionInput"></a>

```python
time_restriction_input: typing.Union[IResolvable, typing.List[ScheduleRotationTimeRestriction]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestriction">ScheduleRotationTimeRestriction</a>]]

---

##### `type_input`<sup>Optional</sup> <a name="type_input" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.typeInput"></a>

```python
type_input: str
```

- *Type:* str

---

##### `end_date`<sup>Required</sup> <a name="end_date" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.endDate"></a>

```python
end_date: str
```

- *Type:* str

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.id"></a>

```python
id: str
```

- *Type:* str

---

##### `length`<sup>Required</sup> <a name="length" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.length"></a>

```python
length: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.name"></a>

```python
name: str
```

- *Type:* str

---

##### `schedule_id`<sup>Required</sup> <a name="schedule_id" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.scheduleId"></a>

```python
schedule_id: str
```

- *Type:* str

---

##### `start_date`<sup>Required</sup> <a name="start_date" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.startDate"></a>

```python
start_date: str
```

- *Type:* str

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.type"></a>

```python
type: str
```

- *Type:* str

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.tfResourceType">tfResourceType</a></code> | <code>str</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.tfResourceType"></a>

```python
tfResourceType: str
```

- *Type:* str

---

## Structs <a name="Structs" id="Structs"></a>

### ScheduleRotationConfig <a name="ScheduleRotationConfig" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import schedule_rotation

scheduleRotation.ScheduleRotationConfig(
  connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection] = None,
  count: typing.Union[typing.Union[int, float], TerraformCount] = None,
  depends_on: typing.List[ITerraformDependable] = None,
  for_each: ITerraformIterator = None,
  lifecycle: TerraformResourceLifecycle = None,
  provider: TerraformProvider = None,
  provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]] = None,
  participant: typing.Union[IResolvable, typing.List[ScheduleRotationParticipant]],
  schedule_id: str,
  start_date: str,
  type: str,
  end_date: str = None,
  id: str = None,
  length: typing.Union[int, float] = None,
  name: str = None,
  time_restriction: typing.Union[IResolvable, typing.List[ScheduleRotationTimeRestriction]] = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.connection">connection</a></code> | <code>typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.dependsOn">depends_on</a></code> | <code>typing.List[cdktf.ITerraformDependable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.provisioners">provisioners</a></code> | <code>typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.participant">participant</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipant">ScheduleRotationParticipant</a>]]</code> | participant block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.scheduleId">schedule_id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#schedule_id ScheduleRotation#schedule_id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.startDate">start_date</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#start_date ScheduleRotation#start_date}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.type">type</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#type ScheduleRotation#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.endDate">end_date</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#end_date ScheduleRotation#end_date}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.id">id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#id ScheduleRotation#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.length">length</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#length ScheduleRotation#length}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.name">name</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#name ScheduleRotation#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.timeRestriction">time_restriction</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestriction">ScheduleRotationTimeRestriction</a>]]</code> | time_restriction block. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.connection"></a>

```python
connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection]
```

- *Type:* typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.count"></a>

```python
count: typing.Union[typing.Union[int, float], TerraformCount]
```

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.dependsOn"></a>

```python
depends_on: typing.List[ITerraformDependable]
```

- *Type:* typing.List[cdktf.ITerraformDependable]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.forEach"></a>

```python
for_each: ITerraformIterator
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.lifecycle"></a>

```python
lifecycle: TerraformResourceLifecycle
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.provider"></a>

```python
provider: TerraformProvider
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.provisioners"></a>

```python
provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]]
```

- *Type:* typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]

---

##### `participant`<sup>Required</sup> <a name="participant" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.participant"></a>

```python
participant: typing.Union[IResolvable, typing.List[ScheduleRotationParticipant]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipant">ScheduleRotationParticipant</a>]]

participant block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#participant ScheduleRotation#participant}

---

##### `schedule_id`<sup>Required</sup> <a name="schedule_id" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.scheduleId"></a>

```python
schedule_id: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#schedule_id ScheduleRotation#schedule_id}.

---

##### `start_date`<sup>Required</sup> <a name="start_date" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.startDate"></a>

```python
start_date: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#start_date ScheduleRotation#start_date}.

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.type"></a>

```python
type: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#type ScheduleRotation#type}.

---

##### `end_date`<sup>Optional</sup> <a name="end_date" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.endDate"></a>

```python
end_date: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#end_date ScheduleRotation#end_date}.

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.id"></a>

```python
id: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#id ScheduleRotation#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `length`<sup>Optional</sup> <a name="length" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.length"></a>

```python
length: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#length ScheduleRotation#length}.

---

##### `name`<sup>Optional</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.name"></a>

```python
name: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#name ScheduleRotation#name}.

---

##### `time_restriction`<sup>Optional</sup> <a name="time_restriction" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.timeRestriction"></a>

```python
time_restriction: typing.Union[IResolvable, typing.List[ScheduleRotationTimeRestriction]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestriction">ScheduleRotationTimeRestriction</a>]]

time_restriction block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#time_restriction ScheduleRotation#time_restriction}

---

### ScheduleRotationParticipant <a name="ScheduleRotationParticipant" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipant"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipant.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import schedule_rotation

scheduleRotation.ScheduleRotationParticipant(
  type: str,
  id: str = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipant.property.type">type</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#type ScheduleRotation#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipant.property.id">id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#id ScheduleRotation#id}. |

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipant.property.type"></a>

```python
type: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#type ScheduleRotation#type}.

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipant.property.id"></a>

```python
id: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#id ScheduleRotation#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

### ScheduleRotationTimeRestriction <a name="ScheduleRotationTimeRestriction" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestriction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestriction.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import schedule_rotation

scheduleRotation.ScheduleRotationTimeRestriction(
  type: str,
  restriction: typing.Union[IResolvable, typing.List[ScheduleRotationTimeRestrictionRestriction]] = None,
  restrictions: typing.Union[IResolvable, typing.List[ScheduleRotationTimeRestrictionRestrictions]] = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestriction.property.type">type</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#type ScheduleRotation#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestriction.property.restriction">restriction</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestriction">ScheduleRotationTimeRestrictionRestriction</a>]]</code> | restriction block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestriction.property.restrictions">restrictions</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictions">ScheduleRotationTimeRestrictionRestrictions</a>]]</code> | restrictions block. |

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestriction.property.type"></a>

```python
type: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#type ScheduleRotation#type}.

---

##### `restriction`<sup>Optional</sup> <a name="restriction" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestriction.property.restriction"></a>

```python
restriction: typing.Union[IResolvable, typing.List[ScheduleRotationTimeRestrictionRestriction]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestriction">ScheduleRotationTimeRestrictionRestriction</a>]]

restriction block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#restriction ScheduleRotation#restriction}

---

##### `restrictions`<sup>Optional</sup> <a name="restrictions" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestriction.property.restrictions"></a>

```python
restrictions: typing.Union[IResolvable, typing.List[ScheduleRotationTimeRestrictionRestrictions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictions">ScheduleRotationTimeRestrictionRestrictions</a>]]

restrictions block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#restrictions ScheduleRotation#restrictions}

---

### ScheduleRotationTimeRestrictionRestriction <a name="ScheduleRotationTimeRestrictionRestriction" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestriction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestriction.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import schedule_rotation

scheduleRotation.ScheduleRotationTimeRestrictionRestriction(
  end_hour: typing.Union[int, float],
  end_min: typing.Union[int, float],
  start_hour: typing.Union[int, float],
  start_min: typing.Union[int, float]
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestriction.property.endHour">end_hour</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#end_hour ScheduleRotation#end_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestriction.property.endMin">end_min</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#end_min ScheduleRotation#end_min}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestriction.property.startHour">start_hour</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#start_hour ScheduleRotation#start_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestriction.property.startMin">start_min</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#start_min ScheduleRotation#start_min}. |

---

##### `end_hour`<sup>Required</sup> <a name="end_hour" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestriction.property.endHour"></a>

```python
end_hour: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#end_hour ScheduleRotation#end_hour}.

---

##### `end_min`<sup>Required</sup> <a name="end_min" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestriction.property.endMin"></a>

```python
end_min: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#end_min ScheduleRotation#end_min}.

---

##### `start_hour`<sup>Required</sup> <a name="start_hour" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestriction.property.startHour"></a>

```python
start_hour: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#start_hour ScheduleRotation#start_hour}.

---

##### `start_min`<sup>Required</sup> <a name="start_min" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestriction.property.startMin"></a>

```python
start_min: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#start_min ScheduleRotation#start_min}.

---

### ScheduleRotationTimeRestrictionRestrictions <a name="ScheduleRotationTimeRestrictionRestrictions" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictions"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictions.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import schedule_rotation

scheduleRotation.ScheduleRotationTimeRestrictionRestrictions(
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
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictions.property.endDay">end_day</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#end_day ScheduleRotation#end_day}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictions.property.endHour">end_hour</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#end_hour ScheduleRotation#end_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictions.property.endMin">end_min</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#end_min ScheduleRotation#end_min}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictions.property.startDay">start_day</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#start_day ScheduleRotation#start_day}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictions.property.startHour">start_hour</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#start_hour ScheduleRotation#start_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictions.property.startMin">start_min</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#start_min ScheduleRotation#start_min}. |

---

##### `end_day`<sup>Required</sup> <a name="end_day" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictions.property.endDay"></a>

```python
end_day: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#end_day ScheduleRotation#end_day}.

---

##### `end_hour`<sup>Required</sup> <a name="end_hour" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictions.property.endHour"></a>

```python
end_hour: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#end_hour ScheduleRotation#end_hour}.

---

##### `end_min`<sup>Required</sup> <a name="end_min" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictions.property.endMin"></a>

```python
end_min: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#end_min ScheduleRotation#end_min}.

---

##### `start_day`<sup>Required</sup> <a name="start_day" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictions.property.startDay"></a>

```python
start_day: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#start_day ScheduleRotation#start_day}.

---

##### `start_hour`<sup>Required</sup> <a name="start_hour" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictions.property.startHour"></a>

```python
start_hour: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#start_hour ScheduleRotation#start_hour}.

---

##### `start_min`<sup>Required</sup> <a name="start_min" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictions.property.startMin"></a>

```python
start_min: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#start_min ScheduleRotation#start_min}.

---

## Classes <a name="Classes" id="Classes"></a>

### ScheduleRotationParticipantList <a name="ScheduleRotationParticipantList" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import schedule_rotation

scheduleRotation.ScheduleRotationParticipantList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> ScheduleRotationParticipantOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipant">ScheduleRotationParticipant</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[ScheduleRotationParticipant]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipant">ScheduleRotationParticipant</a>]]

---


### ScheduleRotationParticipantOutputReference <a name="ScheduleRotationParticipantOutputReference" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import schedule_rotation

scheduleRotation.ScheduleRotationParticipantOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.resetId">reset_id</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `reset_id` <a name="reset_id" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.resetId"></a>

```python
def reset_id() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.property.idInput">id_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.property.typeInput">type_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.property.id">id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.property.type">type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipant">ScheduleRotationParticipant</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `id_input`<sup>Optional</sup> <a name="id_input" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.property.idInput"></a>

```python
id_input: str
```

- *Type:* str

---

##### `type_input`<sup>Optional</sup> <a name="type_input" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.property.typeInput"></a>

```python
type_input: str
```

- *Type:* str

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.property.id"></a>

```python
id: str
```

- *Type:* str

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.property.type"></a>

```python
type: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, ScheduleRotationParticipant]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipant">ScheduleRotationParticipant</a>]

---


### ScheduleRotationTimeRestrictionList <a name="ScheduleRotationTimeRestrictionList" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import schedule_rotation

scheduleRotation.ScheduleRotationTimeRestrictionList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> ScheduleRotationTimeRestrictionOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestriction">ScheduleRotationTimeRestriction</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[ScheduleRotationTimeRestriction]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestriction">ScheduleRotationTimeRestriction</a>]]

---


### ScheduleRotationTimeRestrictionOutputReference <a name="ScheduleRotationTimeRestrictionOutputReference" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import schedule_rotation

scheduleRotation.ScheduleRotationTimeRestrictionOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.putRestriction">put_restriction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.putRestrictions">put_restrictions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.resetRestriction">reset_restriction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.resetRestrictions">reset_restrictions</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `put_restriction` <a name="put_restriction" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.putRestriction"></a>

```python
def put_restriction(
  value: typing.Union[IResolvable, typing.List[ScheduleRotationTimeRestrictionRestriction]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.putRestriction.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestriction">ScheduleRotationTimeRestrictionRestriction</a>]]

---

##### `put_restrictions` <a name="put_restrictions" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.putRestrictions"></a>

```python
def put_restrictions(
  value: typing.Union[IResolvable, typing.List[ScheduleRotationTimeRestrictionRestrictions]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.putRestrictions.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictions">ScheduleRotationTimeRestrictionRestrictions</a>]]

---

##### `reset_restriction` <a name="reset_restriction" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.resetRestriction"></a>

```python
def reset_restriction() -> None
```

##### `reset_restrictions` <a name="reset_restrictions" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.resetRestrictions"></a>

```python
def reset_restrictions() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.property.restriction">restriction</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList">ScheduleRotationTimeRestrictionRestrictionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.property.restrictions">restrictions</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList">ScheduleRotationTimeRestrictionRestrictionsList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.property.restrictionInput">restriction_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestriction">ScheduleRotationTimeRestrictionRestriction</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.property.restrictionsInput">restrictions_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictions">ScheduleRotationTimeRestrictionRestrictions</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.property.typeInput">type_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.property.type">type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestriction">ScheduleRotationTimeRestriction</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `restriction`<sup>Required</sup> <a name="restriction" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.property.restriction"></a>

```python
restriction: ScheduleRotationTimeRestrictionRestrictionList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList">ScheduleRotationTimeRestrictionRestrictionList</a>

---

##### `restrictions`<sup>Required</sup> <a name="restrictions" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.property.restrictions"></a>

```python
restrictions: ScheduleRotationTimeRestrictionRestrictionsList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList">ScheduleRotationTimeRestrictionRestrictionsList</a>

---

##### `restriction_input`<sup>Optional</sup> <a name="restriction_input" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.property.restrictionInput"></a>

```python
restriction_input: typing.Union[IResolvable, typing.List[ScheduleRotationTimeRestrictionRestriction]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestriction">ScheduleRotationTimeRestrictionRestriction</a>]]

---

##### `restrictions_input`<sup>Optional</sup> <a name="restrictions_input" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.property.restrictionsInput"></a>

```python
restrictions_input: typing.Union[IResolvable, typing.List[ScheduleRotationTimeRestrictionRestrictions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictions">ScheduleRotationTimeRestrictionRestrictions</a>]]

---

##### `type_input`<sup>Optional</sup> <a name="type_input" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.property.typeInput"></a>

```python
type_input: str
```

- *Type:* str

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.property.type"></a>

```python
type: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, ScheduleRotationTimeRestriction]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestriction">ScheduleRotationTimeRestriction</a>]

---


### ScheduleRotationTimeRestrictionRestrictionList <a name="ScheduleRotationTimeRestrictionRestrictionList" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import schedule_rotation

scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> ScheduleRotationTimeRestrictionRestrictionOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestriction">ScheduleRotationTimeRestrictionRestriction</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[ScheduleRotationTimeRestrictionRestriction]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestriction">ScheduleRotationTimeRestrictionRestriction</a>]]

---


### ScheduleRotationTimeRestrictionRestrictionOutputReference <a name="ScheduleRotationTimeRestrictionRestrictionOutputReference" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import schedule_rotation

scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.endHourInput">end_hour_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.endMinInput">end_min_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.startHourInput">start_hour_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.startMinInput">start_min_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.endHour">end_hour</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.endMin">end_min</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.startHour">start_hour</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.startMin">start_min</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestriction">ScheduleRotationTimeRestrictionRestriction</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `end_hour_input`<sup>Optional</sup> <a name="end_hour_input" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.endHourInput"></a>

```python
end_hour_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `end_min_input`<sup>Optional</sup> <a name="end_min_input" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.endMinInput"></a>

```python
end_min_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `start_hour_input`<sup>Optional</sup> <a name="start_hour_input" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.startHourInput"></a>

```python
start_hour_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `start_min_input`<sup>Optional</sup> <a name="start_min_input" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.startMinInput"></a>

```python
start_min_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `end_hour`<sup>Required</sup> <a name="end_hour" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.endHour"></a>

```python
end_hour: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `end_min`<sup>Required</sup> <a name="end_min" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.endMin"></a>

```python
end_min: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `start_hour`<sup>Required</sup> <a name="start_hour" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.startHour"></a>

```python
start_hour: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `start_min`<sup>Required</sup> <a name="start_min" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.startMin"></a>

```python
start_min: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, ScheduleRotationTimeRestrictionRestriction]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestriction">ScheduleRotationTimeRestrictionRestriction</a>]

---


### ScheduleRotationTimeRestrictionRestrictionsList <a name="ScheduleRotationTimeRestrictionRestrictionsList" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import schedule_rotation

scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> ScheduleRotationTimeRestrictionRestrictionsOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictions">ScheduleRotationTimeRestrictionRestrictions</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[ScheduleRotationTimeRestrictionRestrictions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictions">ScheduleRotationTimeRestrictionRestrictions</a>]]

---


### ScheduleRotationTimeRestrictionRestrictionsOutputReference <a name="ScheduleRotationTimeRestrictionRestrictionsOutputReference" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import schedule_rotation

scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.endDayInput">end_day_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.endHourInput">end_hour_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.endMinInput">end_min_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.startDayInput">start_day_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.startHourInput">start_hour_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.startMinInput">start_min_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.endDay">end_day</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.endHour">end_hour</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.endMin">end_min</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.startDay">start_day</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.startHour">start_hour</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.startMin">start_min</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictions">ScheduleRotationTimeRestrictionRestrictions</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `end_day_input`<sup>Optional</sup> <a name="end_day_input" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.endDayInput"></a>

```python
end_day_input: str
```

- *Type:* str

---

##### `end_hour_input`<sup>Optional</sup> <a name="end_hour_input" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.endHourInput"></a>

```python
end_hour_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `end_min_input`<sup>Optional</sup> <a name="end_min_input" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.endMinInput"></a>

```python
end_min_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `start_day_input`<sup>Optional</sup> <a name="start_day_input" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.startDayInput"></a>

```python
start_day_input: str
```

- *Type:* str

---

##### `start_hour_input`<sup>Optional</sup> <a name="start_hour_input" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.startHourInput"></a>

```python
start_hour_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `start_min_input`<sup>Optional</sup> <a name="start_min_input" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.startMinInput"></a>

```python
start_min_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `end_day`<sup>Required</sup> <a name="end_day" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.endDay"></a>

```python
end_day: str
```

- *Type:* str

---

##### `end_hour`<sup>Required</sup> <a name="end_hour" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.endHour"></a>

```python
end_hour: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `end_min`<sup>Required</sup> <a name="end_min" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.endMin"></a>

```python
end_min: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `start_day`<sup>Required</sup> <a name="start_day" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.startDay"></a>

```python
start_day: str
```

- *Type:* str

---

##### `start_hour`<sup>Required</sup> <a name="start_hour" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.startHour"></a>

```python
start_hour: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `start_min`<sup>Required</sup> <a name="start_min" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.startMin"></a>

```python
start_min: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, ScheduleRotationTimeRestrictionRestrictions]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictions">ScheduleRotationTimeRestrictionRestrictions</a>]

---



