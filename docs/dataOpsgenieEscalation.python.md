# `data_opsgenie_escalation`

Refer to the Terraform Registory for docs: [`data_opsgenie_escalation`](https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation).

# `dataOpsgenieEscalation` Submodule <a name="`dataOpsgenieEscalation` Submodule" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### DataOpsgenieEscalation <a name="DataOpsgenieEscalation" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation"></a>

Represents a {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation opsgenie_escalation}.

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import data_opsgenie_escalation

dataOpsgenieEscalation.DataOpsgenieEscalation(
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
  description: str = None,
  id: str = None,
  owner_team_id: str = None,
  repeat: typing.Union[IResolvable, typing.List[DataOpsgenieEscalationRepeat]] = None,
  rules: typing.Union[IResolvable, typing.List[DataOpsgenieEscalationRules]] = None
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.id">id</a></code> | <code>str</code> | The scoped construct ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.connection">connection</a></code> | <code>typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.dependsOn">depends_on</a></code> | <code>typing.List[cdktf.ITerraformDependable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.provisioners">provisioners</a></code> | <code>typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.name">name</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#name DataOpsgenieEscalation#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.description">description</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#description DataOpsgenieEscalation#description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.id">id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#id DataOpsgenieEscalation#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.ownerTeamId">owner_team_id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#owner_team_id DataOpsgenieEscalation#owner_team_id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.repeat">repeat</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat">DataOpsgenieEscalationRepeat</a>]]</code> | repeat block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.rules">rules</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules">DataOpsgenieEscalationRules</a>]]</code> | rules block. |

---

##### `scope`<sup>Required</sup> <a name="scope" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.id"></a>

- *Type:* str

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.connection"></a>

- *Type:* typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.count"></a>

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.dependsOn"></a>

- *Type:* typing.List[cdktf.ITerraformDependable]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.forEach"></a>

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.lifecycle"></a>

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.provider"></a>

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.provisioners"></a>

- *Type:* typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.name"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#name DataOpsgenieEscalation#name}.

---

##### `description`<sup>Optional</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.description"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#description DataOpsgenieEscalation#description}.

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.id"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#id DataOpsgenieEscalation#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `owner_team_id`<sup>Optional</sup> <a name="owner_team_id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.ownerTeamId"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#owner_team_id DataOpsgenieEscalation#owner_team_id}.

---

##### `repeat`<sup>Optional</sup> <a name="repeat" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.repeat"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat">DataOpsgenieEscalationRepeat</a>]]

repeat block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#repeat DataOpsgenieEscalation#repeat}

---

##### `rules`<sup>Optional</sup> <a name="rules" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.rules"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules">DataOpsgenieEscalationRules</a>]]

rules block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#rules DataOpsgenieEscalation#rules}

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.toString">to_string</a></code> | Returns a string representation of this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.addOverride">add_override</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.overrideLogicalId">override_logical_id</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetOverrideLogicalId">reset_override_logical_id</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.toMetadata">to_metadata</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.toTerraform">to_terraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.putRepeat">put_repeat</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.putRules">put_rules</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetDescription">reset_description</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetId">reset_id</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetOwnerTeamId">reset_owner_team_id</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetRepeat">reset_repeat</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetRules">reset_rules</a></code> | *No description.* |

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.toString"></a>

```python
def to_string() -> str
```

Returns a string representation of this construct.

##### `add_override` <a name="add_override" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.addOverride"></a>

```python
def add_override(
  path: str,
  value: typing.Any
) -> None
```

###### `path`<sup>Required</sup> <a name="path" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.addOverride.parameter.path"></a>

- *Type:* str

---

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.addOverride.parameter.value"></a>

- *Type:* typing.Any

---

##### `override_logical_id` <a name="override_logical_id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.overrideLogicalId"></a>

```python
def override_logical_id(
  new_logical_id: str
) -> None
```

Overrides the auto-generated logical ID with a specific ID.

###### `new_logical_id`<sup>Required</sup> <a name="new_logical_id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* str

The new logical ID to use for this stack element.

---

##### `reset_override_logical_id` <a name="reset_override_logical_id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetOverrideLogicalId"></a>

```python
def reset_override_logical_id() -> None
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `to_metadata` <a name="to_metadata" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.toMetadata"></a>

```python
def to_metadata() -> typing.Any
```

##### `to_terraform` <a name="to_terraform" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.toTerraform"></a>

```python
def to_terraform() -> typing.Any
```

Adds this resource to the terraform JSON output.

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `put_repeat` <a name="put_repeat" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.putRepeat"></a>

```python
def put_repeat(
  value: typing.Union[IResolvable, typing.List[DataOpsgenieEscalationRepeat]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.putRepeat.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat">DataOpsgenieEscalationRepeat</a>]]

---

##### `put_rules` <a name="put_rules" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.putRules"></a>

```python
def put_rules(
  value: typing.Union[IResolvable, typing.List[DataOpsgenieEscalationRules]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.putRules.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules">DataOpsgenieEscalationRules</a>]]

---

##### `reset_description` <a name="reset_description" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetDescription"></a>

```python
def reset_description() -> None
```

##### `reset_id` <a name="reset_id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetId"></a>

```python
def reset_id() -> None
```

##### `reset_owner_team_id` <a name="reset_owner_team_id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetOwnerTeamId"></a>

```python
def reset_owner_team_id() -> None
```

##### `reset_repeat` <a name="reset_repeat" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetRepeat"></a>

```python
def reset_repeat() -> None
```

##### `reset_rules` <a name="reset_rules" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetRules"></a>

```python
def reset_rules() -> None
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.isConstruct">is_construct</a></code> | Checks if `x` is a construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.isTerraformElement">is_terraform_element</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.isTerraformDataSource">is_terraform_data_source</a></code> | *No description.* |

---

##### `is_construct` <a name="is_construct" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.isConstruct"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import data_opsgenie_escalation

dataOpsgenieEscalation.DataOpsgenieEscalation.is_construct(
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

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.isConstruct.parameter.x"></a>

- *Type:* typing.Any

Any object.

---

##### `is_terraform_element` <a name="is_terraform_element" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.isTerraformElement"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import data_opsgenie_escalation

dataOpsgenieEscalation.DataOpsgenieEscalation.is_terraform_element(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.isTerraformElement.parameter.x"></a>

- *Type:* typing.Any

---

##### `is_terraform_data_source` <a name="is_terraform_data_source" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.isTerraformDataSource"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import data_opsgenie_escalation

dataOpsgenieEscalation.DataOpsgenieEscalation.is_terraform_data_source(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.isTerraformDataSource.parameter.x"></a>

- *Type:* typing.Any

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.node">node</a></code> | <code>constructs.Node</code> | The tree node. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.cdktfStack">cdktf_stack</a></code> | <code>cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.friendlyUniqueId">friendly_unique_id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.terraformMetaArguments">terraform_meta_arguments</a></code> | <code>typing.Mapping[typing.Any]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.terraformResourceType">terraform_resource_type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.terraformGeneratorMetadata">terraform_generator_metadata</a></code> | <code>cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.dependsOn">depends_on</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.repeat">repeat</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList">DataOpsgenieEscalationRepeatList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.rules">rules</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList">DataOpsgenieEscalationRulesList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.descriptionInput">description_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.idInput">id_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.nameInput">name_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.ownerTeamIdInput">owner_team_id_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.repeatInput">repeat_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat">DataOpsgenieEscalationRepeat</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.rulesInput">rules_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules">DataOpsgenieEscalationRules</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.description">description</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.id">id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.name">name</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.ownerTeamId">owner_team_id</a></code> | <code>str</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.node"></a>

```python
node: Node
```

- *Type:* constructs.Node

The tree node.

---

##### `cdktf_stack`<sup>Required</sup> <a name="cdktf_stack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.cdktfStack"></a>

```python
cdktf_stack: TerraformStack
```

- *Type:* cdktf.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `friendly_unique_id`<sup>Required</sup> <a name="friendly_unique_id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.friendlyUniqueId"></a>

```python
friendly_unique_id: str
```

- *Type:* str

---

##### `terraform_meta_arguments`<sup>Required</sup> <a name="terraform_meta_arguments" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.terraformMetaArguments"></a>

```python
terraform_meta_arguments: typing.Mapping[typing.Any]
```

- *Type:* typing.Mapping[typing.Any]

---

##### `terraform_resource_type`<sup>Required</sup> <a name="terraform_resource_type" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.terraformResourceType"></a>

```python
terraform_resource_type: str
```

- *Type:* str

---

##### `terraform_generator_metadata`<sup>Optional</sup> <a name="terraform_generator_metadata" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.terraformGeneratorMetadata"></a>

```python
terraform_generator_metadata: TerraformProviderGeneratorMetadata
```

- *Type:* cdktf.TerraformProviderGeneratorMetadata

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.count"></a>

```python
count: typing.Union[typing.Union[int, float], TerraformCount]
```

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.dependsOn"></a>

```python
depends_on: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.forEach"></a>

```python
for_each: ITerraformIterator
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.lifecycle"></a>

```python
lifecycle: TerraformResourceLifecycle
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.provider"></a>

```python
provider: TerraformProvider
```

- *Type:* cdktf.TerraformProvider

---

##### `repeat`<sup>Required</sup> <a name="repeat" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.repeat"></a>

```python
repeat: DataOpsgenieEscalationRepeatList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList">DataOpsgenieEscalationRepeatList</a>

---

##### `rules`<sup>Required</sup> <a name="rules" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.rules"></a>

```python
rules: DataOpsgenieEscalationRulesList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList">DataOpsgenieEscalationRulesList</a>

---

##### `description_input`<sup>Optional</sup> <a name="description_input" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.descriptionInput"></a>

```python
description_input: str
```

- *Type:* str

---

##### `id_input`<sup>Optional</sup> <a name="id_input" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.idInput"></a>

```python
id_input: str
```

- *Type:* str

---

##### `name_input`<sup>Optional</sup> <a name="name_input" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.nameInput"></a>

```python
name_input: str
```

- *Type:* str

---

##### `owner_team_id_input`<sup>Optional</sup> <a name="owner_team_id_input" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.ownerTeamIdInput"></a>

```python
owner_team_id_input: str
```

- *Type:* str

---

##### `repeat_input`<sup>Optional</sup> <a name="repeat_input" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.repeatInput"></a>

```python
repeat_input: typing.Union[IResolvable, typing.List[DataOpsgenieEscalationRepeat]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat">DataOpsgenieEscalationRepeat</a>]]

---

##### `rules_input`<sup>Optional</sup> <a name="rules_input" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.rulesInput"></a>

```python
rules_input: typing.Union[IResolvable, typing.List[DataOpsgenieEscalationRules]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules">DataOpsgenieEscalationRules</a>]]

---

##### `description`<sup>Required</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.description"></a>

```python
description: str
```

- *Type:* str

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.id"></a>

```python
id: str
```

- *Type:* str

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.name"></a>

```python
name: str
```

- *Type:* str

---

##### `owner_team_id`<sup>Required</sup> <a name="owner_team_id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.ownerTeamId"></a>

```python
owner_team_id: str
```

- *Type:* str

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.tfResourceType">tfResourceType</a></code> | <code>str</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.tfResourceType"></a>

```python
tfResourceType: str
```

- *Type:* str

---

## Structs <a name="Structs" id="Structs"></a>

### DataOpsgenieEscalationConfig <a name="DataOpsgenieEscalationConfig" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import data_opsgenie_escalation

dataOpsgenieEscalation.DataOpsgenieEscalationConfig(
  connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection] = None,
  count: typing.Union[typing.Union[int, float], TerraformCount] = None,
  depends_on: typing.List[ITerraformDependable] = None,
  for_each: ITerraformIterator = None,
  lifecycle: TerraformResourceLifecycle = None,
  provider: TerraformProvider = None,
  provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]] = None,
  name: str,
  description: str = None,
  id: str = None,
  owner_team_id: str = None,
  repeat: typing.Union[IResolvable, typing.List[DataOpsgenieEscalationRepeat]] = None,
  rules: typing.Union[IResolvable, typing.List[DataOpsgenieEscalationRules]] = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.connection">connection</a></code> | <code>typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.dependsOn">depends_on</a></code> | <code>typing.List[cdktf.ITerraformDependable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.provisioners">provisioners</a></code> | <code>typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.name">name</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#name DataOpsgenieEscalation#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.description">description</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#description DataOpsgenieEscalation#description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.id">id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#id DataOpsgenieEscalation#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.ownerTeamId">owner_team_id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#owner_team_id DataOpsgenieEscalation#owner_team_id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.repeat">repeat</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat">DataOpsgenieEscalationRepeat</a>]]</code> | repeat block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.rules">rules</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules">DataOpsgenieEscalationRules</a>]]</code> | rules block. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.connection"></a>

```python
connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection]
```

- *Type:* typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.count"></a>

```python
count: typing.Union[typing.Union[int, float], TerraformCount]
```

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.dependsOn"></a>

```python
depends_on: typing.List[ITerraformDependable]
```

- *Type:* typing.List[cdktf.ITerraformDependable]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.forEach"></a>

```python
for_each: ITerraformIterator
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.lifecycle"></a>

```python
lifecycle: TerraformResourceLifecycle
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.provider"></a>

```python
provider: TerraformProvider
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.provisioners"></a>

```python
provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]]
```

- *Type:* typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.name"></a>

```python
name: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#name DataOpsgenieEscalation#name}.

---

##### `description`<sup>Optional</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.description"></a>

```python
description: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#description DataOpsgenieEscalation#description}.

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.id"></a>

```python
id: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#id DataOpsgenieEscalation#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `owner_team_id`<sup>Optional</sup> <a name="owner_team_id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.ownerTeamId"></a>

```python
owner_team_id: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#owner_team_id DataOpsgenieEscalation#owner_team_id}.

---

##### `repeat`<sup>Optional</sup> <a name="repeat" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.repeat"></a>

```python
repeat: typing.Union[IResolvable, typing.List[DataOpsgenieEscalationRepeat]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat">DataOpsgenieEscalationRepeat</a>]]

repeat block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#repeat DataOpsgenieEscalation#repeat}

---

##### `rules`<sup>Optional</sup> <a name="rules" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.rules"></a>

```python
rules: typing.Union[IResolvable, typing.List[DataOpsgenieEscalationRules]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules">DataOpsgenieEscalationRules</a>]]

rules block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#rules DataOpsgenieEscalation#rules}

---

### DataOpsgenieEscalationRepeat <a name="DataOpsgenieEscalationRepeat" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import data_opsgenie_escalation

dataOpsgenieEscalation.DataOpsgenieEscalationRepeat(
  close_alert_after_all: typing.Union[bool, IResolvable] = None,
  count: typing.Union[int, float] = None,
  reset_recipient_states: typing.Union[bool, IResolvable] = None,
  wait_interval: typing.Union[int, float] = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat.property.closeAlertAfterAll">close_alert_after_all</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#close_alert_after_all DataOpsgenieEscalation#close_alert_after_all}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat.property.count">count</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#count DataOpsgenieEscalation#count}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat.property.resetRecipientStates">reset_recipient_states</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#reset_recipient_states DataOpsgenieEscalation#reset_recipient_states}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat.property.waitInterval">wait_interval</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#wait_interval DataOpsgenieEscalation#wait_interval}. |

---

##### `close_alert_after_all`<sup>Optional</sup> <a name="close_alert_after_all" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat.property.closeAlertAfterAll"></a>

```python
close_alert_after_all: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#close_alert_after_all DataOpsgenieEscalation#close_alert_after_all}.

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat.property.count"></a>

```python
count: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#count DataOpsgenieEscalation#count}.

---

##### `reset_recipient_states`<sup>Optional</sup> <a name="reset_recipient_states" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat.property.resetRecipientStates"></a>

```python
reset_recipient_states: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#reset_recipient_states DataOpsgenieEscalation#reset_recipient_states}.

---

##### `wait_interval`<sup>Optional</sup> <a name="wait_interval" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat.property.waitInterval"></a>

```python
wait_interval: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#wait_interval DataOpsgenieEscalation#wait_interval}.

---

### DataOpsgenieEscalationRules <a name="DataOpsgenieEscalationRules" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import data_opsgenie_escalation

dataOpsgenieEscalation.DataOpsgenieEscalationRules(
  condition: str,
  delay: typing.Union[int, float],
  notify_type: str,
  recipient: typing.Union[IResolvable, typing.List[DataOpsgenieEscalationRulesRecipient]]
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules.property.condition">condition</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#condition DataOpsgenieEscalation#condition}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules.property.delay">delay</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#delay DataOpsgenieEscalation#delay}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules.property.notifyType">notify_type</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#notify_type DataOpsgenieEscalation#notify_type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules.property.recipient">recipient</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient">DataOpsgenieEscalationRulesRecipient</a>]]</code> | recipient block. |

---

##### `condition`<sup>Required</sup> <a name="condition" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules.property.condition"></a>

```python
condition: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#condition DataOpsgenieEscalation#condition}.

---

##### `delay`<sup>Required</sup> <a name="delay" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules.property.delay"></a>

```python
delay: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#delay DataOpsgenieEscalation#delay}.

---

##### `notify_type`<sup>Required</sup> <a name="notify_type" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules.property.notifyType"></a>

```python
notify_type: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#notify_type DataOpsgenieEscalation#notify_type}.

---

##### `recipient`<sup>Required</sup> <a name="recipient" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules.property.recipient"></a>

```python
recipient: typing.Union[IResolvable, typing.List[DataOpsgenieEscalationRulesRecipient]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient">DataOpsgenieEscalationRulesRecipient</a>]]

recipient block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#recipient DataOpsgenieEscalation#recipient}

---

### DataOpsgenieEscalationRulesRecipient <a name="DataOpsgenieEscalationRulesRecipient" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import data_opsgenie_escalation

dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient(
  id: str = None,
  type: str = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient.property.id">id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#id DataOpsgenieEscalation#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient.property.type">type</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#type DataOpsgenieEscalation#type}. |

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient.property.id"></a>

```python
id: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#id DataOpsgenieEscalation#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `type`<sup>Optional</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient.property.type"></a>

```python
type: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#type DataOpsgenieEscalation#type}.

---

## Classes <a name="Classes" id="Classes"></a>

### DataOpsgenieEscalationRepeatList <a name="DataOpsgenieEscalationRepeatList" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import data_opsgenie_escalation

dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> DataOpsgenieEscalationRepeatOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat">DataOpsgenieEscalationRepeat</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[DataOpsgenieEscalationRepeat]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat">DataOpsgenieEscalationRepeat</a>]]

---


### DataOpsgenieEscalationRepeatOutputReference <a name="DataOpsgenieEscalationRepeatOutputReference" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import data_opsgenie_escalation

dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resetCloseAlertAfterAll">reset_close_alert_after_all</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resetCount">reset_count</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resetResetRecipientStates">reset_reset_recipient_states</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resetWaitInterval">reset_wait_interval</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `reset_close_alert_after_all` <a name="reset_close_alert_after_all" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resetCloseAlertAfterAll"></a>

```python
def reset_close_alert_after_all() -> None
```

##### `reset_count` <a name="reset_count" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resetCount"></a>

```python
def reset_count() -> None
```

##### `reset_reset_recipient_states` <a name="reset_reset_recipient_states" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resetResetRecipientStates"></a>

```python
def reset_reset_recipient_states() -> None
```

##### `reset_wait_interval` <a name="reset_wait_interval" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resetWaitInterval"></a>

```python
def reset_wait_interval() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.closeAlertAfterAllInput">close_alert_after_all_input</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.countInput">count_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.resetRecipientStatesInput">reset_recipient_states_input</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.waitIntervalInput">wait_interval_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.closeAlertAfterAll">close_alert_after_all</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.count">count</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.resetRecipientStates">reset_recipient_states</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.waitInterval">wait_interval</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat">DataOpsgenieEscalationRepeat</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `close_alert_after_all_input`<sup>Optional</sup> <a name="close_alert_after_all_input" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.closeAlertAfterAllInput"></a>

```python
close_alert_after_all_input: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `count_input`<sup>Optional</sup> <a name="count_input" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.countInput"></a>

```python
count_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `reset_recipient_states_input`<sup>Optional</sup> <a name="reset_recipient_states_input" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.resetRecipientStatesInput"></a>

```python
reset_recipient_states_input: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `wait_interval_input`<sup>Optional</sup> <a name="wait_interval_input" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.waitIntervalInput"></a>

```python
wait_interval_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `close_alert_after_all`<sup>Required</sup> <a name="close_alert_after_all" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.closeAlertAfterAll"></a>

```python
close_alert_after_all: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `count`<sup>Required</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.count"></a>

```python
count: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `reset_recipient_states`<sup>Required</sup> <a name="reset_recipient_states" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.resetRecipientStates"></a>

```python
reset_recipient_states: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `wait_interval`<sup>Required</sup> <a name="wait_interval" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.waitInterval"></a>

```python
wait_interval: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, DataOpsgenieEscalationRepeat]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat">DataOpsgenieEscalationRepeat</a>]

---


### DataOpsgenieEscalationRulesList <a name="DataOpsgenieEscalationRulesList" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import data_opsgenie_escalation

dataOpsgenieEscalation.DataOpsgenieEscalationRulesList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> DataOpsgenieEscalationRulesOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules">DataOpsgenieEscalationRules</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[DataOpsgenieEscalationRules]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules">DataOpsgenieEscalationRules</a>]]

---


### DataOpsgenieEscalationRulesOutputReference <a name="DataOpsgenieEscalationRulesOutputReference" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import data_opsgenie_escalation

dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.putRecipient">put_recipient</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `put_recipient` <a name="put_recipient" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.putRecipient"></a>

```python
def put_recipient(
  value: typing.Union[IResolvable, typing.List[DataOpsgenieEscalationRulesRecipient]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.putRecipient.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient">DataOpsgenieEscalationRulesRecipient</a>]]

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.recipient">recipient</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList">DataOpsgenieEscalationRulesRecipientList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.conditionInput">condition_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.delayInput">delay_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.notifyTypeInput">notify_type_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.recipientInput">recipient_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient">DataOpsgenieEscalationRulesRecipient</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.condition">condition</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.delay">delay</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.notifyType">notify_type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules">DataOpsgenieEscalationRules</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `recipient`<sup>Required</sup> <a name="recipient" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.recipient"></a>

```python
recipient: DataOpsgenieEscalationRulesRecipientList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList">DataOpsgenieEscalationRulesRecipientList</a>

---

##### `condition_input`<sup>Optional</sup> <a name="condition_input" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.conditionInput"></a>

```python
condition_input: str
```

- *Type:* str

---

##### `delay_input`<sup>Optional</sup> <a name="delay_input" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.delayInput"></a>

```python
delay_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `notify_type_input`<sup>Optional</sup> <a name="notify_type_input" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.notifyTypeInput"></a>

```python
notify_type_input: str
```

- *Type:* str

---

##### `recipient_input`<sup>Optional</sup> <a name="recipient_input" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.recipientInput"></a>

```python
recipient_input: typing.Union[IResolvable, typing.List[DataOpsgenieEscalationRulesRecipient]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient">DataOpsgenieEscalationRulesRecipient</a>]]

---

##### `condition`<sup>Required</sup> <a name="condition" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.condition"></a>

```python
condition: str
```

- *Type:* str

---

##### `delay`<sup>Required</sup> <a name="delay" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.delay"></a>

```python
delay: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `notify_type`<sup>Required</sup> <a name="notify_type" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.notifyType"></a>

```python
notify_type: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, DataOpsgenieEscalationRules]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules">DataOpsgenieEscalationRules</a>]

---


### DataOpsgenieEscalationRulesRecipientList <a name="DataOpsgenieEscalationRulesRecipientList" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import data_opsgenie_escalation

dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> DataOpsgenieEscalationRulesRecipientOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient">DataOpsgenieEscalationRulesRecipient</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[DataOpsgenieEscalationRulesRecipient]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient">DataOpsgenieEscalationRulesRecipient</a>]]

---


### DataOpsgenieEscalationRulesRecipientOutputReference <a name="DataOpsgenieEscalationRulesRecipientOutputReference" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import data_opsgenie_escalation

dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.resetId">reset_id</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.resetType">reset_type</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `reset_id` <a name="reset_id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.resetId"></a>

```python
def reset_id() -> None
```

##### `reset_type` <a name="reset_type" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.resetType"></a>

```python
def reset_type() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.idInput">id_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.typeInput">type_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.id">id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.type">type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient">DataOpsgenieEscalationRulesRecipient</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `id_input`<sup>Optional</sup> <a name="id_input" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.idInput"></a>

```python
id_input: str
```

- *Type:* str

---

##### `type_input`<sup>Optional</sup> <a name="type_input" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.typeInput"></a>

```python
type_input: str
```

- *Type:* str

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.id"></a>

```python
id: str
```

- *Type:* str

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.type"></a>

```python
type: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, DataOpsgenieEscalationRulesRecipient]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient">DataOpsgenieEscalationRulesRecipient</a>]

---



