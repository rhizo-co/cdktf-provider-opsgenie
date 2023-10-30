# `opsgenie_integration_action`

Refer to the Terraform Registory for docs: [`opsgenie_integration_action`](https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action).

# `integrationAction` Submodule <a name="`integrationAction` Submodule" id="rhizo-co-terraform-provider-opsgenie.integrationAction"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### IntegrationAction <a name="IntegrationAction" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction"></a>

Represents a {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action opsgenie_integration_action}.

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationAction(
  scope: Construct,
  id: str,
  connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection] = None,
  count: typing.Union[typing.Union[int, float], TerraformCount] = None,
  depends_on: typing.List[ITerraformDependable] = None,
  for_each: ITerraformIterator = None,
  lifecycle: TerraformResourceLifecycle = None,
  provider: TerraformProvider = None,
  provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]] = None,
  integration_id: str,
  acknowledge: typing.Union[IResolvable, typing.List[IntegrationActionAcknowledge]] = None,
  add_note: typing.Union[IResolvable, typing.List[IntegrationActionAddNote]] = None,
  close: typing.Union[IResolvable, typing.List[IntegrationActionClose]] = None,
  create: typing.Union[IResolvable, typing.List[IntegrationActionCreate]] = None,
  id: str = None,
  ignore: typing.Union[IResolvable, typing.List[IntegrationActionIgnore]] = None
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.Initializer.parameter.id">id</a></code> | <code>str</code> | The scoped construct ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.Initializer.parameter.connection">connection</a></code> | <code>typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.Initializer.parameter.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.Initializer.parameter.dependsOn">depends_on</a></code> | <code>typing.List[cdktf.ITerraformDependable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.Initializer.parameter.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.Initializer.parameter.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.Initializer.parameter.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.Initializer.parameter.provisioners">provisioners</a></code> | <code>typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.Initializer.parameter.integrationId">integration_id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#integration_id IntegrationAction#integration_id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.Initializer.parameter.acknowledge">acknowledge</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledge">IntegrationActionAcknowledge</a>]]</code> | acknowledge block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.Initializer.parameter.addNote">add_note</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNote">IntegrationActionAddNote</a>]]</code> | add_note block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.Initializer.parameter.close">close</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionClose">IntegrationActionClose</a>]]</code> | close block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.Initializer.parameter.create">create</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate">IntegrationActionCreate</a>]]</code> | create block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.Initializer.parameter.id">id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#id IntegrationAction#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.Initializer.parameter.ignore">ignore</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnore">IntegrationActionIgnore</a>]]</code> | ignore block. |

---

##### `scope`<sup>Required</sup> <a name="scope" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.Initializer.parameter.id"></a>

- *Type:* str

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.Initializer.parameter.connection"></a>

- *Type:* typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.Initializer.parameter.count"></a>

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.Initializer.parameter.dependsOn"></a>

- *Type:* typing.List[cdktf.ITerraformDependable]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.Initializer.parameter.forEach"></a>

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.Initializer.parameter.lifecycle"></a>

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.Initializer.parameter.provider"></a>

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.Initializer.parameter.provisioners"></a>

- *Type:* typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]

---

##### `integration_id`<sup>Required</sup> <a name="integration_id" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.Initializer.parameter.integrationId"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#integration_id IntegrationAction#integration_id}.

---

##### `acknowledge`<sup>Optional</sup> <a name="acknowledge" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.Initializer.parameter.acknowledge"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledge">IntegrationActionAcknowledge</a>]]

acknowledge block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#acknowledge IntegrationAction#acknowledge}

---

##### `add_note`<sup>Optional</sup> <a name="add_note" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.Initializer.parameter.addNote"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNote">IntegrationActionAddNote</a>]]

add_note block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#add_note IntegrationAction#add_note}

---

##### `close`<sup>Optional</sup> <a name="close" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.Initializer.parameter.close"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionClose">IntegrationActionClose</a>]]

close block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#close IntegrationAction#close}

---

##### `create`<sup>Optional</sup> <a name="create" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.Initializer.parameter.create"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate">IntegrationActionCreate</a>]]

create block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#create IntegrationAction#create}

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.Initializer.parameter.id"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#id IntegrationAction#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `ignore`<sup>Optional</sup> <a name="ignore" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.Initializer.parameter.ignore"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnore">IntegrationActionIgnore</a>]]

ignore block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#ignore IntegrationAction#ignore}

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.toString">to_string</a></code> | Returns a string representation of this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.addOverride">add_override</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.overrideLogicalId">override_logical_id</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.resetOverrideLogicalId">reset_override_logical_id</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.toMetadata">to_metadata</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.toTerraform">to_terraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.putAcknowledge">put_acknowledge</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.putAddNote">put_add_note</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.putClose">put_close</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.putCreate">put_create</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.putIgnore">put_ignore</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.resetAcknowledge">reset_acknowledge</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.resetAddNote">reset_add_note</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.resetClose">reset_close</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.resetCreate">reset_create</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.resetId">reset_id</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.resetIgnore">reset_ignore</a></code> | *No description.* |

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.toString"></a>

```python
def to_string() -> str
```

Returns a string representation of this construct.

##### `add_override` <a name="add_override" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.addOverride"></a>

```python
def add_override(
  path: str,
  value: typing.Any
) -> None
```

###### `path`<sup>Required</sup> <a name="path" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.addOverride.parameter.path"></a>

- *Type:* str

---

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.addOverride.parameter.value"></a>

- *Type:* typing.Any

---

##### `override_logical_id` <a name="override_logical_id" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.overrideLogicalId"></a>

```python
def override_logical_id(
  new_logical_id: str
) -> None
```

Overrides the auto-generated logical ID with a specific ID.

###### `new_logical_id`<sup>Required</sup> <a name="new_logical_id" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* str

The new logical ID to use for this stack element.

---

##### `reset_override_logical_id` <a name="reset_override_logical_id" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.resetOverrideLogicalId"></a>

