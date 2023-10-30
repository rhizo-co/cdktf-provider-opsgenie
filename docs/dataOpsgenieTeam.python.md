# `data_opsgenie_team`

Refer to the Terraform Registory for docs: [`data_opsgenie_team`](https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/team).

# `dataOpsgenieTeam` Submodule <a name="`dataOpsgenieTeam` Submodule" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### DataOpsgenieTeam <a name="DataOpsgenieTeam" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam"></a>

Represents a {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/team opsgenie_team}.

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import data_opsgenie_team

dataOpsgenieTeam.DataOpsgenieTeam(
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
  member: typing.Union[IResolvable, typing.List[DataOpsgenieTeamMember]] = None
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.Initializer.parameter.id">id</a></code> | <code>str</code> | The scoped construct ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.Initializer.parameter.connection">connection</a></code> | <code>typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.Initializer.parameter.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.Initializer.parameter.dependsOn">depends_on</a></code> | <code>typing.List[cdktf.ITerraformDependable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.Initializer.parameter.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.Initializer.parameter.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.Initializer.parameter.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.Initializer.parameter.provisioners">provisioners</a></code> | <code>typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.Initializer.parameter.name">name</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/team#name DataOpsgenieTeam#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.Initializer.parameter.description">description</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/team#description DataOpsgenieTeam#description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.Initializer.parameter.id">id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/team#id DataOpsgenieTeam#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.Initializer.parameter.member">member</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMember">DataOpsgenieTeamMember</a>]]</code> | member block. |

---

##### `scope`<sup>Required</sup> <a name="scope" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.Initializer.parameter.id"></a>

- *Type:* str

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.Initializer.parameter.connection"></a>

- *Type:* typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.Initializer.parameter.count"></a>

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.Initializer.parameter.dependsOn"></a>

- *Type:* typing.List[cdktf.ITerraformDependable]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.Initializer.parameter.forEach"></a>

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.Initializer.parameter.lifecycle"></a>

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.Initializer.parameter.provider"></a>

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.Initializer.parameter.provisioners"></a>

- *Type:* typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.Initializer.parameter.name"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/team#name DataOpsgenieTeam#name}.

---

##### `description`<sup>Optional</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.Initializer.parameter.description"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/team#description DataOpsgenieTeam#description}.

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.Initializer.parameter.id"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/team#id DataOpsgenieTeam#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `member`<sup>Optional</sup> <a name="member" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.Initializer.parameter.member"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMember">DataOpsgenieTeamMember</a>]]

member block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/team#member DataOpsgenieTeam#member}

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.toString">to_string</a></code> | Returns a string representation of this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.addOverride">add_override</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.overrideLogicalId">override_logical_id</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.resetOverrideLogicalId">reset_override_logical_id</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.toMetadata">to_metadata</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.toTerraform">to_terraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.putMember">put_member</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.resetDescription">reset_description</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.resetId">reset_id</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.resetMember">reset_member</a></code> | *No description.* |

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.toString"></a>

```python
def to_string() -> str
```

Returns a string representation of this construct.

##### `add_override` <a name="add_override" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.addOverride"></a>

```python
def add_override(
  path: str,
  value: typing.Any
) -> None
```

###### `path`<sup>Required</sup> <a name="path" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.addOverride.parameter.path"></a>

- *Type:* str

---

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.addOverride.parameter.value"></a>

- *Type:* typing.Any

---

##### `override_logical_id` <a name="override_logical_id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.overrideLogicalId"></a>

```python
def override_logical_id(
  new_logical_id: str
) -> None
```

Overrides the auto-generated logical ID with a specific ID.

###### `new_logical_id`<sup>Required</sup> <a name="new_logical_id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* str

The new logical ID to use for this stack element.

---

##### `reset_override_logical_id` <a name="reset_override_logical_id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.resetOverrideLogicalId"></a>

```python
def reset_override_logical_id() -> None
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `to_metadata` <a name="to_metadata" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.toMetadata"></a>

```python
def to_metadata() -> typing.Any
```

##### `to_terraform` <a name="to_terraform" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.toTerraform"></a>

```python
def to_terraform() -> typing.Any
```

Adds this resource to the terraform JSON output.

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `put_member` <a name="put_member" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.putMember"></a>

```python
def put_member(
  value: typing.Union[IResolvable, typing.List[DataOpsgenieTeamMember]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.putMember.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMember">DataOpsgenieTeamMember</a>]]

---

##### `reset_description` <a name="reset_description" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.resetDescription"></a>

```python
def reset_description() -> None
```

##### `reset_id` <a name="reset_id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.resetId"></a>

```python
def reset_id() -> None
```

##### `reset_member` <a name="reset_member" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.resetMember"></a>

```python
def reset_member() -> None
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.isConstruct">is_construct</a></code> | Checks if `x` is a construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.isTerraformElement">is_terraform_element</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.isTerraformDataSource">is_terraform_data_source</a></code> | *No description.* |

---

##### `is_construct` <a name="is_construct" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.isConstruct"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import data_opsgenie_team

dataOpsgenieTeam.DataOpsgenieTeam.is_construct(
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

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.isConstruct.parameter.x"></a>

- *Type:* typing.Any

Any object.

---

##### `is_terraform_element` <a name="is_terraform_element" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.isTerraformElement"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import data_opsgenie_team

dataOpsgenieTeam.DataOpsgenieTeam.is_terraform_element(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.isTerraformElement.parameter.x"></a>

- *Type:* typing.Any

---

##### `is_terraform_data_source` <a name="is_terraform_data_source" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.isTerraformDataSource"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import data_opsgenie_team

dataOpsgenieTeam.DataOpsgenieTeam.is_terraform_data_source(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.isTerraformDataSource.parameter.x"></a>

- *Type:* typing.Any

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.node">node</a></code> | <code>constructs.Node</code> | The tree node. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.cdktfStack">cdktf_stack</a></code> | <code>cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.friendlyUniqueId">friendly_unique_id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.terraformMetaArguments">terraform_meta_arguments</a></code> | <code>typing.Mapping[typing.Any]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.terraformResourceType">terraform_resource_type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.terraformGeneratorMetadata">terraform_generator_metadata</a></code> | <code>cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.dependsOn">depends_on</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.member">member</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList">DataOpsgenieTeamMemberList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.descriptionInput">description_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.idInput">id_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.memberInput">member_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMember">DataOpsgenieTeamMember</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.nameInput">name_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.description">description</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.id">id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.name">name</a></code> | <code>str</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.node"></a>

```python
node: Node
```

- *Type:* constructs.Node

The tree node.

---

##### `cdktf_stack`<sup>Required</sup> <a name="cdktf_stack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.cdktfStack"></a>

```python
cdktf_stack: TerraformStack
```

- *Type:* cdktf.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `friendly_unique_id`<sup>Required</sup> <a name="friendly_unique_id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.friendlyUniqueId"></a>

```python
friendly_unique_id: str
```

- *Type:* str

---

##### `terraform_meta_arguments`<sup>Required</sup> <a name="terraform_meta_arguments" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.terraformMetaArguments"></a>

```python
terraform_meta_arguments: typing.Mapping[typing.Any]
```

- *Type:* typing.Mapping[typing.Any]

---

##### `terraform_resource_type`<sup>Required</sup> <a name="terraform_resource_type" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.terraformResourceType"></a>

```python
terraform_resource_type: str
```

- *Type:* str

---

##### `terraform_generator_metadata`<sup>Optional</sup> <a name="terraform_generator_metadata" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.terraformGeneratorMetadata"></a>

```python
terraform_generator_metadata: TerraformProviderGeneratorMetadata
```

- *Type:* cdktf.TerraformProviderGeneratorMetadata

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.count"></a>

```python
count: typing.Union[typing.Union[int, float], TerraformCount]
```

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.dependsOn"></a>

```python
depends_on: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.forEach"></a>

```python
for_each: ITerraformIterator
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.lifecycle"></a>

```python
lifecycle: TerraformResourceLifecycle
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.provider"></a>

```python
provider: TerraformProvider
```

- *Type:* cdktf.TerraformProvider

---

##### `member`<sup>Required</sup> <a name="member" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.member"></a>

```python
member: DataOpsgenieTeamMemberList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList">DataOpsgenieTeamMemberList</a>

---

##### `description_input`<sup>Optional</sup> <a name="description_input" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.descriptionInput"></a>

```python
description_input: str
```

- *Type:* str

---

##### `id_input`<sup>Optional</sup> <a name="id_input" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.idInput"></a>

```python
id_input: str
```

- *Type:* str

---

##### `member_input`<sup>Optional</sup> <a name="member_input" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.memberInput"></a>

```python
member_input: typing.Union[IResolvable, typing.List[DataOpsgenieTeamMember]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMember">DataOpsgenieTeamMember</a>]]

---

##### `name_input`<sup>Optional</sup> <a name="name_input" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.nameInput"></a>

```python
name_input: str
```

- *Type:* str

---

##### `description`<sup>Required</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.description"></a>

```python
description: str
```

- *Type:* str

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.id"></a>

```python
id: str
```

- *Type:* str

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.name"></a>

```python
name: str
```

- *Type:* str

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.tfResourceType">tfResourceType</a></code> | <code>str</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.tfResourceType"></a>

```python
tfResourceType: str
```

- *Type:* str

---

## Structs <a name="Structs" id="Structs"></a>

### DataOpsgenieTeamConfig <a name="DataOpsgenieTeamConfig" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import data_opsgenie_team

dataOpsgenieTeam.DataOpsgenieTeamConfig(
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
  member: typing.Union[IResolvable, typing.List[DataOpsgenieTeamMember]] = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.connection">connection</a></code> | <code>typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.dependsOn">depends_on</a></code> | <code>typing.List[cdktf.ITerraformDependable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.provisioners">provisioners</a></code> | <code>typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.name">name</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/team#name DataOpsgenieTeam#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.description">description</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/team#description DataOpsgenieTeam#description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.id">id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/team#id DataOpsgenieTeam#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.member">member</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMember">DataOpsgenieTeamMember</a>]]</code> | member block. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.connection"></a>

```python
connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection]
```

- *Type:* typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.count"></a>

```python
count: typing.Union[typing.Union[int, float], TerraformCount]
```

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.dependsOn"></a>

```python
depends_on: typing.List[ITerraformDependable]
```

- *Type:* typing.List[cdktf.ITerraformDependable]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.forEach"></a>

```python
for_each: ITerraformIterator
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.lifecycle"></a>

```python
lifecycle: TerraformResourceLifecycle
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.provider"></a>

```python
provider: TerraformProvider
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.provisioners"></a>

```python
provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]]
```

- *Type:* typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.name"></a>

```python
name: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/team#name DataOpsgenieTeam#name}.

---

##### `description`<sup>Optional</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.description"></a>

```python
description: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/team#description DataOpsgenieTeam#description}.

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.id"></a>

```python
id: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/team#id DataOpsgenieTeam#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `member`<sup>Optional</sup> <a name="member" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.member"></a>

```python
member: typing.Union[IResolvable, typing.List[DataOpsgenieTeamMember]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMember">DataOpsgenieTeamMember</a>]]

member block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/team#member DataOpsgenieTeam#member}

---

### DataOpsgenieTeamMember <a name="DataOpsgenieTeamMember" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMember"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMember.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import data_opsgenie_team

dataOpsgenieTeam.DataOpsgenieTeamMember(
  id: str = None,
  role: str = None,
  username: str = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMember.property.id">id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/team#id DataOpsgenieTeam#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMember.property.role">role</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/team#role DataOpsgenieTeam#role}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMember.property.username">username</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/team#username DataOpsgenieTeam#username}. |

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMember.property.id"></a>

```python
id: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/team#id DataOpsgenieTeam#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `role`<sup>Optional</sup> <a name="role" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMember.property.role"></a>

```python
role: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/team#role DataOpsgenieTeam#role}.

---

##### `username`<sup>Optional</sup> <a name="username" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMember.property.username"></a>

```python
username: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/team#username DataOpsgenieTeam#username}.

---

## Classes <a name="Classes" id="Classes"></a>

### DataOpsgenieTeamMemberList <a name="DataOpsgenieTeamMemberList" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import data_opsgenie_team

dataOpsgenieTeam.DataOpsgenieTeamMemberList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> DataOpsgenieTeamMemberOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMember">DataOpsgenieTeamMember</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[DataOpsgenieTeamMember]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMember">DataOpsgenieTeamMember</a>]]

---


### DataOpsgenieTeamMemberOutputReference <a name="DataOpsgenieTeamMemberOutputReference" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import data_opsgenie_team

dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.resetId">reset_id</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.resetRole">reset_role</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.resetUsername">reset_username</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `reset_id` <a name="reset_id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.resetId"></a>

```python
def reset_id() -> None
```

##### `reset_role` <a name="reset_role" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.resetRole"></a>

```python
def reset_role() -> None
```

##### `reset_username` <a name="reset_username" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.resetUsername"></a>

```python
def reset_username() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.property.idInput">id_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.property.roleInput">role_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.property.usernameInput">username_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.property.id">id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.property.role">role</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.property.username">username</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMember">DataOpsgenieTeamMember</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `id_input`<sup>Optional</sup> <a name="id_input" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.property.idInput"></a>

```python
id_input: str
```

- *Type:* str

---

##### `role_input`<sup>Optional</sup> <a name="role_input" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.property.roleInput"></a>

```python
role_input: str
```

- *Type:* str

---

##### `username_input`<sup>Optional</sup> <a name="username_input" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.property.usernameInput"></a>

```python
username_input: str
```

- *Type:* str

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.property.id"></a>

```python
id: str
```

- *Type:* str

---

##### `role`<sup>Required</sup> <a name="role" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.property.role"></a>

```python
role: str
```

- *Type:* str

---

##### `username`<sup>Required</sup> <a name="username" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.property.username"></a>

```python
username: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, DataOpsgenieTeamMember]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMember">DataOpsgenieTeamMember</a>]

---