```python
def reset_override_logical_id() -> None
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `to_metadata` <a name="to_metadata" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.toMetadata"></a>

```python
def to_metadata() -> typing.Any
```

##### `to_terraform` <a name="to_terraform" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.toTerraform"></a>

```python
def to_terraform() -> typing.Any
```

Adds this resource to the terraform JSON output.

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `put_acknowledge` <a name="put_acknowledge" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.putAcknowledge"></a>

```python
def put_acknowledge(
  value: typing.Union[IResolvable, typing.List[IntegrationActionAcknowledge]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.putAcknowledge.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledge">IntegrationActionAcknowledge</a>]]

---

##### `put_add_note` <a name="put_add_note" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.putAddNote"></a>

```python
def put_add_note(
  value: typing.Union[IResolvable, typing.List[IntegrationActionAddNote]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.putAddNote.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNote">IntegrationActionAddNote</a>]]

---

##### `put_close` <a name="put_close" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.putClose"></a>

```python
def put_close(
  value: typing.Union[IResolvable, typing.List[IntegrationActionClose]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.putClose.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionClose">IntegrationActionClose</a>]]

---

##### `put_create` <a name="put_create" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.putCreate"></a>

```python
def put_create(
  value: typing.Union[IResolvable, typing.List[IntegrationActionCreate]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.putCreate.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate">IntegrationActionCreate</a>]]

---

##### `put_ignore` <a name="put_ignore" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.putIgnore"></a>

```python
def put_ignore(
  value: typing.Union[IResolvable, typing.List[IntegrationActionIgnore]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.putIgnore.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnore">IntegrationActionIgnore</a>]]

---

##### `reset_acknowledge` <a name="reset_acknowledge" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.resetAcknowledge"></a>

```python
def reset_acknowledge() -> None
```

##### `reset_add_note` <a name="reset_add_note" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.resetAddNote"></a>

```python
def reset_add_note() -> None
```

##### `reset_close` <a name="reset_close" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.resetClose"></a>

```python
def reset_close() -> None
```

##### `reset_create` <a name="reset_create" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.resetCreate"></a>

```python
def reset_create() -> None
```

##### `reset_id` <a name="reset_id" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.resetId"></a>

```python
def reset_id() -> None
```

##### `reset_ignore` <a name="reset_ignore" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.resetIgnore"></a>

```python
def reset_ignore() -> None
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.isConstruct">is_construct</a></code> | Checks if `x` is a construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.isTerraformElement">is_terraform_element</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.isTerraformResource">is_terraform_resource</a></code> | *No description.* |

---

##### `is_construct` <a name="is_construct" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.isConstruct"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationAction.is_construct(
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

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.isConstruct.parameter.x"></a>

- *Type:* typing.Any

Any object.

---

##### `is_terraform_element` <a name="is_terraform_element" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.isTerraformElement"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationAction.is_terraform_element(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.isTerraformElement.parameter.x"></a>

- *Type:* typing.Any

---

##### `is_terraform_resource` <a name="is_terraform_resource" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.isTerraformResource"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationAction.is_terraform_resource(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.isTerraformResource.parameter.x"></a>

- *Type:* typing.Any

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.node">node</a></code> | <code>constructs.Node</code> | The tree node. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.cdktfStack">cdktf_stack</a></code> | <code>cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.friendlyUniqueId">friendly_unique_id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.terraformMetaArguments">terraform_meta_arguments</a></code> | <code>typing.Mapping[typing.Any]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.terraformResourceType">terraform_resource_type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.terraformGeneratorMetadata">terraform_generator_metadata</a></code> | <code>cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.connection">connection</a></code> | <code>typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.dependsOn">depends_on</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.provisioners">provisioners</a></code> | <code>typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.acknowledge">acknowledge</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeList">IntegrationActionAcknowledgeList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.addNote">add_note</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteList">IntegrationActionAddNoteList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.close">close</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseList">IntegrationActionCloseList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.create">create</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateList">IntegrationActionCreateList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.ignore">ignore</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreList">IntegrationActionIgnoreList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.acknowledgeInput">acknowledge_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledge">IntegrationActionAcknowledge</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.addNoteInput">add_note_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNote">IntegrationActionAddNote</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.closeInput">close_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionClose">IntegrationActionClose</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.createInput">create_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate">IntegrationActionCreate</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.idInput">id_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.ignoreInput">ignore_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnore">IntegrationActionIgnore</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.integrationIdInput">integration_id_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.id">id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.integrationId">integration_id</a></code> | <code>str</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.node"></a>

```python
node: Node
```

- *Type:* constructs.Node

The tree node.

---

##### `cdktf_stack`<sup>Required</sup> <a name="cdktf_stack" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.cdktfStack"></a>

```python
cdktf_stack: TerraformStack
```

- *Type:* cdktf.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `friendly_unique_id`<sup>Required</sup> <a name="friendly_unique_id" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.friendlyUniqueId"></a>

```python
friendly_unique_id: str
```

- *Type:* str

---

##### `terraform_meta_arguments`<sup>Required</sup> <a name="terraform_meta_arguments" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.terraformMetaArguments"></a>

```python
terraform_meta_arguments: typing.Mapping[typing.Any]
```

- *Type:* typing.Mapping[typing.Any]

---

##### `terraform_resource_type`<sup>Required</sup> <a name="terraform_resource_type" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.terraformResourceType"></a>

```python
terraform_resource_type: str
```

- *Type:* str

---

##### `terraform_generator_metadata`<sup>Optional</sup> <a name="terraform_generator_metadata" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.terraformGeneratorMetadata"></a>

```python
terraform_generator_metadata: TerraformProviderGeneratorMetadata
```

- *Type:* cdktf.TerraformProviderGeneratorMetadata

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.connection"></a>

```python
connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection]
```

- *Type:* typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.count"></a>

```python
count: typing.Union[typing.Union[int, float], TerraformCount]
```

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.dependsOn"></a>

```python
depends_on: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.forEach"></a>

```python
for_each: ITerraformIterator
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.lifecycle"></a>

```python
lifecycle: TerraformResourceLifecycle
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.provider"></a>

```python
provider: TerraformProvider
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.provisioners"></a>

```python
provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]]
```

- *Type:* typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]

---

##### `acknowledge`<sup>Required</sup> <a name="acknowledge" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.acknowledge"></a>

```python
acknowledge: IntegrationActionAcknowledgeList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeList">IntegrationActionAcknowledgeList</a>

---

##### `add_note`<sup>Required</sup> <a name="add_note" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.addNote"></a>

```python
add_note: IntegrationActionAddNoteList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteList">IntegrationActionAddNoteList</a>

---

##### `close`<sup>Required</sup> <a name="close" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.close"></a>

```python
close: IntegrationActionCloseList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseList">IntegrationActionCloseList</a>

---

##### `create`<sup>Required</sup> <a name="create" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.create"></a>

```python
create: IntegrationActionCreateList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateList">IntegrationActionCreateList</a>

---

##### `ignore`<sup>Required</sup> <a name="ignore" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.ignore"></a>

```python
ignore: IntegrationActionIgnoreList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreList">IntegrationActionIgnoreList</a>

---

##### `acknowledge_input`<sup>Optional</sup> <a name="acknowledge_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.acknowledgeInput"></a>

```python
acknowledge_input: typing.Union[IResolvable, typing.List[IntegrationActionAcknowledge]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledge">IntegrationActionAcknowledge</a>]]

---

##### `add_note_input`<sup>Optional</sup> <a name="add_note_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.addNoteInput"></a>

```python
add_note_input: typing.Union[IResolvable, typing.List[IntegrationActionAddNote]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNote">IntegrationActionAddNote</a>]]

---

##### `close_input`<sup>Optional</sup> <a name="close_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.closeInput"></a>

```python
close_input: typing.Union[IResolvable, typing.List[IntegrationActionClose]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionClose">IntegrationActionClose</a>]]

---

##### `create_input`<sup>Optional</sup> <a name="create_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.createInput"></a>

```python
create_input: typing.Union[IResolvable, typing.List[IntegrationActionCreate]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate">IntegrationActionCreate</a>]]

---

##### `id_input`<sup>Optional</sup> <a name="id_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.idInput"></a>

```python
id_input: str
```

- *Type:* str

---

##### `ignore_input`<sup>Optional</sup> <a name="ignore_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.ignoreInput"></a>

```python
ignore_input: typing.Union[IResolvable, typing.List[IntegrationActionIgnore]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnore">IntegrationActionIgnore</a>]]

---

##### `integration_id_input`<sup>Optional</sup> <a name="integration_id_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.integrationIdInput"></a>

```python
integration_id_input: str
```

- *Type:* str

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.id"></a>

```python
id: str
```

- *Type:* str

---

##### `integration_id`<sup>Required</sup> <a name="integration_id" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.integrationId"></a>

```python
integration_id: str
```

- *Type:* str

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.tfResourceType">tfResourceType</a></code> | <code>str</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationAction.property.tfResourceType"></a>

```python
tfResourceType: str
```

- *Type:* str

---

## Structs <a name="Structs" id="Structs"></a>

### IntegrationActionAcknowledge <a name="IntegrationActionAcknowledge" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledge"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledge.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionAcknowledge(
  name: str,
  alias: str = None,
  filter: typing.Union[IResolvable, typing.List[IntegrationActionAcknowledgeFilter]] = None,
  note: str = None,
  order: typing.Union[int, float] = None,
  type: str = None,
  user: str = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledge.property.name">name</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#name IntegrationAction#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledge.property.alias">alias</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#alias IntegrationAction#alias}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledge.property.filter">filter</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilter">IntegrationActionAcknowledgeFilter</a>]]</code> | filter block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledge.property.note">note</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#note IntegrationAction#note}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledge.property.order">order</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#order IntegrationAction#order}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledge.property.type">type</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#type IntegrationAction#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledge.property.user">user</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#user IntegrationAction#user}. |

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledge.property.name"></a>

```python
name: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#name IntegrationAction#name}.

---

##### `alias`<sup>Optional</sup> <a name="alias" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledge.property.alias"></a>

```python
alias: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#alias IntegrationAction#alias}.

---

##### `filter`<sup>Optional</sup> <a name="filter" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledge.property.filter"></a>

```python
filter: typing.Union[IResolvable, typing.List[IntegrationActionAcknowledgeFilter]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilter">IntegrationActionAcknowledgeFilter</a>]]

filter block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#filter IntegrationAction#filter}

---

##### `note`<sup>Optional</sup> <a name="note" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledge.property.note"></a>

```python
note: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#note IntegrationAction#note}.

---

##### `order`<sup>Optional</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledge.property.order"></a>

```python
order: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#order IntegrationAction#order}.

---

##### `type`<sup>Optional</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledge.property.type"></a>

```python
type: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#type IntegrationAction#type}.

---

##### `user`<sup>Optional</sup> <a name="user" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledge.property.user"></a>

```python
user: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#user IntegrationAction#user}.

---

### IntegrationActionAcknowledgeFilter <a name="IntegrationActionAcknowledgeFilter" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilter"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilter.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionAcknowledgeFilter(
  type: str,
  conditions: typing.Union[IResolvable, typing.List[IntegrationActionAcknowledgeFilterConditions]] = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilter.property.type">type</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#type IntegrationAction#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilter.property.conditions">conditions</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditions">IntegrationActionAcknowledgeFilterConditions</a>]]</code> | conditions block. |

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilter.property.type"></a>

```python
type: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#type IntegrationAction#type}.

---

##### `conditions`<sup>Optional</sup> <a name="conditions" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilter.property.conditions"></a>

```python
conditions: typing.Union[IResolvable, typing.List[IntegrationActionAcknowledgeFilterConditions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditions">IntegrationActionAcknowledgeFilterConditions</a>]]

conditions block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#conditions IntegrationAction#conditions}

---

### IntegrationActionAcknowledgeFilterConditions <a name="IntegrationActionAcknowledgeFilterConditions" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditions"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditions.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionAcknowledgeFilterConditions(
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
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditions.property.field">field</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#field IntegrationAction#field}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditions.property.operation">operation</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#operation IntegrationAction#operation}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditions.property.expectedValue">expected_value</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#expected_value IntegrationAction#expected_value}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditions.property.key">key</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#key IntegrationAction#key}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditions.property.not">not</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#not IntegrationAction#not}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditions.property.order">order</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#order IntegrationAction#order}. |

---

##### `field`<sup>Required</sup> <a name="field" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditions.property.field"></a>

```python
field: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#field IntegrationAction#field}.

---

##### `operation`<sup>Required</sup> <a name="operation" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditions.property.operation"></a>

```python
operation: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#operation IntegrationAction#operation}.

---

##### `expected_value`<sup>Optional</sup> <a name="expected_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditions.property.expectedValue"></a>

```python
expected_value: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#expected_value IntegrationAction#expected_value}.

---

##### `key`<sup>Optional</sup> <a name="key" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditions.property.key"></a>

```python
key: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#key IntegrationAction#key}.

---

##### `not`<sup>Optional</sup> <a name="not" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditions.property.not"></a>

```python
not: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#not IntegrationAction#not}.

---

##### `order`<sup>Optional</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditions.property.order"></a>

```python
order: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#order IntegrationAction#order}.

---

### IntegrationActionAddNote <a name="IntegrationActionAddNote" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNote"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNote.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionAddNote(
  name: str,
  alias: str = None,
  filter: typing.Union[IResolvable, typing.List[IntegrationActionAddNoteFilter]] = None,
  note: str = None,
  order: typing.Union[int, float] = None,
  type: str = None,
  user: str = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNote.property.name">name</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#name IntegrationAction#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNote.property.alias">alias</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#alias IntegrationAction#alias}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNote.property.filter">filter</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilter">IntegrationActionAddNoteFilter</a>]]</code> | filter block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNote.property.note">note</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#note IntegrationAction#note}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNote.property.order">order</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#order IntegrationAction#order}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNote.property.type">type</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#type IntegrationAction#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNote.property.user">user</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#user IntegrationAction#user}. |

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNote.property.name"></a>

```python
name: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#name IntegrationAction#name}.

---

##### `alias`<sup>Optional</sup> <a name="alias" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNote.property.alias"></a>

```python
alias: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#alias IntegrationAction#alias}.

---

##### `filter`<sup>Optional</sup> <a name="filter" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNote.property.filter"></a>

```python
filter: typing.Union[IResolvable, typing.List[IntegrationActionAddNoteFilter]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilter">IntegrationActionAddNoteFilter</a>]]

filter block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#filter IntegrationAction#filter}

---

##### `note`<sup>Optional</sup> <a name="note" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNote.property.note"></a>

```python
note: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#note IntegrationAction#note}.

---

##### `order`<sup>Optional</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNote.property.order"></a>

```python
order: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#order IntegrationAction#order}.

---

##### `type`<sup>Optional</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNote.property.type"></a>

```python
type: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#type IntegrationAction#type}.

---

##### `user`<sup>Optional</sup> <a name="user" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNote.property.user"></a>

```python
user: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#user IntegrationAction#user}.

---

### IntegrationActionAddNoteFilter <a name="IntegrationActionAddNoteFilter" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilter"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilter.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionAddNoteFilter(
  type: str,
  conditions: typing.Union[IResolvable, typing.List[IntegrationActionAddNoteFilterConditions]] = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilter.property.type">type</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#type IntegrationAction#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilter.property.conditions">conditions</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditions">IntegrationActionAddNoteFilterConditions</a>]]</code> | conditions block. |

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilter.property.type"></a>

```python
type: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#type IntegrationAction#type}.

---

##### `conditions`<sup>Optional</sup> <a name="conditions" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilter.property.conditions"></a>

```python
conditions: typing.Union[IResolvable, typing.List[IntegrationActionAddNoteFilterConditions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditions">IntegrationActionAddNoteFilterConditions</a>]]

conditions block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#conditions IntegrationAction#conditions}

---

### IntegrationActionAddNoteFilterConditions <a name="IntegrationActionAddNoteFilterConditions" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditions"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditions.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionAddNoteFilterConditions(
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
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditions.property.field">field</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#field IntegrationAction#field}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditions.property.operation">operation</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#operation IntegrationAction#operation}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditions.property.expectedValue">expected_value</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#expected_value IntegrationAction#expected_value}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditions.property.key">key</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#key IntegrationAction#key}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditions.property.not">not</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#not IntegrationAction#not}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditions.property.order">order</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#order IntegrationAction#order}. |

---

##### `field`<sup>Required</sup> <a name="field" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditions.property.field"></a>

```python
field: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#field IntegrationAction#field}.

---

##### `operation`<sup>Required</sup> <a name="operation" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditions.property.operation"></a>

```python
operation: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#operation IntegrationAction#operation}.

---

##### `expected_value`<sup>Optional</sup> <a name="expected_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditions.property.expectedValue"></a>

```python
expected_value: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#expected_value IntegrationAction#expected_value}.

---

##### `key`<sup>Optional</sup> <a name="key" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditions.property.key"></a>

```python
key: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#key IntegrationAction#key}.

---

##### `not`<sup>Optional</sup> <a name="not" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditions.property.not"></a>

```python
not: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#not IntegrationAction#not}.

---

##### `order`<sup>Optional</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditions.property.order"></a>

```python
order: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#order IntegrationAction#order}.

---

### IntegrationActionClose <a name="IntegrationActionClose" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionClose"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionClose.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionClose(
  name: str,
  alias: str = None,
  filter: typing.Union[IResolvable, typing.List[IntegrationActionCloseFilter]] = None,
  note: str = None,
  order: typing.Union[int, float] = None,
  type: str = None,
  user: str = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionClose.property.name">name</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#name IntegrationAction#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionClose.property.alias">alias</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#alias IntegrationAction#alias}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionClose.property.filter">filter</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilter">IntegrationActionCloseFilter</a>]]</code> | filter block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionClose.property.note">note</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#note IntegrationAction#note}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionClose.property.order">order</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#order IntegrationAction#order}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionClose.property.type">type</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#type IntegrationAction#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionClose.property.user">user</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#user IntegrationAction#user}. |

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionClose.property.name"></a>

```python
name: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#name IntegrationAction#name}.

---

##### `alias`<sup>Optional</sup> <a name="alias" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionClose.property.alias"></a>

```python
alias: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#alias IntegrationAction#alias}.

---

##### `filter`<sup>Optional</sup> <a name="filter" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionClose.property.filter"></a>

```python
filter: typing.Union[IResolvable, typing.List[IntegrationActionCloseFilter]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilter">IntegrationActionCloseFilter</a>]]

filter block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#filter IntegrationAction#filter}

---

##### `note`<sup>Optional</sup> <a name="note" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionClose.property.note"></a>

```python
note: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#note IntegrationAction#note}.

---

##### `order`<sup>Optional</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionClose.property.order"></a>

```python
order: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#order IntegrationAction#order}.

---

##### `type`<sup>Optional</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionClose.property.type"></a>

```python
type: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#type IntegrationAction#type}.

---

##### `user`<sup>Optional</sup> <a name="user" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionClose.property.user"></a>

```python
user: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#user IntegrationAction#user}.

---

### IntegrationActionCloseFilter <a name="IntegrationActionCloseFilter" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilter"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilter.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionCloseFilter(
  type: str,
  conditions: typing.Union[IResolvable, typing.List[IntegrationActionCloseFilterConditions]] = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilter.property.type">type</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#type IntegrationAction#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilter.property.conditions">conditions</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditions">IntegrationActionCloseFilterConditions</a>]]</code> | conditions block. |

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilter.property.type"></a>

```python
type: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#type IntegrationAction#type}.

---

##### `conditions`<sup>Optional</sup> <a name="conditions" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilter.property.conditions"></a>

```python
conditions: typing.Union[IResolvable, typing.List[IntegrationActionCloseFilterConditions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditions">IntegrationActionCloseFilterConditions</a>]]

conditions block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#conditions IntegrationAction#conditions}

---

### IntegrationActionCloseFilterConditions <a name="IntegrationActionCloseFilterConditions" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditions"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditions.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionCloseFilterConditions(
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
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditions.property.field">field</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#field IntegrationAction#field}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditions.property.operation">operation</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#operation IntegrationAction#operation}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditions.property.expectedValue">expected_value</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#expected_value IntegrationAction#expected_value}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditions.property.key">key</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#key IntegrationAction#key}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditions.property.not">not</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#not IntegrationAction#not}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditions.property.order">order</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#order IntegrationAction#order}. |

---

##### `field`<sup>Required</sup> <a name="field" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditions.property.field"></a>

```python
field: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#field IntegrationAction#field}.

---

##### `operation`<sup>Required</sup> <a name="operation" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditions.property.operation"></a>

```python
operation: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#operation IntegrationAction#operation}.

---

##### `expected_value`<sup>Optional</sup> <a name="expected_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditions.property.expectedValue"></a>

```python
expected_value: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#expected_value IntegrationAction#expected_value}.

---

##### `key`<sup>Optional</sup> <a name="key" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditions.property.key"></a>

```python
key: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#key IntegrationAction#key}.

---

##### `not`<sup>Optional</sup> <a name="not" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditions.property.not"></a>

```python
not: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#not IntegrationAction#not}.

---

##### `order`<sup>Optional</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditions.property.order"></a>

```python
order: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#order IntegrationAction#order}.

---

### IntegrationActionConfig <a name="IntegrationActionConfig" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionConfig"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionConfig.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionConfig(
  connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection] = None,
  count: typing.Union[typing.Union[int, float], TerraformCount] = None,
  depends_on: typing.List[ITerraformDependable] = None,
  for_each: ITerraformIterator = None,
  lifecycle: TerraformResourceLifecycle = None,
  provider: TerraformProvider = None,
  provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]] = None,
  integration_id: str,
  acknowledge: typing.Union[IResolvable, typing.List[IntegrationActionAcknowledge]] = None,
  add_note: typing.Union[IResolvable, typing.List[IntegrationActionAddNote]] = None,
  close: typing.Union[IResolvable, typing.List[IntegrationActionClose]] = None,
  create: typing.Union[IResolvable, typing.List[IntegrationActionCreate]] = None,
  id: str = None,
  ignore: typing.Union[IResolvable, typing.List[IntegrationActionIgnore]] = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionConfig.property.connection">connection</a></code> | <code>typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionConfig.property.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionConfig.property.dependsOn">depends_on</a></code> | <code>typing.List[cdktf.ITerraformDependable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionConfig.property.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionConfig.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionConfig.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionConfig.property.provisioners">provisioners</a></code> | <code>typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionConfig.property.integrationId">integration_id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#integration_id IntegrationAction#integration_id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionConfig.property.acknowledge">acknowledge</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledge">IntegrationActionAcknowledge</a>]]</code> | acknowledge block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionConfig.property.addNote">add_note</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNote">IntegrationActionAddNote</a>]]</code> | add_note block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionConfig.property.close">close</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionClose">IntegrationActionClose</a>]]</code> | close block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionConfig.property.create">create</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate">IntegrationActionCreate</a>]]</code> | create block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionConfig.property.id">id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#id IntegrationAction#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionConfig.property.ignore">ignore</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnore">IntegrationActionIgnore</a>]]</code> | ignore block. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionConfig.property.connection"></a>

```python
connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection]
```

- *Type:* typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionConfig.property.count"></a>

```python
count: typing.Union[typing.Union[int, float], TerraformCount]
```

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionConfig.property.dependsOn"></a>

```python
depends_on: typing.List[ITerraformDependable]
```

- *Type:* typing.List[cdktf.ITerraformDependable]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionConfig.property.forEach"></a>

```python
for_each: ITerraformIterator
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionConfig.property.lifecycle"></a>

```python
lifecycle: TerraformResourceLifecycle
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionConfig.property.provider"></a>

```python
provider: TerraformProvider
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionConfig.property.provisioners"></a>

```python
provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]]
```

- *Type:* typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]

---

##### `integration_id`<sup>Required</sup> <a name="integration_id" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionConfig.property.integrationId"></a>

```python
integration_id: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#integration_id IntegrationAction#integration_id}.

---

##### `acknowledge`<sup>Optional</sup> <a name="acknowledge" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionConfig.property.acknowledge"></a>

```python
acknowledge: typing.Union[IResolvable, typing.List[IntegrationActionAcknowledge]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledge">IntegrationActionAcknowledge</a>]]

acknowledge block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#acknowledge IntegrationAction#acknowledge}

---

##### `add_note`<sup>Optional</sup> <a name="add_note" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionConfig.property.addNote"></a>

```python
add_note: typing.Union[IResolvable, typing.List[IntegrationActionAddNote]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNote">IntegrationActionAddNote</a>]]

add_note block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#add_note IntegrationAction#add_note}

---

##### `close`<sup>Optional</sup> <a name="close" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionConfig.property.close"></a>

```python
close: typing.Union[IResolvable, typing.List[IntegrationActionClose]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionClose">IntegrationActionClose</a>]]

close block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#close IntegrationAction#close}

---

##### `create`<sup>Optional</sup> <a name="create" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionConfig.property.create"></a>

```python
create: typing.Union[IResolvable, typing.List[IntegrationActionCreate]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate">IntegrationActionCreate</a>]]

create block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#create IntegrationAction#create}

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionConfig.property.id"></a>

```python
id: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#id IntegrationAction#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `ignore`<sup>Optional</sup> <a name="ignore" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionConfig.property.ignore"></a>

```python
ignore: typing.Union[IResolvable, typing.List[IntegrationActionIgnore]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnore">IntegrationActionIgnore</a>]]

ignore block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#ignore IntegrationAction#ignore}

---

### IntegrationActionCreate <a name="IntegrationActionCreate" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionCreate(
  name: str,
  alert_actions: typing.List[str] = None,
  alias: str = None,
  append_attachments: typing.Union[bool, IResolvable] = None,
  custom_priority: str = None,
  description: str = None,
  entity: str = None,
  extra_properties: typing.Mapping[str] = None,
  filter: typing.Union[IResolvable, typing.List[IntegrationActionCreateFilter]] = None,
  ignore_alert_actions_from_payload: typing.Union[bool, IResolvable] = None,
  ignore_extra_properties_from_payload: typing.Union[bool, IResolvable] = None,
  ignore_responders_from_payload: typing.Union[bool, IResolvable] = None,
  ignore_tags_from_payload: typing.Union[bool, IResolvable] = None,
  ignore_teams_from_payload: typing.Union[bool, IResolvable] = None,
  message: str = None,
  note: str = None,
  order: typing.Union[int, float] = None,
  priority: str = None,
  responders: typing.Union[IResolvable, typing.List[IntegrationActionCreateResponders]] = None,
  source: str = None,
  tags: typing.List[str] = None,
  type: str = None,
  user: str = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.name">name</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#name IntegrationAction#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.alertActions">alert_actions</a></code> | <code>typing.List[str]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#alert_actions IntegrationAction#alert_actions}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.alias">alias</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#alias IntegrationAction#alias}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.appendAttachments">append_attachments</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#append_attachments IntegrationAction#append_attachments}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.customPriority">custom_priority</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#custom_priority IntegrationAction#custom_priority}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.description">description</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#description IntegrationAction#description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.entity">entity</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#entity IntegrationAction#entity}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.extraProperties">extra_properties</a></code> | <code>typing.Mapping[str]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#extra_properties IntegrationAction#extra_properties}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.filter">filter</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilter">IntegrationActionCreateFilter</a>]]</code> | filter block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.ignoreAlertActionsFromPayload">ignore_alert_actions_from_payload</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#ignore_alert_actions_from_payload IntegrationAction#ignore_alert_actions_from_payload}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.ignoreExtraPropertiesFromPayload">ignore_extra_properties_from_payload</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#ignore_extra_properties_from_payload IntegrationAction#ignore_extra_properties_from_payload}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.ignoreRespondersFromPayload">ignore_responders_from_payload</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#ignore_responders_from_payload IntegrationAction#ignore_responders_from_payload}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.ignoreTagsFromPayload">ignore_tags_from_payload</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#ignore_tags_from_payload IntegrationAction#ignore_tags_from_payload}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.ignoreTeamsFromPayload">ignore_teams_from_payload</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#ignore_teams_from_payload IntegrationAction#ignore_teams_from_payload}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.message">message</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#message IntegrationAction#message}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.note">note</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#note IntegrationAction#note}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.order">order</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#order IntegrationAction#order}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.priority">priority</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#priority IntegrationAction#priority}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.responders">responders</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateResponders">IntegrationActionCreateResponders</a>]]</code> | responders block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.source">source</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#source IntegrationAction#source}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.tags">tags</a></code> | <code>typing.List[str]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#tags IntegrationAction#tags}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.type">type</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#type IntegrationAction#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.user">user</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#user IntegrationAction#user}. |

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.name"></a>

```python
name: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#name IntegrationAction#name}.

---

##### `alert_actions`<sup>Optional</sup> <a name="alert_actions" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.alertActions"></a>

```python
alert_actions: typing.List[str]
```

- *Type:* typing.List[str]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#alert_actions IntegrationAction#alert_actions}.

---

##### `alias`<sup>Optional</sup> <a name="alias" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.alias"></a>

```python
alias: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#alias IntegrationAction#alias}.

---

##### `append_attachments`<sup>Optional</sup> <a name="append_attachments" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.appendAttachments"></a>

```python
append_attachments: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#append_attachments IntegrationAction#append_attachments}.

---

##### `custom_priority`<sup>Optional</sup> <a name="custom_priority" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.customPriority"></a>

```python
custom_priority: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#custom_priority IntegrationAction#custom_priority}.

---

##### `description`<sup>Optional</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.description"></a>

```python
description: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#description IntegrationAction#description}.

---

##### `entity`<sup>Optional</sup> <a name="entity" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.entity"></a>

```python
entity: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#entity IntegrationAction#entity}.

---

##### `extra_properties`<sup>Optional</sup> <a name="extra_properties" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.extraProperties"></a>

```python
extra_properties: typing.Mapping[str]
```

- *Type:* typing.Mapping[str]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#extra_properties IntegrationAction#extra_properties}.

---

##### `filter`<sup>Optional</sup> <a name="filter" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.filter"></a>

```python
filter: typing.Union[IResolvable, typing.List[IntegrationActionCreateFilter]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilter">IntegrationActionCreateFilter</a>]]

filter block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#filter IntegrationAction#filter}

---

##### `ignore_alert_actions_from_payload`<sup>Optional</sup> <a name="ignore_alert_actions_from_payload" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.ignoreAlertActionsFromPayload"></a>

```python
ignore_alert_actions_from_payload: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#ignore_alert_actions_from_payload IntegrationAction#ignore_alert_actions_from_payload}.

---

##### `ignore_extra_properties_from_payload`<sup>Optional</sup> <a name="ignore_extra_properties_from_payload" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.ignoreExtraPropertiesFromPayload"></a>

```python
ignore_extra_properties_from_payload: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#ignore_extra_properties_from_payload IntegrationAction#ignore_extra_properties_from_payload}.

---

##### `ignore_responders_from_payload`<sup>Optional</sup> <a name="ignore_responders_from_payload" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.ignoreRespondersFromPayload"></a>

```python
ignore_responders_from_payload: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#ignore_responders_from_payload IntegrationAction#ignore_responders_from_payload}.

---

##### `ignore_tags_from_payload`<sup>Optional</sup> <a name="ignore_tags_from_payload" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.ignoreTagsFromPayload"></a>

```python
ignore_tags_from_payload: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#ignore_tags_from_payload IntegrationAction#ignore_tags_from_payload}.

---

##### `ignore_teams_from_payload`<sup>Optional</sup> <a name="ignore_teams_from_payload" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.ignoreTeamsFromPayload"></a>

```python
ignore_teams_from_payload: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#ignore_teams_from_payload IntegrationAction#ignore_teams_from_payload}.

---

##### `message`<sup>Optional</sup> <a name="message" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.message"></a>

```python
message: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#message IntegrationAction#message}.

---

##### `note`<sup>Optional</sup> <a name="note" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.note"></a>

```python
note: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#note IntegrationAction#note}.

---

##### `order`<sup>Optional</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.order"></a>

```python
order: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#order IntegrationAction#order}.

---

##### `priority`<sup>Optional</sup> <a name="priority" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.priority"></a>

```python
priority: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#priority IntegrationAction#priority}.

---

##### `responders`<sup>Optional</sup> <a name="responders" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.responders"></a>

```python
responders: typing.Union[IResolvable, typing.List[IntegrationActionCreateResponders]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateResponders">IntegrationActionCreateResponders</a>]]

responders block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#responders IntegrationAction#responders}

---

##### `source`<sup>Optional</sup> <a name="source" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.source"></a>

```python
source: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#source IntegrationAction#source}.

---

##### `tags`<sup>Optional</sup> <a name="tags" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.tags"></a>

```python
tags: typing.List[str]
```

- *Type:* typing.List[str]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#tags IntegrationAction#tags}.

---

##### `type`<sup>Optional</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.type"></a>

```python
type: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#type IntegrationAction#type}.

---

##### `user`<sup>Optional</sup> <a name="user" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate.property.user"></a>

```python
user: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#user IntegrationAction#user}.

---

### IntegrationActionCreateFilter <a name="IntegrationActionCreateFilter" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilter"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilter.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionCreateFilter(
  type: str,
  conditions: typing.Union[IResolvable, typing.List[IntegrationActionCreateFilterConditions]] = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilter.property.type">type</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#type IntegrationAction#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilter.property.conditions">conditions</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditions">IntegrationActionCreateFilterConditions</a>]]</code> | conditions block. |

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilter.property.type"></a>

```python
type: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#type IntegrationAction#type}.

---

##### `conditions`<sup>Optional</sup> <a name="conditions" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilter.property.conditions"></a>

```python
conditions: typing.Union[IResolvable, typing.List[IntegrationActionCreateFilterConditions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditions">IntegrationActionCreateFilterConditions</a>]]

conditions block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#conditions IntegrationAction#conditions}

---

### IntegrationActionCreateFilterConditions <a name="IntegrationActionCreateFilterConditions" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditions"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditions.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionCreateFilterConditions(
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
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditions.property.field">field</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#field IntegrationAction#field}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditions.property.operation">operation</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#operation IntegrationAction#operation}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditions.property.expectedValue">expected_value</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#expected_value IntegrationAction#expected_value}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditions.property.key">key</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#key IntegrationAction#key}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditions.property.not">not</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#not IntegrationAction#not}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditions.property.order">order</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#order IntegrationAction#order}. |

---

##### `field`<sup>Required</sup> <a name="field" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditions.property.field"></a>

```python
field: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#field IntegrationAction#field}.

---

##### `operation`<sup>Required</sup> <a name="operation" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditions.property.operation"></a>

```python
operation: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#operation IntegrationAction#operation}.

---

##### `expected_value`<sup>Optional</sup> <a name="expected_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditions.property.expectedValue"></a>

```python
expected_value: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#expected_value IntegrationAction#expected_value}.

---

##### `key`<sup>Optional</sup> <a name="key" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditions.property.key"></a>

```python
key: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#key IntegrationAction#key}.

---

##### `not`<sup>Optional</sup> <a name="not" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditions.property.not"></a>

```python
not: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#not IntegrationAction#not}.

---

##### `order`<sup>Optional</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditions.property.order"></a>

```python
order: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#order IntegrationAction#order}.

---

### IntegrationActionCreateResponders <a name="IntegrationActionCreateResponders" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateResponders"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateResponders.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionCreateResponders(
  id: str,
  type: str
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateResponders.property.id">id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#id IntegrationAction#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateResponders.property.type">type</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#type IntegrationAction#type}. |

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateResponders.property.id"></a>

```python
id: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#id IntegrationAction#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateResponders.property.type"></a>

```python
type: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#type IntegrationAction#type}.

---

### IntegrationActionIgnore <a name="IntegrationActionIgnore" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnore"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnore.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionIgnore(
  name: str,
  filter: typing.Union[IResolvable, typing.List[IntegrationActionIgnoreFilter]] = None,
  order: typing.Union[int, float] = None,
  type: str = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnore.property.name">name</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#name IntegrationAction#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnore.property.filter">filter</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilter">IntegrationActionIgnoreFilter</a>]]</code> | filter block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnore.property.order">order</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#order IntegrationAction#order}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnore.property.type">type</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#type IntegrationAction#type}. |

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnore.property.name"></a>

```python
name: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#name IntegrationAction#name}.

---

##### `filter`<sup>Optional</sup> <a name="filter" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnore.property.filter"></a>

```python
filter: typing.Union[IResolvable, typing.List[IntegrationActionIgnoreFilter]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilter">IntegrationActionIgnoreFilter</a>]]

filter block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#filter IntegrationAction#filter}

---

##### `order`<sup>Optional</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnore.property.order"></a>

```python
order: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#order IntegrationAction#order}.

---

##### `type`<sup>Optional</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnore.property.type"></a>

```python
type: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#type IntegrationAction#type}.

---

### IntegrationActionIgnoreFilter <a name="IntegrationActionIgnoreFilter" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilter"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilter.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionIgnoreFilter(
  type: str,
  conditions: typing.Union[IResolvable, typing.List[IntegrationActionIgnoreFilterConditions]] = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilter.property.type">type</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#type IntegrationAction#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilter.property.conditions">conditions</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditions">IntegrationActionIgnoreFilterConditions</a>]]</code> | conditions block. |

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilter.property.type"></a>

```python
type: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#type IntegrationAction#type}.

---

##### `conditions`<sup>Optional</sup> <a name="conditions" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilter.property.conditions"></a>

```python
conditions: typing.Union[IResolvable, typing.List[IntegrationActionIgnoreFilterConditions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditions">IntegrationActionIgnoreFilterConditions</a>]]

conditions block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#conditions IntegrationAction#conditions}

---

### IntegrationActionIgnoreFilterConditions <a name="IntegrationActionIgnoreFilterConditions" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditions"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditions.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionIgnoreFilterConditions(
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
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditions.property.field">field</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#field IntegrationAction#field}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditions.property.operation">operation</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#operation IntegrationAction#operation}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditions.property.expectedValue">expected_value</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#expected_value IntegrationAction#expected_value}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditions.property.key">key</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#key IntegrationAction#key}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditions.property.not">not</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#not IntegrationAction#not}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditions.property.order">order</a></code> | <code>typing.Union[int, float]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#order IntegrationAction#order}. |

---

##### `field`<sup>Required</sup> <a name="field" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditions.property.field"></a>

```python
field: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#field IntegrationAction#field}.

---

##### `operation`<sup>Required</sup> <a name="operation" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditions.property.operation"></a>

```python
operation: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#operation IntegrationAction#operation}.

---

##### `expected_value`<sup>Optional</sup> <a name="expected_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditions.property.expectedValue"></a>

```python
expected_value: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#expected_value IntegrationAction#expected_value}.

---

##### `key`<sup>Optional</sup> <a name="key" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditions.property.key"></a>

```python
key: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#key IntegrationAction#key}.

---

##### `not`<sup>Optional</sup> <a name="not" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditions.property.not"></a>

```python
not: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#not IntegrationAction#not}.

---

##### `order`<sup>Optional</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditions.property.order"></a>

```python
order: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/integration_action#order IntegrationAction#order}.

---

## Classes <a name="Classes" id="Classes"></a>

### IntegrationActionAcknowledgeFilterConditionsList <a name="IntegrationActionAcknowledgeFilterConditionsList" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionAcknowledgeFilterConditionsList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> IntegrationActionAcknowledgeFilterConditionsOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditions">IntegrationActionAcknowledgeFilterConditions</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[IntegrationActionAcknowledgeFilterConditions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditions">IntegrationActionAcknowledgeFilterConditions</a>]]

---


### IntegrationActionAcknowledgeFilterConditionsOutputReference <a name="IntegrationActionAcknowledgeFilterConditionsOutputReference" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.resetExpectedValue">reset_expected_value</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.resetKey">reset_key</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.resetNot">reset_not</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.resetOrder">reset_order</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `reset_expected_value` <a name="reset_expected_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.resetExpectedValue"></a>

```python
def reset_expected_value() -> None
```

##### `reset_key` <a name="reset_key" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.resetKey"></a>

```python
def reset_key() -> None
```

##### `reset_not` <a name="reset_not" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.resetNot"></a>

```python
def reset_not() -> None
```

##### `reset_order` <a name="reset_order" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.resetOrder"></a>

```python
def reset_order() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.property.expectedValueInput">expected_value_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.property.fieldInput">field_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.property.keyInput">key_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.property.notInput">not_input</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.property.operationInput">operation_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.property.orderInput">order_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.property.expectedValue">expected_value</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.property.field">field</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.property.key">key</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.property.not">not</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.property.operation">operation</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.property.order">order</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditions">IntegrationActionAcknowledgeFilterConditions</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `expected_value_input`<sup>Optional</sup> <a name="expected_value_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.property.expectedValueInput"></a>

```python
expected_value_input: str
```

- *Type:* str

---

##### `field_input`<sup>Optional</sup> <a name="field_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.property.fieldInput"></a>

```python
field_input: str
```

- *Type:* str

---

##### `key_input`<sup>Optional</sup> <a name="key_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.property.keyInput"></a>

```python
key_input: str
```

- *Type:* str

---

##### `not_input`<sup>Optional</sup> <a name="not_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.property.notInput"></a>

```python
not_input: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `operation_input`<sup>Optional</sup> <a name="operation_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.property.operationInput"></a>

```python
operation_input: str
```

- *Type:* str

---

##### `order_input`<sup>Optional</sup> <a name="order_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.property.orderInput"></a>

```python
order_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `expected_value`<sup>Required</sup> <a name="expected_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.property.expectedValue"></a>

```python
expected_value: str
```

- *Type:* str

---

##### `field`<sup>Required</sup> <a name="field" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.property.field"></a>

```python
field: str
```

- *Type:* str

---

##### `key`<sup>Required</sup> <a name="key" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.property.key"></a>

```python
key: str
```

- *Type:* str

---

##### `not`<sup>Required</sup> <a name="not" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.property.not"></a>

```python
not: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `operation`<sup>Required</sup> <a name="operation" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.property.operation"></a>

```python
operation: str
```

- *Type:* str

---

##### `order`<sup>Required</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.property.order"></a>

```python
order: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, IntegrationActionAcknowledgeFilterConditions]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditions">IntegrationActionAcknowledgeFilterConditions</a>]

---


### IntegrationActionAcknowledgeFilterList <a name="IntegrationActionAcknowledgeFilterList" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionAcknowledgeFilterList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> IntegrationActionAcknowledgeFilterOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilter">IntegrationActionAcknowledgeFilter</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[IntegrationActionAcknowledgeFilter]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilter">IntegrationActionAcknowledgeFilter</a>]]

---


### IntegrationActionAcknowledgeFilterOutputReference <a name="IntegrationActionAcknowledgeFilterOutputReference" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionAcknowledgeFilterOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.putConditions">put_conditions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.resetConditions">reset_conditions</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `put_conditions` <a name="put_conditions" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.putConditions"></a>

```python
def put_conditions(
  value: typing.Union[IResolvable, typing.List[IntegrationActionAcknowledgeFilterConditions]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.putConditions.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditions">IntegrationActionAcknowledgeFilterConditions</a>]]

---

##### `reset_conditions` <a name="reset_conditions" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.resetConditions"></a>

```python
def reset_conditions() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.property.conditions">conditions</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsList">IntegrationActionAcknowledgeFilterConditionsList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.property.conditionsInput">conditions_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditions">IntegrationActionAcknowledgeFilterConditions</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.property.typeInput">type_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.property.type">type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilter">IntegrationActionAcknowledgeFilter</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `conditions`<sup>Required</sup> <a name="conditions" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.property.conditions"></a>

```python
conditions: IntegrationActionAcknowledgeFilterConditionsList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditionsList">IntegrationActionAcknowledgeFilterConditionsList</a>

---

##### `conditions_input`<sup>Optional</sup> <a name="conditions_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.property.conditionsInput"></a>

```python
conditions_input: typing.Union[IResolvable, typing.List[IntegrationActionAcknowledgeFilterConditions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterConditions">IntegrationActionAcknowledgeFilterConditions</a>]]

---

##### `type_input`<sup>Optional</sup> <a name="type_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.property.typeInput"></a>

```python
type_input: str
```

- *Type:* str

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.property.type"></a>

```python
type: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, IntegrationActionAcknowledgeFilter]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilter">IntegrationActionAcknowledgeFilter</a>]

---


### IntegrationActionAcknowledgeList <a name="IntegrationActionAcknowledgeList" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionAcknowledgeList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> IntegrationActionAcknowledgeOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledge">IntegrationActionAcknowledge</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[IntegrationActionAcknowledge]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledge">IntegrationActionAcknowledge</a>]]

---


### IntegrationActionAcknowledgeOutputReference <a name="IntegrationActionAcknowledgeOutputReference" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionAcknowledgeOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.putFilter">put_filter</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.resetAlias">reset_alias</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.resetFilter">reset_filter</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.resetNote">reset_note</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.resetOrder">reset_order</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.resetType">reset_type</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.resetUser">reset_user</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `put_filter` <a name="put_filter" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.putFilter"></a>

```python
def put_filter(
  value: typing.Union[IResolvable, typing.List[IntegrationActionAcknowledgeFilter]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.putFilter.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilter">IntegrationActionAcknowledgeFilter</a>]]

---

##### `reset_alias` <a name="reset_alias" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.resetAlias"></a>

```python
def reset_alias() -> None
```

##### `reset_filter` <a name="reset_filter" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.resetFilter"></a>

```python
def reset_filter() -> None
```

##### `reset_note` <a name="reset_note" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.resetNote"></a>

```python
def reset_note() -> None
```

##### `reset_order` <a name="reset_order" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.resetOrder"></a>

```python
def reset_order() -> None
```

##### `reset_type` <a name="reset_type" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.resetType"></a>

```python
def reset_type() -> None
```

##### `reset_user` <a name="reset_user" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.resetUser"></a>

```python
def reset_user() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.property.filter">filter</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterList">IntegrationActionAcknowledgeFilterList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.property.aliasInput">alias_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.property.filterInput">filter_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilter">IntegrationActionAcknowledgeFilter</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.property.nameInput">name_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.property.noteInput">note_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.property.orderInput">order_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.property.typeInput">type_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.property.userInput">user_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.property.alias">alias</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.property.name">name</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.property.note">note</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.property.order">order</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.property.type">type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.property.user">user</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledge">IntegrationActionAcknowledge</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `filter`<sup>Required</sup> <a name="filter" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.property.filter"></a>

```python
filter: IntegrationActionAcknowledgeFilterList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilterList">IntegrationActionAcknowledgeFilterList</a>

---

##### `alias_input`<sup>Optional</sup> <a name="alias_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.property.aliasInput"></a>

```python
alias_input: str
```

- *Type:* str

---

##### `filter_input`<sup>Optional</sup> <a name="filter_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.property.filterInput"></a>

```python
filter_input: typing.Union[IResolvable, typing.List[IntegrationActionAcknowledgeFilter]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeFilter">IntegrationActionAcknowledgeFilter</a>]]

---

##### `name_input`<sup>Optional</sup> <a name="name_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.property.nameInput"></a>

```python
name_input: str
```

- *Type:* str

---

##### `note_input`<sup>Optional</sup> <a name="note_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.property.noteInput"></a>

```python
note_input: str
```

- *Type:* str

---

##### `order_input`<sup>Optional</sup> <a name="order_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.property.orderInput"></a>

```python
order_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `type_input`<sup>Optional</sup> <a name="type_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.property.typeInput"></a>

```python
type_input: str
```

- *Type:* str

---

##### `user_input`<sup>Optional</sup> <a name="user_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.property.userInput"></a>

```python
user_input: str
```

- *Type:* str

---

##### `alias`<sup>Required</sup> <a name="alias" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.property.alias"></a>

```python
alias: str
```

- *Type:* str

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.property.name"></a>

```python
name: str
```

- *Type:* str

---

##### `note`<sup>Required</sup> <a name="note" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.property.note"></a>

```python
note: str
```

- *Type:* str

---

##### `order`<sup>Required</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.property.order"></a>

```python
order: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.property.type"></a>

```python
type: str
```

- *Type:* str

---

##### `user`<sup>Required</sup> <a name="user" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.property.user"></a>

```python
user: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledgeOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, IntegrationActionAcknowledge]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAcknowledge">IntegrationActionAcknowledge</a>]

---


### IntegrationActionAddNoteFilterConditionsList <a name="IntegrationActionAddNoteFilterConditionsList" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionAddNoteFilterConditionsList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> IntegrationActionAddNoteFilterConditionsOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditions">IntegrationActionAddNoteFilterConditions</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[IntegrationActionAddNoteFilterConditions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditions">IntegrationActionAddNoteFilterConditions</a>]]

---


### IntegrationActionAddNoteFilterConditionsOutputReference <a name="IntegrationActionAddNoteFilterConditionsOutputReference" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.resetExpectedValue">reset_expected_value</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.resetKey">reset_key</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.resetNot">reset_not</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.resetOrder">reset_order</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `reset_expected_value` <a name="reset_expected_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.resetExpectedValue"></a>

```python
def reset_expected_value() -> None
```

##### `reset_key` <a name="reset_key" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.resetKey"></a>

```python
def reset_key() -> None
```

##### `reset_not` <a name="reset_not" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.resetNot"></a>

```python
def reset_not() -> None
```

##### `reset_order` <a name="reset_order" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.resetOrder"></a>

```python
def reset_order() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.property.expectedValueInput">expected_value_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.property.fieldInput">field_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.property.keyInput">key_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.property.notInput">not_input</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.property.operationInput">operation_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.property.orderInput">order_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.property.expectedValue">expected_value</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.property.field">field</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.property.key">key</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.property.not">not</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.property.operation">operation</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.property.order">order</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditions">IntegrationActionAddNoteFilterConditions</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `expected_value_input`<sup>Optional</sup> <a name="expected_value_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.property.expectedValueInput"></a>

```python
expected_value_input: str
```

- *Type:* str

---

##### `field_input`<sup>Optional</sup> <a name="field_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.property.fieldInput"></a>

```python
field_input: str
```

- *Type:* str

---

##### `key_input`<sup>Optional</sup> <a name="key_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.property.keyInput"></a>

```python
key_input: str
```

- *Type:* str

---

##### `not_input`<sup>Optional</sup> <a name="not_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.property.notInput"></a>

```python
not_input: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `operation_input`<sup>Optional</sup> <a name="operation_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.property.operationInput"></a>

```python
operation_input: str
```

- *Type:* str

---

##### `order_input`<sup>Optional</sup> <a name="order_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.property.orderInput"></a>

```python
order_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `expected_value`<sup>Required</sup> <a name="expected_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.property.expectedValue"></a>

```python
expected_value: str
```

- *Type:* str

---

##### `field`<sup>Required</sup> <a name="field" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.property.field"></a>

```python
field: str
```

- *Type:* str

---

##### `key`<sup>Required</sup> <a name="key" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.property.key"></a>

```python
key: str
```

- *Type:* str

---

##### `not`<sup>Required</sup> <a name="not" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.property.not"></a>

```python
not: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `operation`<sup>Required</sup> <a name="operation" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.property.operation"></a>

```python
operation: str
```

- *Type:* str

---

##### `order`<sup>Required</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.property.order"></a>

```python
order: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, IntegrationActionAddNoteFilterConditions]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditions">IntegrationActionAddNoteFilterConditions</a>]

---


### IntegrationActionAddNoteFilterList <a name="IntegrationActionAddNoteFilterList" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionAddNoteFilterList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> IntegrationActionAddNoteFilterOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilter">IntegrationActionAddNoteFilter</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[IntegrationActionAddNoteFilter]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilter">IntegrationActionAddNoteFilter</a>]]

---


### IntegrationActionAddNoteFilterOutputReference <a name="IntegrationActionAddNoteFilterOutputReference" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionAddNoteFilterOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.putConditions">put_conditions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.resetConditions">reset_conditions</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `put_conditions` <a name="put_conditions" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.putConditions"></a>

```python
def put_conditions(
  value: typing.Union[IResolvable, typing.List[IntegrationActionAddNoteFilterConditions]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.putConditions.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditions">IntegrationActionAddNoteFilterConditions</a>]]

---

##### `reset_conditions` <a name="reset_conditions" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.resetConditions"></a>

```python
def reset_conditions() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.property.conditions">conditions</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsList">IntegrationActionAddNoteFilterConditionsList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.property.conditionsInput">conditions_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditions">IntegrationActionAddNoteFilterConditions</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.property.typeInput">type_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.property.type">type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilter">IntegrationActionAddNoteFilter</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `conditions`<sup>Required</sup> <a name="conditions" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.property.conditions"></a>

```python
conditions: IntegrationActionAddNoteFilterConditionsList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditionsList">IntegrationActionAddNoteFilterConditionsList</a>

---

##### `conditions_input`<sup>Optional</sup> <a name="conditions_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.property.conditionsInput"></a>

```python
conditions_input: typing.Union[IResolvable, typing.List[IntegrationActionAddNoteFilterConditions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterConditions">IntegrationActionAddNoteFilterConditions</a>]]

---

##### `type_input`<sup>Optional</sup> <a name="type_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.property.typeInput"></a>

```python
type_input: str
```

- *Type:* str

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.property.type"></a>

```python
type: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, IntegrationActionAddNoteFilter]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilter">IntegrationActionAddNoteFilter</a>]

---


### IntegrationActionAddNoteList <a name="IntegrationActionAddNoteList" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionAddNoteList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> IntegrationActionAddNoteOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNote">IntegrationActionAddNote</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[IntegrationActionAddNote]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNote">IntegrationActionAddNote</a>]]

---


### IntegrationActionAddNoteOutputReference <a name="IntegrationActionAddNoteOutputReference" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionAddNoteOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.putFilter">put_filter</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.resetAlias">reset_alias</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.resetFilter">reset_filter</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.resetNote">reset_note</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.resetOrder">reset_order</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.resetType">reset_type</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.resetUser">reset_user</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `put_filter` <a name="put_filter" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.putFilter"></a>

```python
def put_filter(
  value: typing.Union[IResolvable, typing.List[IntegrationActionAddNoteFilter]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.putFilter.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilter">IntegrationActionAddNoteFilter</a>]]

---

##### `reset_alias` <a name="reset_alias" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.resetAlias"></a>

```python
def reset_alias() -> None
```

##### `reset_filter` <a name="reset_filter" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.resetFilter"></a>

```python
def reset_filter() -> None
```

##### `reset_note` <a name="reset_note" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.resetNote"></a>

```python
def reset_note() -> None
```

##### `reset_order` <a name="reset_order" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.resetOrder"></a>

```python
def reset_order() -> None
```

##### `reset_type` <a name="reset_type" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.resetType"></a>

```python
def reset_type() -> None
```

##### `reset_user` <a name="reset_user" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.resetUser"></a>

```python
def reset_user() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.property.filter">filter</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterList">IntegrationActionAddNoteFilterList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.property.aliasInput">alias_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.property.filterInput">filter_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilter">IntegrationActionAddNoteFilter</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.property.nameInput">name_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.property.noteInput">note_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.property.orderInput">order_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.property.typeInput">type_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.property.userInput">user_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.property.alias">alias</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.property.name">name</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.property.note">note</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.property.order">order</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.property.type">type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.property.user">user</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNote">IntegrationActionAddNote</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `filter`<sup>Required</sup> <a name="filter" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.property.filter"></a>

```python
filter: IntegrationActionAddNoteFilterList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilterList">IntegrationActionAddNoteFilterList</a>

---

##### `alias_input`<sup>Optional</sup> <a name="alias_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.property.aliasInput"></a>

```python
alias_input: str
```

- *Type:* str

---

##### `filter_input`<sup>Optional</sup> <a name="filter_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.property.filterInput"></a>

```python
filter_input: typing.Union[IResolvable, typing.List[IntegrationActionAddNoteFilter]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteFilter">IntegrationActionAddNoteFilter</a>]]

---

##### `name_input`<sup>Optional</sup> <a name="name_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.property.nameInput"></a>

```python
name_input: str
```

- *Type:* str

---

##### `note_input`<sup>Optional</sup> <a name="note_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.property.noteInput"></a>

```python
note_input: str
```

- *Type:* str

---

##### `order_input`<sup>Optional</sup> <a name="order_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.property.orderInput"></a>

```python
order_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `type_input`<sup>Optional</sup> <a name="type_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.property.typeInput"></a>

```python
type_input: str
```

- *Type:* str

---

##### `user_input`<sup>Optional</sup> <a name="user_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.property.userInput"></a>

```python
user_input: str
```

- *Type:* str

---

##### `alias`<sup>Required</sup> <a name="alias" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.property.alias"></a>

```python
alias: str
```

- *Type:* str

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.property.name"></a>

```python
name: str
```

- *Type:* str

---

##### `note`<sup>Required</sup> <a name="note" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.property.note"></a>

```python
note: str
```

- *Type:* str

---

##### `order`<sup>Required</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.property.order"></a>

```python
order: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.property.type"></a>

```python
type: str
```

- *Type:* str

---

##### `user`<sup>Required</sup> <a name="user" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.property.user"></a>

```python
user: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNoteOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, IntegrationActionAddNote]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionAddNote">IntegrationActionAddNote</a>]

---


### IntegrationActionCloseFilterConditionsList <a name="IntegrationActionCloseFilterConditionsList" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionCloseFilterConditionsList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> IntegrationActionCloseFilterConditionsOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditions">IntegrationActionCloseFilterConditions</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[IntegrationActionCloseFilterConditions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditions">IntegrationActionCloseFilterConditions</a>]]

---


### IntegrationActionCloseFilterConditionsOutputReference <a name="IntegrationActionCloseFilterConditionsOutputReference" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionCloseFilterConditionsOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.resetExpectedValue">reset_expected_value</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.resetKey">reset_key</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.resetNot">reset_not</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.resetOrder">reset_order</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `reset_expected_value` <a name="reset_expected_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.resetExpectedValue"></a>

```python
def reset_expected_value() -> None
```

##### `reset_key` <a name="reset_key" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.resetKey"></a>

```python
def reset_key() -> None
```

##### `reset_not` <a name="reset_not" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.resetNot"></a>

```python
def reset_not() -> None
```

##### `reset_order` <a name="reset_order" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.resetOrder"></a>

```python
def reset_order() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.property.expectedValueInput">expected_value_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.property.fieldInput">field_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.property.keyInput">key_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.property.notInput">not_input</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.property.operationInput">operation_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.property.orderInput">order_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.property.expectedValue">expected_value</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.property.field">field</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.property.key">key</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.property.not">not</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.property.operation">operation</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.property.order">order</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditions">IntegrationActionCloseFilterConditions</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `expected_value_input`<sup>Optional</sup> <a name="expected_value_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.property.expectedValueInput"></a>

```python
expected_value_input: str
```

- *Type:* str

---

##### `field_input`<sup>Optional</sup> <a name="field_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.property.fieldInput"></a>

```python
field_input: str
```

- *Type:* str

---

##### `key_input`<sup>Optional</sup> <a name="key_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.property.keyInput"></a>

```python
key_input: str
```

- *Type:* str

---

##### `not_input`<sup>Optional</sup> <a name="not_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.property.notInput"></a>

```python
not_input: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `operation_input`<sup>Optional</sup> <a name="operation_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.property.operationInput"></a>

```python
operation_input: str
```

- *Type:* str

---

##### `order_input`<sup>Optional</sup> <a name="order_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.property.orderInput"></a>

```python
order_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `expected_value`<sup>Required</sup> <a name="expected_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.property.expectedValue"></a>

```python
expected_value: str
```

- *Type:* str

---

##### `field`<sup>Required</sup> <a name="field" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.property.field"></a>

```python
field: str
```

- *Type:* str

---

##### `key`<sup>Required</sup> <a name="key" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.property.key"></a>

```python
key: str
```

- *Type:* str

---

##### `not`<sup>Required</sup> <a name="not" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.property.not"></a>

```python
not: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `operation`<sup>Required</sup> <a name="operation" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.property.operation"></a>

```python
operation: str
```

- *Type:* str

---

##### `order`<sup>Required</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.property.order"></a>

```python
order: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, IntegrationActionCloseFilterConditions]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditions">IntegrationActionCloseFilterConditions</a>]

---


### IntegrationActionCloseFilterList <a name="IntegrationActionCloseFilterList" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionCloseFilterList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> IntegrationActionCloseFilterOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilter">IntegrationActionCloseFilter</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[IntegrationActionCloseFilter]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilter">IntegrationActionCloseFilter</a>]]

---


### IntegrationActionCloseFilterOutputReference <a name="IntegrationActionCloseFilterOutputReference" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionCloseFilterOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.putConditions">put_conditions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.resetConditions">reset_conditions</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `put_conditions` <a name="put_conditions" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.putConditions"></a>

```python
def put_conditions(
  value: typing.Union[IResolvable, typing.List[IntegrationActionCloseFilterConditions]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.putConditions.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditions">IntegrationActionCloseFilterConditions</a>]]

---

##### `reset_conditions` <a name="reset_conditions" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.resetConditions"></a>

```python
def reset_conditions() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.property.conditions">conditions</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsList">IntegrationActionCloseFilterConditionsList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.property.conditionsInput">conditions_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditions">IntegrationActionCloseFilterConditions</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.property.typeInput">type_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.property.type">type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilter">IntegrationActionCloseFilter</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `conditions`<sup>Required</sup> <a name="conditions" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.property.conditions"></a>

```python
conditions: IntegrationActionCloseFilterConditionsList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditionsList">IntegrationActionCloseFilterConditionsList</a>

---

##### `conditions_input`<sup>Optional</sup> <a name="conditions_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.property.conditionsInput"></a>

```python
conditions_input: typing.Union[IResolvable, typing.List[IntegrationActionCloseFilterConditions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterConditions">IntegrationActionCloseFilterConditions</a>]]

---

##### `type_input`<sup>Optional</sup> <a name="type_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.property.typeInput"></a>

```python
type_input: str
```

- *Type:* str

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.property.type"></a>

```python
type: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, IntegrationActionCloseFilter]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilter">IntegrationActionCloseFilter</a>]

---


### IntegrationActionCloseList <a name="IntegrationActionCloseList" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionCloseList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> IntegrationActionCloseOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionClose">IntegrationActionClose</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[IntegrationActionClose]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionClose">IntegrationActionClose</a>]]

---


### IntegrationActionCloseOutputReference <a name="IntegrationActionCloseOutputReference" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionCloseOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.putFilter">put_filter</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.resetAlias">reset_alias</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.resetFilter">reset_filter</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.resetNote">reset_note</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.resetOrder">reset_order</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.resetType">reset_type</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.resetUser">reset_user</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `put_filter` <a name="put_filter" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.putFilter"></a>

```python
def put_filter(
  value: typing.Union[IResolvable, typing.List[IntegrationActionCloseFilter]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.putFilter.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilter">IntegrationActionCloseFilter</a>]]

---

##### `reset_alias` <a name="reset_alias" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.resetAlias"></a>

```python
def reset_alias() -> None
```

##### `reset_filter` <a name="reset_filter" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.resetFilter"></a>

```python
def reset_filter() -> None
```

##### `reset_note` <a name="reset_note" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.resetNote"></a>

```python
def reset_note() -> None
```

##### `reset_order` <a name="reset_order" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.resetOrder"></a>

```python
def reset_order() -> None
```

##### `reset_type` <a name="reset_type" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.resetType"></a>

```python
def reset_type() -> None
```

##### `reset_user` <a name="reset_user" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.resetUser"></a>

```python
def reset_user() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.property.filter">filter</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterList">IntegrationActionCloseFilterList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.property.aliasInput">alias_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.property.filterInput">filter_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilter">IntegrationActionCloseFilter</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.property.nameInput">name_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.property.noteInput">note_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.property.orderInput">order_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.property.typeInput">type_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.property.userInput">user_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.property.alias">alias</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.property.name">name</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.property.note">note</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.property.order">order</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.property.type">type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.property.user">user</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionClose">IntegrationActionClose</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `filter`<sup>Required</sup> <a name="filter" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.property.filter"></a>

```python
filter: IntegrationActionCloseFilterList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilterList">IntegrationActionCloseFilterList</a>

---

##### `alias_input`<sup>Optional</sup> <a name="alias_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.property.aliasInput"></a>

```python
alias_input: str
```

- *Type:* str

---

##### `filter_input`<sup>Optional</sup> <a name="filter_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.property.filterInput"></a>

```python
filter_input: typing.Union[IResolvable, typing.List[IntegrationActionCloseFilter]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseFilter">IntegrationActionCloseFilter</a>]]

---

##### `name_input`<sup>Optional</sup> <a name="name_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.property.nameInput"></a>

```python
name_input: str
```

- *Type:* str

---

##### `note_input`<sup>Optional</sup> <a name="note_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.property.noteInput"></a>

```python
note_input: str
```

- *Type:* str

---

##### `order_input`<sup>Optional</sup> <a name="order_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.property.orderInput"></a>

```python
order_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `type_input`<sup>Optional</sup> <a name="type_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.property.typeInput"></a>

```python
type_input: str
```

- *Type:* str

---

##### `user_input`<sup>Optional</sup> <a name="user_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.property.userInput"></a>

```python
user_input: str
```

- *Type:* str

---

##### `alias`<sup>Required</sup> <a name="alias" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.property.alias"></a>

```python
alias: str
```

- *Type:* str

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.property.name"></a>

```python
name: str
```

- *Type:* str

---

##### `note`<sup>Required</sup> <a name="note" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.property.note"></a>

```python
note: str
```

- *Type:* str

---

##### `order`<sup>Required</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.property.order"></a>

```python
order: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.property.type"></a>

```python
type: str
```

- *Type:* str

---

##### `user`<sup>Required</sup> <a name="user" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.property.user"></a>

```python
user: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCloseOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, IntegrationActionClose]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionClose">IntegrationActionClose</a>]

---


### IntegrationActionCreateFilterConditionsList <a name="IntegrationActionCreateFilterConditionsList" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionCreateFilterConditionsList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> IntegrationActionCreateFilterConditionsOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditions">IntegrationActionCreateFilterConditions</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[IntegrationActionCreateFilterConditions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditions">IntegrationActionCreateFilterConditions</a>]]

---


### IntegrationActionCreateFilterConditionsOutputReference <a name="IntegrationActionCreateFilterConditionsOutputReference" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionCreateFilterConditionsOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.resetExpectedValue">reset_expected_value</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.resetKey">reset_key</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.resetNot">reset_not</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.resetOrder">reset_order</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `reset_expected_value` <a name="reset_expected_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.resetExpectedValue"></a>

```python
def reset_expected_value() -> None
```

##### `reset_key` <a name="reset_key" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.resetKey"></a>

```python
def reset_key() -> None
```

##### `reset_not` <a name="reset_not" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.resetNot"></a>

```python
def reset_not() -> None
```

##### `reset_order` <a name="reset_order" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.resetOrder"></a>

```python
def reset_order() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.property.expectedValueInput">expected_value_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.property.fieldInput">field_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.property.keyInput">key_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.property.notInput">not_input</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.property.operationInput">operation_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.property.orderInput">order_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.property.expectedValue">expected_value</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.property.field">field</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.property.key">key</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.property.not">not</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.property.operation">operation</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.property.order">order</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditions">IntegrationActionCreateFilterConditions</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `expected_value_input`<sup>Optional</sup> <a name="expected_value_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.property.expectedValueInput"></a>

```python
expected_value_input: str
```

- *Type:* str

---

##### `field_input`<sup>Optional</sup> <a name="field_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.property.fieldInput"></a>

```python
field_input: str
```

- *Type:* str

---

##### `key_input`<sup>Optional</sup> <a name="key_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.property.keyInput"></a>

```python
key_input: str
```

- *Type:* str

---

##### `not_input`<sup>Optional</sup> <a name="not_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.property.notInput"></a>

```python
not_input: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `operation_input`<sup>Optional</sup> <a name="operation_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.property.operationInput"></a>

```python
operation_input: str
```

- *Type:* str

---

##### `order_input`<sup>Optional</sup> <a name="order_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.property.orderInput"></a>

```python
order_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `expected_value`<sup>Required</sup> <a name="expected_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.property.expectedValue"></a>

```python
expected_value: str
```

- *Type:* str

---

##### `field`<sup>Required</sup> <a name="field" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.property.field"></a>

```python
field: str
```

- *Type:* str

---

##### `key`<sup>Required</sup> <a name="key" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.property.key"></a>

```python
key: str
```

- *Type:* str

---

##### `not`<sup>Required</sup> <a name="not" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.property.not"></a>

```python
not: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `operation`<sup>Required</sup> <a name="operation" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.property.operation"></a>

```python
operation: str
```

- *Type:* str

---

##### `order`<sup>Required</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.property.order"></a>

```python
order: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, IntegrationActionCreateFilterConditions]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditions">IntegrationActionCreateFilterConditions</a>]

---


### IntegrationActionCreateFilterList <a name="IntegrationActionCreateFilterList" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionCreateFilterList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> IntegrationActionCreateFilterOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilter">IntegrationActionCreateFilter</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[IntegrationActionCreateFilter]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilter">IntegrationActionCreateFilter</a>]]

---


### IntegrationActionCreateFilterOutputReference <a name="IntegrationActionCreateFilterOutputReference" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionCreateFilterOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.putConditions">put_conditions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.resetConditions">reset_conditions</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `put_conditions` <a name="put_conditions" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.putConditions"></a>

```python
def put_conditions(
  value: typing.Union[IResolvable, typing.List[IntegrationActionCreateFilterConditions]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.putConditions.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditions">IntegrationActionCreateFilterConditions</a>]]

---

##### `reset_conditions` <a name="reset_conditions" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.resetConditions"></a>

```python
def reset_conditions() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.property.conditions">conditions</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsList">IntegrationActionCreateFilterConditionsList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.property.conditionsInput">conditions_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditions">IntegrationActionCreateFilterConditions</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.property.typeInput">type_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.property.type">type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilter">IntegrationActionCreateFilter</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `conditions`<sup>Required</sup> <a name="conditions" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.property.conditions"></a>

```python
conditions: IntegrationActionCreateFilterConditionsList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditionsList">IntegrationActionCreateFilterConditionsList</a>

---

##### `conditions_input`<sup>Optional</sup> <a name="conditions_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.property.conditionsInput"></a>

```python
conditions_input: typing.Union[IResolvable, typing.List[IntegrationActionCreateFilterConditions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterConditions">IntegrationActionCreateFilterConditions</a>]]

---

##### `type_input`<sup>Optional</sup> <a name="type_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.property.typeInput"></a>

```python
type_input: str
```

- *Type:* str

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.property.type"></a>

```python
type: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, IntegrationActionCreateFilter]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilter">IntegrationActionCreateFilter</a>]

---


### IntegrationActionCreateList <a name="IntegrationActionCreateList" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionCreateList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> IntegrationActionCreateOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate">IntegrationActionCreate</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[IntegrationActionCreate]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate">IntegrationActionCreate</a>]]

---


### IntegrationActionCreateOutputReference <a name="IntegrationActionCreateOutputReference" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionCreateOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.putFilter">put_filter</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.putResponders">put_responders</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetAlertActions">reset_alert_actions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetAlias">reset_alias</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetAppendAttachments">reset_append_attachments</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetCustomPriority">reset_custom_priority</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetDescription">reset_description</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetEntity">reset_entity</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetExtraProperties">reset_extra_properties</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetFilter">reset_filter</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetIgnoreAlertActionsFromPayload">reset_ignore_alert_actions_from_payload</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetIgnoreExtraPropertiesFromPayload">reset_ignore_extra_properties_from_payload</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetIgnoreRespondersFromPayload">reset_ignore_responders_from_payload</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetIgnoreTagsFromPayload">reset_ignore_tags_from_payload</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetIgnoreTeamsFromPayload">reset_ignore_teams_from_payload</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetMessage">reset_message</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetNote">reset_note</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetOrder">reset_order</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetPriority">reset_priority</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetResponders">reset_responders</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetSource">reset_source</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetTags">reset_tags</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetType">reset_type</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetUser">reset_user</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `put_filter` <a name="put_filter" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.putFilter"></a>

```python
def put_filter(
  value: typing.Union[IResolvable, typing.List[IntegrationActionCreateFilter]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.putFilter.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilter">IntegrationActionCreateFilter</a>]]

---

##### `put_responders` <a name="put_responders" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.putResponders"></a>

```python
def put_responders(
  value: typing.Union[IResolvable, typing.List[IntegrationActionCreateResponders]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.putResponders.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateResponders">IntegrationActionCreateResponders</a>]]

---

##### `reset_alert_actions` <a name="reset_alert_actions" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetAlertActions"></a>

```python
def reset_alert_actions() -> None
```

##### `reset_alias` <a name="reset_alias" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetAlias"></a>

```python
def reset_alias() -> None
```

##### `reset_append_attachments` <a name="reset_append_attachments" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetAppendAttachments"></a>

```python
def reset_append_attachments() -> None
```

##### `reset_custom_priority` <a name="reset_custom_priority" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetCustomPriority"></a>

```python
def reset_custom_priority() -> None
```

##### `reset_description` <a name="reset_description" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetDescription"></a>

```python
def reset_description() -> None
```

##### `reset_entity` <a name="reset_entity" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetEntity"></a>

```python
def reset_entity() -> None
```

##### `reset_extra_properties` <a name="reset_extra_properties" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetExtraProperties"></a>

```python
def reset_extra_properties() -> None
```

##### `reset_filter` <a name="reset_filter" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetFilter"></a>

```python
def reset_filter() -> None
```

##### `reset_ignore_alert_actions_from_payload` <a name="reset_ignore_alert_actions_from_payload" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetIgnoreAlertActionsFromPayload"></a>

```python
def reset_ignore_alert_actions_from_payload() -> None
```

##### `reset_ignore_extra_properties_from_payload` <a name="reset_ignore_extra_properties_from_payload" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetIgnoreExtraPropertiesFromPayload"></a>

```python
def reset_ignore_extra_properties_from_payload() -> None
```

##### `reset_ignore_responders_from_payload` <a name="reset_ignore_responders_from_payload" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetIgnoreRespondersFromPayload"></a>

```python
def reset_ignore_responders_from_payload() -> None
```

##### `reset_ignore_tags_from_payload` <a name="reset_ignore_tags_from_payload" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetIgnoreTagsFromPayload"></a>

```python
def reset_ignore_tags_from_payload() -> None
```

##### `reset_ignore_teams_from_payload` <a name="reset_ignore_teams_from_payload" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetIgnoreTeamsFromPayload"></a>

```python
def reset_ignore_teams_from_payload() -> None
```

##### `reset_message` <a name="reset_message" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetMessage"></a>

```python
def reset_message() -> None
```

##### `reset_note` <a name="reset_note" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetNote"></a>

```python
def reset_note() -> None
```

##### `reset_order` <a name="reset_order" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetOrder"></a>

```python
def reset_order() -> None
```

##### `reset_priority` <a name="reset_priority" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetPriority"></a>

```python
def reset_priority() -> None
```

##### `reset_responders` <a name="reset_responders" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetResponders"></a>

```python
def reset_responders() -> None
```

##### `reset_source` <a name="reset_source" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetSource"></a>

```python
def reset_source() -> None
```

##### `reset_tags` <a name="reset_tags" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetTags"></a>

```python
def reset_tags() -> None
```

##### `reset_type` <a name="reset_type" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetType"></a>

```python
def reset_type() -> None
```

##### `reset_user` <a name="reset_user" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.resetUser"></a>

```python
def reset_user() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.filter">filter</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterList">IntegrationActionCreateFilterList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.responders">responders</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersList">IntegrationActionCreateRespondersList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.alertActionsInput">alert_actions_input</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.aliasInput">alias_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.appendAttachmentsInput">append_attachments_input</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.customPriorityInput">custom_priority_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.descriptionInput">description_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.entityInput">entity_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.extraPropertiesInput">extra_properties_input</a></code> | <code>typing.Mapping[str]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.filterInput">filter_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilter">IntegrationActionCreateFilter</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.ignoreAlertActionsFromPayloadInput">ignore_alert_actions_from_payload_input</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.ignoreExtraPropertiesFromPayloadInput">ignore_extra_properties_from_payload_input</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.ignoreRespondersFromPayloadInput">ignore_responders_from_payload_input</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.ignoreTagsFromPayloadInput">ignore_tags_from_payload_input</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.ignoreTeamsFromPayloadInput">ignore_teams_from_payload_input</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.messageInput">message_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.nameInput">name_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.noteInput">note_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.orderInput">order_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.priorityInput">priority_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.respondersInput">responders_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateResponders">IntegrationActionCreateResponders</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.sourceInput">source_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.tagsInput">tags_input</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.typeInput">type_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.userInput">user_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.alertActions">alert_actions</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.alias">alias</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.appendAttachments">append_attachments</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.customPriority">custom_priority</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.description">description</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.entity">entity</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.extraProperties">extra_properties</a></code> | <code>typing.Mapping[str]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.ignoreAlertActionsFromPayload">ignore_alert_actions_from_payload</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.ignoreExtraPropertiesFromPayload">ignore_extra_properties_from_payload</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.ignoreRespondersFromPayload">ignore_responders_from_payload</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.ignoreTagsFromPayload">ignore_tags_from_payload</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.ignoreTeamsFromPayload">ignore_teams_from_payload</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.message">message</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.name">name</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.note">note</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.order">order</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.priority">priority</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.source">source</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.tags">tags</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.type">type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.user">user</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate">IntegrationActionCreate</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `filter`<sup>Required</sup> <a name="filter" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.filter"></a>

```python
filter: IntegrationActionCreateFilterList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilterList">IntegrationActionCreateFilterList</a>

---

##### `responders`<sup>Required</sup> <a name="responders" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.responders"></a>

```python
responders: IntegrationActionCreateRespondersList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersList">IntegrationActionCreateRespondersList</a>

---

##### `alert_actions_input`<sup>Optional</sup> <a name="alert_actions_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.alertActionsInput"></a>

```python
alert_actions_input: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `alias_input`<sup>Optional</sup> <a name="alias_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.aliasInput"></a>

```python
alias_input: str
```

- *Type:* str

---

##### `append_attachments_input`<sup>Optional</sup> <a name="append_attachments_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.appendAttachmentsInput"></a>

```python
append_attachments_input: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `custom_priority_input`<sup>Optional</sup> <a name="custom_priority_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.customPriorityInput"></a>

```python
custom_priority_input: str
```

- *Type:* str

---

##### `description_input`<sup>Optional</sup> <a name="description_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.descriptionInput"></a>

```python
description_input: str
```

- *Type:* str

---

##### `entity_input`<sup>Optional</sup> <a name="entity_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.entityInput"></a>

```python
entity_input: str
```

- *Type:* str

---

##### `extra_properties_input`<sup>Optional</sup> <a name="extra_properties_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.extraPropertiesInput"></a>

```python
extra_properties_input: typing.Mapping[str]
```

- *Type:* typing.Mapping[str]

---

##### `filter_input`<sup>Optional</sup> <a name="filter_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.filterInput"></a>

```python
filter_input: typing.Union[IResolvable, typing.List[IntegrationActionCreateFilter]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateFilter">IntegrationActionCreateFilter</a>]]

---

##### `ignore_alert_actions_from_payload_input`<sup>Optional</sup> <a name="ignore_alert_actions_from_payload_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.ignoreAlertActionsFromPayloadInput"></a>

```python
ignore_alert_actions_from_payload_input: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `ignore_extra_properties_from_payload_input`<sup>Optional</sup> <a name="ignore_extra_properties_from_payload_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.ignoreExtraPropertiesFromPayloadInput"></a>

```python
ignore_extra_properties_from_payload_input: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `ignore_responders_from_payload_input`<sup>Optional</sup> <a name="ignore_responders_from_payload_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.ignoreRespondersFromPayloadInput"></a>

```python
ignore_responders_from_payload_input: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `ignore_tags_from_payload_input`<sup>Optional</sup> <a name="ignore_tags_from_payload_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.ignoreTagsFromPayloadInput"></a>

```python
ignore_tags_from_payload_input: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `ignore_teams_from_payload_input`<sup>Optional</sup> <a name="ignore_teams_from_payload_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.ignoreTeamsFromPayloadInput"></a>

```python
ignore_teams_from_payload_input: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `message_input`<sup>Optional</sup> <a name="message_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.messageInput"></a>

```python
message_input: str
```

- *Type:* str

---

##### `name_input`<sup>Optional</sup> <a name="name_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.nameInput"></a>

```python
name_input: str
```

- *Type:* str

---

##### `note_input`<sup>Optional</sup> <a name="note_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.noteInput"></a>

```python
note_input: str
```

- *Type:* str

---

##### `order_input`<sup>Optional</sup> <a name="order_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.orderInput"></a>

```python
order_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `priority_input`<sup>Optional</sup> <a name="priority_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.priorityInput"></a>

```python
priority_input: str
```

- *Type:* str

---

##### `responders_input`<sup>Optional</sup> <a name="responders_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.respondersInput"></a>

```python
responders_input: typing.Union[IResolvable, typing.List[IntegrationActionCreateResponders]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateResponders">IntegrationActionCreateResponders</a>]]

---

##### `source_input`<sup>Optional</sup> <a name="source_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.sourceInput"></a>

```python
source_input: str
```

- *Type:* str

---

##### `tags_input`<sup>Optional</sup> <a name="tags_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.tagsInput"></a>

```python
tags_input: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `type_input`<sup>Optional</sup> <a name="type_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.typeInput"></a>

```python
type_input: str
```

- *Type:* str

---

##### `user_input`<sup>Optional</sup> <a name="user_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.userInput"></a>

```python
user_input: str
```

- *Type:* str

---

##### `alert_actions`<sup>Required</sup> <a name="alert_actions" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.alertActions"></a>

```python
alert_actions: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `alias`<sup>Required</sup> <a name="alias" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.alias"></a>

```python
alias: str
```

- *Type:* str

---

##### `append_attachments`<sup>Required</sup> <a name="append_attachments" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.appendAttachments"></a>

```python
append_attachments: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `custom_priority`<sup>Required</sup> <a name="custom_priority" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.customPriority"></a>

```python
custom_priority: str
```

- *Type:* str

---

##### `description`<sup>Required</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.description"></a>

```python
description: str
```

- *Type:* str

---

##### `entity`<sup>Required</sup> <a name="entity" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.entity"></a>

```python
entity: str
```

- *Type:* str

---

##### `extra_properties`<sup>Required</sup> <a name="extra_properties" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.extraProperties"></a>

```python
extra_properties: typing.Mapping[str]
```

- *Type:* typing.Mapping[str]

---

##### `ignore_alert_actions_from_payload`<sup>Required</sup> <a name="ignore_alert_actions_from_payload" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.ignoreAlertActionsFromPayload"></a>

```python
ignore_alert_actions_from_payload: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `ignore_extra_properties_from_payload`<sup>Required</sup> <a name="ignore_extra_properties_from_payload" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.ignoreExtraPropertiesFromPayload"></a>

```python
ignore_extra_properties_from_payload: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `ignore_responders_from_payload`<sup>Required</sup> <a name="ignore_responders_from_payload" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.ignoreRespondersFromPayload"></a>

```python
ignore_responders_from_payload: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `ignore_tags_from_payload`<sup>Required</sup> <a name="ignore_tags_from_payload" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.ignoreTagsFromPayload"></a>

```python
ignore_tags_from_payload: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `ignore_teams_from_payload`<sup>Required</sup> <a name="ignore_teams_from_payload" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.ignoreTeamsFromPayload"></a>

```python
ignore_teams_from_payload: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `message`<sup>Required</sup> <a name="message" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.message"></a>

```python
message: str
```

- *Type:* str

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.name"></a>

```python
name: str
```

- *Type:* str

---

##### `note`<sup>Required</sup> <a name="note" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.note"></a>

```python
note: str
```

- *Type:* str

---

##### `order`<sup>Required</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.order"></a>

```python
order: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `priority`<sup>Required</sup> <a name="priority" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.priority"></a>

```python
priority: str
```

- *Type:* str

---

##### `source`<sup>Required</sup> <a name="source" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.source"></a>

```python
source: str
```

- *Type:* str

---

##### `tags`<sup>Required</sup> <a name="tags" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.tags"></a>

```python
tags: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.type"></a>

```python
type: str
```

- *Type:* str

---

##### `user`<sup>Required</sup> <a name="user" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.user"></a>

```python
user: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, IntegrationActionCreate]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreate">IntegrationActionCreate</a>]

---


### IntegrationActionCreateRespondersList <a name="IntegrationActionCreateRespondersList" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionCreateRespondersList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> IntegrationActionCreateRespondersOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateResponders">IntegrationActionCreateResponders</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[IntegrationActionCreateResponders]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateResponders">IntegrationActionCreateResponders</a>]]

---


### IntegrationActionCreateRespondersOutputReference <a name="IntegrationActionCreateRespondersOutputReference" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionCreateRespondersOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.property.idInput">id_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.property.typeInput">type_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.property.id">id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.property.type">type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateResponders">IntegrationActionCreateResponders</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `id_input`<sup>Optional</sup> <a name="id_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.property.idInput"></a>

```python
id_input: str
```

- *Type:* str

---

##### `type_input`<sup>Optional</sup> <a name="type_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.property.typeInput"></a>

```python
type_input: str
```

- *Type:* str

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.property.id"></a>

```python
id: str
```

- *Type:* str

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.property.type"></a>

```python
type: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateRespondersOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, IntegrationActionCreateResponders]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionCreateResponders">IntegrationActionCreateResponders</a>]

---


### IntegrationActionIgnoreFilterConditionsList <a name="IntegrationActionIgnoreFilterConditionsList" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionIgnoreFilterConditionsList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> IntegrationActionIgnoreFilterConditionsOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditions">IntegrationActionIgnoreFilterConditions</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[IntegrationActionIgnoreFilterConditions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditions">IntegrationActionIgnoreFilterConditions</a>]]

---


### IntegrationActionIgnoreFilterConditionsOutputReference <a name="IntegrationActionIgnoreFilterConditionsOutputReference" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.resetExpectedValue">reset_expected_value</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.resetKey">reset_key</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.resetNot">reset_not</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.resetOrder">reset_order</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `reset_expected_value` <a name="reset_expected_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.resetExpectedValue"></a>

```python
def reset_expected_value() -> None
```

##### `reset_key` <a name="reset_key" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.resetKey"></a>

```python
def reset_key() -> None
```

##### `reset_not` <a name="reset_not" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.resetNot"></a>

```python
def reset_not() -> None
```

##### `reset_order` <a name="reset_order" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.resetOrder"></a>

```python
def reset_order() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.property.expectedValueInput">expected_value_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.property.fieldInput">field_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.property.keyInput">key_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.property.notInput">not_input</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.property.operationInput">operation_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.property.orderInput">order_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.property.expectedValue">expected_value</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.property.field">field</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.property.key">key</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.property.not">not</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.property.operation">operation</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.property.order">order</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditions">IntegrationActionIgnoreFilterConditions</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `expected_value_input`<sup>Optional</sup> <a name="expected_value_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.property.expectedValueInput"></a>

```python
expected_value_input: str
```

- *Type:* str

---

##### `field_input`<sup>Optional</sup> <a name="field_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.property.fieldInput"></a>

```python
field_input: str
```

- *Type:* str

---

##### `key_input`<sup>Optional</sup> <a name="key_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.property.keyInput"></a>

```python
key_input: str
```

- *Type:* str

---

##### `not_input`<sup>Optional</sup> <a name="not_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.property.notInput"></a>

```python
not_input: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `operation_input`<sup>Optional</sup> <a name="operation_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.property.operationInput"></a>

```python
operation_input: str
```

- *Type:* str

---

##### `order_input`<sup>Optional</sup> <a name="order_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.property.orderInput"></a>

```python
order_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `expected_value`<sup>Required</sup> <a name="expected_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.property.expectedValue"></a>

```python
expected_value: str
```

- *Type:* str

---

##### `field`<sup>Required</sup> <a name="field" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.property.field"></a>

```python
field: str
```

- *Type:* str

---

##### `key`<sup>Required</sup> <a name="key" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.property.key"></a>

```python
key: str
```

- *Type:* str

---

##### `not`<sup>Required</sup> <a name="not" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.property.not"></a>

```python
not: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `operation`<sup>Required</sup> <a name="operation" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.property.operation"></a>

```python
operation: str
```

- *Type:* str

---

##### `order`<sup>Required</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.property.order"></a>

```python
order: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, IntegrationActionIgnoreFilterConditions]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditions">IntegrationActionIgnoreFilterConditions</a>]

---


### IntegrationActionIgnoreFilterList <a name="IntegrationActionIgnoreFilterList" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionIgnoreFilterList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> IntegrationActionIgnoreFilterOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilter">IntegrationActionIgnoreFilter</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[IntegrationActionIgnoreFilter]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilter">IntegrationActionIgnoreFilter</a>]]

---


### IntegrationActionIgnoreFilterOutputReference <a name="IntegrationActionIgnoreFilterOutputReference" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionIgnoreFilterOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.putConditions">put_conditions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.resetConditions">reset_conditions</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `put_conditions` <a name="put_conditions" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.putConditions"></a>

```python
def put_conditions(
  value: typing.Union[IResolvable, typing.List[IntegrationActionIgnoreFilterConditions]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.putConditions.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditions">IntegrationActionIgnoreFilterConditions</a>]]

---

##### `reset_conditions` <a name="reset_conditions" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.resetConditions"></a>

```python
def reset_conditions() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.property.conditions">conditions</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsList">IntegrationActionIgnoreFilterConditionsList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.property.conditionsInput">conditions_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditions">IntegrationActionIgnoreFilterConditions</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.property.typeInput">type_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.property.type">type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilter">IntegrationActionIgnoreFilter</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `conditions`<sup>Required</sup> <a name="conditions" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.property.conditions"></a>

```python
conditions: IntegrationActionIgnoreFilterConditionsList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditionsList">IntegrationActionIgnoreFilterConditionsList</a>

---

##### `conditions_input`<sup>Optional</sup> <a name="conditions_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.property.conditionsInput"></a>

```python
conditions_input: typing.Union[IResolvable, typing.List[IntegrationActionIgnoreFilterConditions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterConditions">IntegrationActionIgnoreFilterConditions</a>]]

---

##### `type_input`<sup>Optional</sup> <a name="type_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.property.typeInput"></a>

```python
type_input: str
```

- *Type:* str

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.property.type"></a>

```python
type: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, IntegrationActionIgnoreFilter]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilter">IntegrationActionIgnoreFilter</a>]

---


### IntegrationActionIgnoreList <a name="IntegrationActionIgnoreList" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionIgnoreList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> IntegrationActionIgnoreOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnore">IntegrationActionIgnore</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[IntegrationActionIgnore]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnore">IntegrationActionIgnore</a>]]

---


### IntegrationActionIgnoreOutputReference <a name="IntegrationActionIgnoreOutputReference" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import integration_action

integrationAction.IntegrationActionIgnoreOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.putFilter">put_filter</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.resetFilter">reset_filter</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.resetOrder">reset_order</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.resetType">reset_type</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `put_filter` <a name="put_filter" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.putFilter"></a>

```python
def put_filter(
  value: typing.Union[IResolvable, typing.List[IntegrationActionIgnoreFilter]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.putFilter.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilter">IntegrationActionIgnoreFilter</a>]]

---

##### `reset_filter` <a name="reset_filter" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.resetFilter"></a>

```python
def reset_filter() -> None
```

##### `reset_order` <a name="reset_order" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.resetOrder"></a>

```python
def reset_order() -> None
```

##### `reset_type` <a name="reset_type" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.resetType"></a>

```python
def reset_type() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.property.filter">filter</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterList">IntegrationActionIgnoreFilterList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.property.filterInput">filter_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilter">IntegrationActionIgnoreFilter</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.property.nameInput">name_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.property.orderInput">order_input</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.property.typeInput">type_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.property.name">name</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.property.order">order</a></code> | <code>typing.Union[int, float]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.property.type">type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnore">IntegrationActionIgnore</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `filter`<sup>Required</sup> <a name="filter" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.property.filter"></a>

```python
filter: IntegrationActionIgnoreFilterList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilterList">IntegrationActionIgnoreFilterList</a>

---

##### `filter_input`<sup>Optional</sup> <a name="filter_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.property.filterInput"></a>

```python
filter_input: typing.Union[IResolvable, typing.List[IntegrationActionIgnoreFilter]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreFilter">IntegrationActionIgnoreFilter</a>]]

---

##### `name_input`<sup>Optional</sup> <a name="name_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.property.nameInput"></a>

```python
name_input: str
```

- *Type:* str

---

##### `order_input`<sup>Optional</sup> <a name="order_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.property.orderInput"></a>

```python
order_input: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `type_input`<sup>Optional</sup> <a name="type_input" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.property.typeInput"></a>

```python
type_input: str
```

- *Type:* str

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.property.name"></a>

```python
name: str
```

- *Type:* str

---

##### `order`<sup>Required</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.property.order"></a>

```python
order: typing.Union[int, float]
```

- *Type:* typing.Union[int, float]

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.property.type"></a>

```python
type: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnoreOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, IntegrationActionIgnore]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.integrationAction.IntegrationActionIgnore">IntegrationActionIgnore</a>]

---



