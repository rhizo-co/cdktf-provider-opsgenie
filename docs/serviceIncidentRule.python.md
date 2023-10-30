# `opsgenie_service_incident_rule`

Refer to the Terraform Registory for docs: [`opsgenie_service_incident_rule`](https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule).

# `serviceIncidentRule` Submodule <a name="`serviceIncidentRule` Submodule" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### ServiceIncidentRule <a name="ServiceIncidentRule" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule"></a>

Represents a {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule opsgenie_service_incident_rule}.

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import service_incident_rule

serviceIncidentRule.ServiceIncidentRule(
  scope: Construct,
  id: str,
  connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection] = None,
  count: typing.Union[typing.Union[int, float], TerraformCount] = None,
  depends_on: typing.List[ITerraformDependable] = None,
  for_each: ITerraformIterator = None,
  lifecycle: TerraformResourceLifecycle = None,
  provider: TerraformProvider = None,
  provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]] = None,
  incident_rule: typing.Union[IResolvable, typing.List[ServiceIncidentRuleIncidentRule]],
  service_id: str,
  id: str = None
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.id">id</a></code> | <code>str</code> | The scoped construct ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.connection">connection</a></code> | <code>typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.dependsOn">depends_on</a></code> | <code>typing.List[cdktf.ITerraformDependable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.provisioners">provisioners</a></code> | <code>typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.incidentRule">incident_rule</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule">ServiceIncidentRuleIncidentRule</a>]]</code> | incident_rule block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.serviceId">service_id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#service_id ServiceIncidentRule#service_id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.id">id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#id ServiceIncidentRule#id}. |

---

##### `scope`<sup>Required</sup> <a name="scope" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.id"></a>

- *Type:* str

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.connection"></a>

- *Type:* typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.count"></a>

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.dependsOn"></a>

- *Type:* typing.List[cdktf.ITerraformDependable]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.forEach"></a>

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.lifecycle"></a>

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.provider"></a>

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.provisioners"></a>

- *Type:* typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]

---

##### `incident_rule`<sup>Required</sup> <a name="incident_rule" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.incidentRule"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule">ServiceIncidentRuleIncidentRule</a>]]

incident_rule block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#incident_rule ServiceIncidentRule#incident_rule}

---

##### `service_id`<sup>Required</sup> <a name="service_id" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.serviceId"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#service_id ServiceIncidentRule#service_id}.

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.id"></a>

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#id ServiceIncidentRule#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.toString">to_string</a></code> | Returns a string representation of this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.addOverride">add_override</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.overrideLogicalId">override_logical_id</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.resetOverrideLogicalId">reset_override_logical_id</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.toMetadata">to_metadata</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.toTerraform">to_terraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.putIncidentRule">put_incident_rule</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.resetId">reset_id</a></code> | *No description.* |

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.toString"></a>

```python
def to_string() -> str
```

Returns a string representation of this construct.

##### `add_override` <a name="add_override" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.addOverride"></a>

```python
def add_override(
  path: str,
  value: typing.Any
) -> None
```

###### `path`<sup>Required</sup> <a name="path" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.addOverride.parameter.path"></a>

- *Type:* str

---

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.addOverride.parameter.value"></a>

- *Type:* typing.Any

---

##### `override_logical_id` <a name="override_logical_id" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.overrideLogicalId"></a>

```python
def override_logical_id(
  new_logical_id: str
) -> None
```

Overrides the auto-generated logical ID with a specific ID.

###### `new_logical_id`<sup>Required</sup> <a name="new_logical_id" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* str

The new logical ID to use for this stack element.

---

##### `reset_override_logical_id` <a name="reset_override_logical_id" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.resetOverrideLogicalId"></a>

```python
def reset_override_logical_id() -> None
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `to_metadata` <a name="to_metadata" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.toMetadata"></a>

```python
def to_metadata() -> typing.Any
```

##### `to_terraform` <a name="to_terraform" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.toTerraform"></a>

```python
def to_terraform() -> typing.Any
```

Adds this resource to the terraform JSON output.

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `put_incident_rule` <a name="put_incident_rule" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.putIncidentRule"></a>

```python
def put_incident_rule(
  value: typing.Union[IResolvable, typing.List[ServiceIncidentRuleIncidentRule]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.putIncidentRule.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule">ServiceIncidentRuleIncidentRule</a>]]

---

##### `reset_id` <a name="reset_id" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.resetId"></a>

```python
def reset_id() -> None
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isConstruct">is_construct</a></code> | Checks if `x` is a construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isTerraformElement">is_terraform_element</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isTerraformResource">is_terraform_resource</a></code> | *No description.* |

---

##### `is_construct` <a name="is_construct" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isConstruct"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import service_incident_rule

serviceIncidentRule.ServiceIncidentRule.is_construct(
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

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isConstruct.parameter.x"></a>

- *Type:* typing.Any

Any object.

---

##### `is_terraform_element` <a name="is_terraform_element" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isTerraformElement"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import service_incident_rule

serviceIncidentRule.ServiceIncidentRule.is_terraform_element(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isTerraformElement.parameter.x"></a>

- *Type:* typing.Any

---

##### `is_terraform_resource` <a name="is_terraform_resource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isTerraformResource"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import service_incident_rule

serviceIncidentRule.ServiceIncidentRule.is_terraform_resource(
  x: typing.Any
)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isTerraformResource.parameter.x"></a>

- *Type:* typing.Any

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.node">node</a></code> | <code>constructs.Node</code> | The tree node. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.cdktfStack">cdktf_stack</a></code> | <code>cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.friendlyUniqueId">friendly_unique_id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.terraformMetaArguments">terraform_meta_arguments</a></code> | <code>typing.Mapping[typing.Any]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.terraformResourceType">terraform_resource_type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.terraformGeneratorMetadata">terraform_generator_metadata</a></code> | <code>cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.connection">connection</a></code> | <code>typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.dependsOn">depends_on</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.provisioners">provisioners</a></code> | <code>typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.incidentRule">incident_rule</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList">ServiceIncidentRuleIncidentRuleList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.idInput">id_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.incidentRuleInput">incident_rule_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule">ServiceIncidentRuleIncidentRule</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.serviceIdInput">service_id_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.id">id</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.serviceId">service_id</a></code> | <code>str</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.node"></a>

```python
node: Node
```

- *Type:* constructs.Node

The tree node.

---

##### `cdktf_stack`<sup>Required</sup> <a name="cdktf_stack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.cdktfStack"></a>

```python
cdktf_stack: TerraformStack
```

- *Type:* cdktf.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `friendly_unique_id`<sup>Required</sup> <a name="friendly_unique_id" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.friendlyUniqueId"></a>

```python
friendly_unique_id: str
```

- *Type:* str

---

##### `terraform_meta_arguments`<sup>Required</sup> <a name="terraform_meta_arguments" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.terraformMetaArguments"></a>

```python
terraform_meta_arguments: typing.Mapping[typing.Any]
```

- *Type:* typing.Mapping[typing.Any]

---

##### `terraform_resource_type`<sup>Required</sup> <a name="terraform_resource_type" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.terraformResourceType"></a>

```python
terraform_resource_type: str
```

- *Type:* str

---

##### `terraform_generator_metadata`<sup>Optional</sup> <a name="terraform_generator_metadata" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.terraformGeneratorMetadata"></a>

```python
terraform_generator_metadata: TerraformProviderGeneratorMetadata
```

- *Type:* cdktf.TerraformProviderGeneratorMetadata

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.connection"></a>

```python
connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection]
```

- *Type:* typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.count"></a>

```python
count: typing.Union[typing.Union[int, float], TerraformCount]
```

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.dependsOn"></a>

```python
depends_on: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.forEach"></a>

```python
for_each: ITerraformIterator
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.lifecycle"></a>

```python
lifecycle: TerraformResourceLifecycle
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.provider"></a>

```python
provider: TerraformProvider
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.provisioners"></a>

```python
provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]]
```

- *Type:* typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]

---

##### `incident_rule`<sup>Required</sup> <a name="incident_rule" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.incidentRule"></a>

```python
incident_rule: ServiceIncidentRuleIncidentRuleList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList">ServiceIncidentRuleIncidentRuleList</a>

---

##### `id_input`<sup>Optional</sup> <a name="id_input" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.idInput"></a>

```python
id_input: str
```

- *Type:* str

---

##### `incident_rule_input`<sup>Optional</sup> <a name="incident_rule_input" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.incidentRuleInput"></a>

```python
incident_rule_input: typing.Union[IResolvable, typing.List[ServiceIncidentRuleIncidentRule]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule">ServiceIncidentRuleIncidentRule</a>]]

---

##### `service_id_input`<sup>Optional</sup> <a name="service_id_input" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.serviceIdInput"></a>

```python
service_id_input: str
```

- *Type:* str

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.id"></a>

```python
id: str
```

- *Type:* str

---

##### `service_id`<sup>Required</sup> <a name="service_id" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.serviceId"></a>

```python
service_id: str
```

- *Type:* str

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.tfResourceType">tfResourceType</a></code> | <code>str</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.tfResourceType"></a>

```python
tfResourceType: str
```

- *Type:* str

---

## Structs <a name="Structs" id="Structs"></a>

### ServiceIncidentRuleConfig <a name="ServiceIncidentRuleConfig" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import service_incident_rule

serviceIncidentRule.ServiceIncidentRuleConfig(
  connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection] = None,
  count: typing.Union[typing.Union[int, float], TerraformCount] = None,
  depends_on: typing.List[ITerraformDependable] = None,
  for_each: ITerraformIterator = None,
  lifecycle: TerraformResourceLifecycle = None,
  provider: TerraformProvider = None,
  provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]] = None,
  incident_rule: typing.Union[IResolvable, typing.List[ServiceIncidentRuleIncidentRule]],
  service_id: str,
  id: str = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.connection">connection</a></code> | <code>typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.count">count</a></code> | <code>typing.Union[typing.Union[int, float], cdktf.TerraformCount]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.dependsOn">depends_on</a></code> | <code>typing.List[cdktf.ITerraformDependable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.forEach">for_each</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.provisioners">provisioners</a></code> | <code>typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.incidentRule">incident_rule</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule">ServiceIncidentRuleIncidentRule</a>]]</code> | incident_rule block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.serviceId">service_id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#service_id ServiceIncidentRule#service_id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.id">id</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#id ServiceIncidentRule#id}. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.connection"></a>

```python
connection: typing.Union[SSHProvisionerConnection, WinrmProvisionerConnection]
```

- *Type:* typing.Union[cdktf.SSHProvisionerConnection, cdktf.WinrmProvisionerConnection]

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.count"></a>

```python
count: typing.Union[typing.Union[int, float], TerraformCount]
```

- *Type:* typing.Union[typing.Union[int, float], cdktf.TerraformCount]

---

##### `depends_on`<sup>Optional</sup> <a name="depends_on" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.dependsOn"></a>

```python
depends_on: typing.List[ITerraformDependable]
```

- *Type:* typing.List[cdktf.ITerraformDependable]

---

##### `for_each`<sup>Optional</sup> <a name="for_each" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.forEach"></a>

```python
for_each: ITerraformIterator
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.lifecycle"></a>

```python
lifecycle: TerraformResourceLifecycle
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.provider"></a>

```python
provider: TerraformProvider
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.provisioners"></a>

```python
provisioners: typing.List[typing.Union[FileProvisioner, LocalExecProvisioner, RemoteExecProvisioner]]
```

- *Type:* typing.List[typing.Union[cdktf.FileProvisioner, cdktf.LocalExecProvisioner, cdktf.RemoteExecProvisioner]]

---

##### `incident_rule`<sup>Required</sup> <a name="incident_rule" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.incidentRule"></a>

```python
incident_rule: typing.Union[IResolvable, typing.List[ServiceIncidentRuleIncidentRule]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule">ServiceIncidentRuleIncidentRule</a>]]

incident_rule block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#incident_rule ServiceIncidentRule#incident_rule}

---

##### `service_id`<sup>Required</sup> <a name="service_id" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.serviceId"></a>

```python
service_id: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#service_id ServiceIncidentRule#service_id}.

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.id"></a>

```python
id: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#id ServiceIncidentRule#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

### ServiceIncidentRuleIncidentRule <a name="ServiceIncidentRuleIncidentRule" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import service_incident_rule

serviceIncidentRule.ServiceIncidentRuleIncidentRule(
  incident_properties: typing.Union[IResolvable, typing.List[ServiceIncidentRuleIncidentRuleIncidentProperties]],
  condition_match_type: str = None,
  conditions: typing.Union[IResolvable, typing.List[ServiceIncidentRuleIncidentRuleConditions]] = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule.property.incidentProperties">incident_properties</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties">ServiceIncidentRuleIncidentRuleIncidentProperties</a>]]</code> | incident_properties block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule.property.conditionMatchType">condition_match_type</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#condition_match_type ServiceIncidentRule#condition_match_type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule.property.conditions">conditions</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions">ServiceIncidentRuleIncidentRuleConditions</a>]]</code> | conditions block. |

---

##### `incident_properties`<sup>Required</sup> <a name="incident_properties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule.property.incidentProperties"></a>

```python
incident_properties: typing.Union[IResolvable, typing.List[ServiceIncidentRuleIncidentRuleIncidentProperties]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties">ServiceIncidentRuleIncidentRuleIncidentProperties</a>]]

incident_properties block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#incident_properties ServiceIncidentRule#incident_properties}

---

##### `condition_match_type`<sup>Optional</sup> <a name="condition_match_type" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule.property.conditionMatchType"></a>

```python
condition_match_type: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#condition_match_type ServiceIncidentRule#condition_match_type}.

---

##### `conditions`<sup>Optional</sup> <a name="conditions" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule.property.conditions"></a>

```python
conditions: typing.Union[IResolvable, typing.List[ServiceIncidentRuleIncidentRuleConditions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions">ServiceIncidentRuleIncidentRuleConditions</a>]]

conditions block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#conditions ServiceIncidentRule#conditions}

---

### ServiceIncidentRuleIncidentRuleConditions <a name="ServiceIncidentRuleIncidentRuleConditions" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import service_incident_rule

serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions(
  field: str,
  operation: str,
  expected_value: str = None,
  key: str = None,
  not: typing.Union[bool, IResolvable] = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.field">field</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#field ServiceIncidentRule#field}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.operation">operation</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#operation ServiceIncidentRule#operation}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.expectedValue">expected_value</a></code> | <code>str</code> | User defined value that will be compared with alert field according to the operation. Default value is empty string. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.key">key</a></code> | <code>str</code> | If 'field' is set as 'extra-properties', key could be used for key-value pair. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.not">not</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Indicates behaviour of the given operation. Default value is false. |

---

##### `field`<sup>Required</sup> <a name="field" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.field"></a>

```python
field: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#field ServiceIncidentRule#field}.

---

##### `operation`<sup>Required</sup> <a name="operation" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.operation"></a>

```python
operation: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#operation ServiceIncidentRule#operation}.

---

##### `expected_value`<sup>Optional</sup> <a name="expected_value" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.expectedValue"></a>

```python
expected_value: str
```

- *Type:* str

User defined value that will be compared with alert field according to the operation. Default value is empty string.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#expected_value ServiceIncidentRule#expected_value}

---

##### `key`<sup>Optional</sup> <a name="key" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.key"></a>

```python
key: str
```

- *Type:* str

If 'field' is set as 'extra-properties', key could be used for key-value pair.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#key ServiceIncidentRule#key}

---

##### `not`<sup>Optional</sup> <a name="not" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.not"></a>

```python
not: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

Indicates behaviour of the given operation. Default value is false.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#not ServiceIncidentRule#not}

---

### ServiceIncidentRuleIncidentRuleIncidentProperties <a name="ServiceIncidentRuleIncidentRuleIncidentProperties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import service_incident_rule

serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties(
  message: str,
  priority: str,
  stakeholder_properties: typing.Union[IResolvable, typing.List[ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties]],
  description: str = None,
  details: typing.Mapping[str] = None,
  tags: typing.List[str] = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.message">message</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#message ServiceIncidentRule#message}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.priority">priority</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#priority ServiceIncidentRule#priority}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.stakeholderProperties">stakeholder_properties</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties">ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties</a>]]</code> | stakeholder_properties block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.description">description</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#description ServiceIncidentRule#description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.details">details</a></code> | <code>typing.Mapping[str]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#details ServiceIncidentRule#details}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.tags">tags</a></code> | <code>typing.List[str]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#tags ServiceIncidentRule#tags}. |

---

##### `message`<sup>Required</sup> <a name="message" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.message"></a>

```python
message: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#message ServiceIncidentRule#message}.

---

##### `priority`<sup>Required</sup> <a name="priority" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.priority"></a>

```python
priority: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#priority ServiceIncidentRule#priority}.

---

##### `stakeholder_properties`<sup>Required</sup> <a name="stakeholder_properties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.stakeholderProperties"></a>

```python
stakeholder_properties: typing.Union[IResolvable, typing.List[ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties">ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties</a>]]

stakeholder_properties block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#stakeholder_properties ServiceIncidentRule#stakeholder_properties}

---

##### `description`<sup>Optional</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.description"></a>

```python
description: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#description ServiceIncidentRule#description}.

---

##### `details`<sup>Optional</sup> <a name="details" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.details"></a>

```python
details: typing.Mapping[str]
```

- *Type:* typing.Mapping[str]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#details ServiceIncidentRule#details}.

---

##### `tags`<sup>Optional</sup> <a name="tags" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.tags"></a>

```python
tags: typing.List[str]
```

- *Type:* typing.List[str]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#tags ServiceIncidentRule#tags}.

---

### ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties <a name="ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import service_incident_rule

serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties(
  message: str,
  description: str = None,
  enable: typing.Union[bool, IResolvable] = None
)
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties.property.message">message</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#message ServiceIncidentRule#message}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties.property.description">description</a></code> | <code>str</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#description ServiceIncidentRule#description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties.property.enable">enable</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#enable ServiceIncidentRule#enable}. |

---

##### `message`<sup>Required</sup> <a name="message" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties.property.message"></a>

```python
message: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#message ServiceIncidentRule#message}.

---

##### `description`<sup>Optional</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties.property.description"></a>

```python
description: str
```

- *Type:* str

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#description ServiceIncidentRule#description}.

---

##### `enable`<sup>Optional</sup> <a name="enable" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties.property.enable"></a>

```python
enable: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#enable ServiceIncidentRule#enable}.

---

## Classes <a name="Classes" id="Classes"></a>

### ServiceIncidentRuleIncidentRuleConditionsList <a name="ServiceIncidentRuleIncidentRuleConditionsList" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import service_incident_rule

serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> ServiceIncidentRuleIncidentRuleConditionsOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions">ServiceIncidentRuleIncidentRuleConditions</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[ServiceIncidentRuleIncidentRuleConditions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions">ServiceIncidentRuleIncidentRuleConditions</a>]]

---


### ServiceIncidentRuleIncidentRuleConditionsOutputReference <a name="ServiceIncidentRuleIncidentRuleConditionsOutputReference" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import service_incident_rule

serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.resetExpectedValue">reset_expected_value</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.resetKey">reset_key</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.resetNot">reset_not</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `reset_expected_value` <a name="reset_expected_value" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.resetExpectedValue"></a>

```python
def reset_expected_value() -> None
```

##### `reset_key` <a name="reset_key" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.resetKey"></a>

```python
def reset_key() -> None
```

##### `reset_not` <a name="reset_not" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.resetNot"></a>

```python
def reset_not() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.expectedValueInput">expected_value_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.fieldInput">field_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.keyInput">key_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.notInput">not_input</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.operationInput">operation_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.expectedValue">expected_value</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.field">field</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.key">key</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.not">not</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.operation">operation</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions">ServiceIncidentRuleIncidentRuleConditions</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `expected_value_input`<sup>Optional</sup> <a name="expected_value_input" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.expectedValueInput"></a>

```python
expected_value_input: str
```

- *Type:* str

---

##### `field_input`<sup>Optional</sup> <a name="field_input" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.fieldInput"></a>

```python
field_input: str
```

- *Type:* str

---

##### `key_input`<sup>Optional</sup> <a name="key_input" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.keyInput"></a>

```python
key_input: str
```

- *Type:* str

---

##### `not_input`<sup>Optional</sup> <a name="not_input" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.notInput"></a>

```python
not_input: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `operation_input`<sup>Optional</sup> <a name="operation_input" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.operationInput"></a>

```python
operation_input: str
```

- *Type:* str

---

##### `expected_value`<sup>Required</sup> <a name="expected_value" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.expectedValue"></a>

```python
expected_value: str
```

- *Type:* str

---

##### `field`<sup>Required</sup> <a name="field" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.field"></a>

```python
field: str
```

- *Type:* str

---

##### `key`<sup>Required</sup> <a name="key" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.key"></a>

```python
key: str
```

- *Type:* str

---

##### `not`<sup>Required</sup> <a name="not" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.not"></a>

```python
not: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `operation`<sup>Required</sup> <a name="operation" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.operation"></a>

```python
operation: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, ServiceIncidentRuleIncidentRuleConditions]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions">ServiceIncidentRuleIncidentRuleConditions</a>]

---


### ServiceIncidentRuleIncidentRuleIncidentPropertiesList <a name="ServiceIncidentRuleIncidentRuleIncidentPropertiesList" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import service_incident_rule

serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties">ServiceIncidentRuleIncidentRuleIncidentProperties</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[ServiceIncidentRuleIncidentRuleIncidentProperties]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties">ServiceIncidentRuleIncidentRuleIncidentProperties</a>]]

---


### ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference <a name="ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import service_incident_rule

serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.putStakeholderProperties">put_stakeholder_properties</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.resetDescription">reset_description</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.resetDetails">reset_details</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.resetTags">reset_tags</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `put_stakeholder_properties` <a name="put_stakeholder_properties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.putStakeholderProperties"></a>

```python
def put_stakeholder_properties(
  value: typing.Union[IResolvable, typing.List[ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.putStakeholderProperties.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties">ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties</a>]]

---

##### `reset_description` <a name="reset_description" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.resetDescription"></a>

```python
def reset_description() -> None
```

##### `reset_details` <a name="reset_details" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.resetDetails"></a>

```python
def reset_details() -> None
```

##### `reset_tags` <a name="reset_tags" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.resetTags"></a>

```python
def reset_tags() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.stakeholderProperties">stakeholder_properties</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList">ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.descriptionInput">description_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.detailsInput">details_input</a></code> | <code>typing.Mapping[str]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.messageInput">message_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.priorityInput">priority_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.stakeholderPropertiesInput">stakeholder_properties_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties">ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.tagsInput">tags_input</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.description">description</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.details">details</a></code> | <code>typing.Mapping[str]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.message">message</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.priority">priority</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.tags">tags</a></code> | <code>typing.List[str]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties">ServiceIncidentRuleIncidentRuleIncidentProperties</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `stakeholder_properties`<sup>Required</sup> <a name="stakeholder_properties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.stakeholderProperties"></a>

```python
stakeholder_properties: ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList">ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList</a>

---

##### `description_input`<sup>Optional</sup> <a name="description_input" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.descriptionInput"></a>

```python
description_input: str
```

- *Type:* str

---

##### `details_input`<sup>Optional</sup> <a name="details_input" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.detailsInput"></a>

```python
details_input: typing.Mapping[str]
```

- *Type:* typing.Mapping[str]

---

##### `message_input`<sup>Optional</sup> <a name="message_input" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.messageInput"></a>

```python
message_input: str
```

- *Type:* str

---

##### `priority_input`<sup>Optional</sup> <a name="priority_input" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.priorityInput"></a>

```python
priority_input: str
```

- *Type:* str

---

##### `stakeholder_properties_input`<sup>Optional</sup> <a name="stakeholder_properties_input" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.stakeholderPropertiesInput"></a>

```python
stakeholder_properties_input: typing.Union[IResolvable, typing.List[ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties">ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties</a>]]

---

##### `tags_input`<sup>Optional</sup> <a name="tags_input" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.tagsInput"></a>

```python
tags_input: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `description`<sup>Required</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.description"></a>

```python
description: str
```

- *Type:* str

---

##### `details`<sup>Required</sup> <a name="details" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.details"></a>

```python
details: typing.Mapping[str]
```

- *Type:* typing.Mapping[str]

---

##### `message`<sup>Required</sup> <a name="message" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.message"></a>

```python
message: str
```

- *Type:* str

---

##### `priority`<sup>Required</sup> <a name="priority" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.priority"></a>

```python
priority: str
```

- *Type:* str

---

##### `tags`<sup>Required</sup> <a name="tags" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.tags"></a>

```python
tags: typing.List[str]
```

- *Type:* typing.List[str]

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, ServiceIncidentRuleIncidentRuleIncidentProperties]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties">ServiceIncidentRuleIncidentRuleIncidentProperties</a>]

---


### ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList <a name="ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import service_incident_rule

serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties">ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties">ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties</a>]]

---


### ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference <a name="ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import service_incident_rule

serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.resetDescription">reset_description</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.resetEnable">reset_enable</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `reset_description` <a name="reset_description" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.resetDescription"></a>

```python
def reset_description() -> None
```

##### `reset_enable` <a name="reset_enable" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.resetEnable"></a>

```python
def reset_enable() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.descriptionInput">description_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.enableInput">enable_input</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.messageInput">message_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.description">description</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.enable">enable</a></code> | <code>typing.Union[bool, cdktf.IResolvable]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.message">message</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties">ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `description_input`<sup>Optional</sup> <a name="description_input" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.descriptionInput"></a>

```python
description_input: str
```

- *Type:* str

---

##### `enable_input`<sup>Optional</sup> <a name="enable_input" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.enableInput"></a>

```python
enable_input: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `message_input`<sup>Optional</sup> <a name="message_input" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.messageInput"></a>

```python
message_input: str
```

- *Type:* str

---

##### `description`<sup>Required</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.description"></a>

```python
description: str
```

- *Type:* str

---

##### `enable`<sup>Required</sup> <a name="enable" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.enable"></a>

```python
enable: typing.Union[bool, IResolvable]
```

- *Type:* typing.Union[bool, cdktf.IResolvable]

---

##### `message`<sup>Required</sup> <a name="message" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.message"></a>

```python
message: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties">ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties</a>]

---


### ServiceIncidentRuleIncidentRuleList <a name="ServiceIncidentRuleIncidentRuleList" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import service_incident_rule

serviceIncidentRule.ServiceIncidentRuleIncidentRuleList(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  wraps_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.Initializer.parameter.wrapsSet">wraps_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `wraps_set`<sup>Required</sup> <a name="wraps_set" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.get">get</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.get"></a>

```python
def get(
  index: typing.Union[int, float]
) -> ServiceIncidentRuleIncidentRuleOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.get.parameter.index"></a>

- *Type:* typing.Union[int, float]

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule">ServiceIncidentRuleIncidentRule</a>]]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, typing.List[ServiceIncidentRuleIncidentRule]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule">ServiceIncidentRuleIncidentRule</a>]]

---


### ServiceIncidentRuleIncidentRuleOutputReference <a name="ServiceIncidentRuleIncidentRuleOutputReference" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer"></a>

```python
from rhizo-co_cdktf_provider_opsgenie import service_incident_rule

serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference(
  terraform_resource: IInterpolatingParent,
  terraform_attribute: str,
  complex_object_index: typing.Union[int, float],
  complex_object_is_from_set: bool
)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.terraformResource">terraform_resource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.terraformAttribute">terraform_attribute</a></code> | <code>str</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.complexObjectIndex">complex_object_index</a></code> | <code>typing.Union[int, float]</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.complexObjectIsFromSet">complex_object_is_from_set</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraform_resource`<sup>Required</sup> <a name="terraform_resource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* str

The attribute on the parent resource this class is referencing.

---

##### `complex_object_index`<sup>Required</sup> <a name="complex_object_index" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* typing.Union[int, float]

the index of this item in the list.

---

##### `complex_object_is_from_set`<sup>Required</sup> <a name="complex_object_is_from_set" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.computeFqn">compute_fqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getAnyMapAttribute">get_any_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getBooleanAttribute">get_boolean_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getBooleanMapAttribute">get_boolean_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getListAttribute">get_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberAttribute">get_number_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberListAttribute">get_number_list_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberMapAttribute">get_number_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getStringAttribute">get_string_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getStringMapAttribute">get_string_map_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.interpolationForAttribute">interpolation_for_attribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.toString">to_string</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.putConditions">put_conditions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.putIncidentProperties">put_incident_properties</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.resetConditionMatchType">reset_condition_match_type</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.resetConditions">reset_conditions</a></code> | *No description.* |

---

##### `compute_fqn` <a name="compute_fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.computeFqn"></a>

```python
def compute_fqn() -> str
```

##### `get_any_map_attribute` <a name="get_any_map_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getAnyMapAttribute"></a>

```python
def get_any_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Any]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_attribute` <a name="get_boolean_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getBooleanAttribute"></a>

```python
def get_boolean_attribute(
  terraform_attribute: str
) -> IResolvable
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_boolean_map_attribute` <a name="get_boolean_map_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getBooleanMapAttribute"></a>

```python
def get_boolean_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[bool]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_list_attribute` <a name="get_list_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getListAttribute"></a>

```python
def get_list_attribute(
  terraform_attribute: str
) -> typing.List[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_attribute` <a name="get_number_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberAttribute"></a>

```python
def get_number_attribute(
  terraform_attribute: str
) -> typing.Union[int, float]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_list_attribute` <a name="get_number_list_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberListAttribute"></a>

```python
def get_number_list_attribute(
  terraform_attribute: str
) -> typing.List[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_number_map_attribute` <a name="get_number_map_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberMapAttribute"></a>

```python
def get_number_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[typing.Union[int, float]]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_attribute` <a name="get_string_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getStringAttribute"></a>

```python
def get_string_attribute(
  terraform_attribute: str
) -> str
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `get_string_map_attribute` <a name="get_string_map_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getStringMapAttribute"></a>

```python
def get_string_map_attribute(
  terraform_attribute: str
) -> typing.Mapping[str]
```

###### `terraform_attribute`<sup>Required</sup> <a name="terraform_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* str

---

##### `interpolation_for_attribute` <a name="interpolation_for_attribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.interpolationForAttribute"></a>

```python
def interpolation_for_attribute(
  property: str
) -> IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* str

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.resolve"></a>

```python
def resolve(
  _context: IResolveContext
) -> typing.Any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `to_string` <a name="to_string" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.toString"></a>

```python
def to_string() -> str
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `put_conditions` <a name="put_conditions" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.putConditions"></a>

```python
def put_conditions(
  value: typing.Union[IResolvable, typing.List[ServiceIncidentRuleIncidentRuleConditions]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.putConditions.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions">ServiceIncidentRuleIncidentRuleConditions</a>]]

---

##### `put_incident_properties` <a name="put_incident_properties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.putIncidentProperties"></a>

```python
def put_incident_properties(
  value: typing.Union[IResolvable, typing.List[ServiceIncidentRuleIncidentRuleIncidentProperties]]
) -> None
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.putIncidentProperties.parameter.value"></a>

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties">ServiceIncidentRuleIncidentRuleIncidentProperties</a>]]

---

##### `reset_condition_match_type` <a name="reset_condition_match_type" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.resetConditionMatchType"></a>

```python
def reset_condition_match_type() -> None
```

##### `reset_conditions` <a name="reset_conditions" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.resetConditions"></a>

```python
def reset_conditions() -> None
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.creationStack">creation_stack</a></code> | <code>typing.List[str]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.fqn">fqn</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditions">conditions</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList">ServiceIncidentRuleIncidentRuleConditionsList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.incidentProperties">incident_properties</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList">ServiceIncidentRuleIncidentRuleIncidentPropertiesList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditionMatchTypeInput">condition_match_type_input</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditionsInput">conditions_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions">ServiceIncidentRuleIncidentRuleConditions</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.incidentPropertiesInput">incident_properties_input</a></code> | <code>typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties">ServiceIncidentRuleIncidentRuleIncidentProperties</a>]]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditionMatchType">condition_match_type</a></code> | <code>str</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.internalValue">internal_value</a></code> | <code>typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule">ServiceIncidentRuleIncidentRule</a>]</code> | *No description.* |

---

##### `creation_stack`<sup>Required</sup> <a name="creation_stack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.creationStack"></a>

```python
creation_stack: typing.List[str]
```

- *Type:* typing.List[str]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.fqn"></a>

```python
fqn: str
```

- *Type:* str

---

##### `conditions`<sup>Required</sup> <a name="conditions" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditions"></a>

```python
conditions: ServiceIncidentRuleIncidentRuleConditionsList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList">ServiceIncidentRuleIncidentRuleConditionsList</a>

---

##### `incident_properties`<sup>Required</sup> <a name="incident_properties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.incidentProperties"></a>

```python
incident_properties: ServiceIncidentRuleIncidentRuleIncidentPropertiesList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList">ServiceIncidentRuleIncidentRuleIncidentPropertiesList</a>

---

##### `condition_match_type_input`<sup>Optional</sup> <a name="condition_match_type_input" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditionMatchTypeInput"></a>

```python
condition_match_type_input: str
```

- *Type:* str

---

##### `conditions_input`<sup>Optional</sup> <a name="conditions_input" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditionsInput"></a>

```python
conditions_input: typing.Union[IResolvable, typing.List[ServiceIncidentRuleIncidentRuleConditions]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions">ServiceIncidentRuleIncidentRuleConditions</a>]]

---

##### `incident_properties_input`<sup>Optional</sup> <a name="incident_properties_input" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.incidentPropertiesInput"></a>

```python
incident_properties_input: typing.Union[IResolvable, typing.List[ServiceIncidentRuleIncidentRuleIncidentProperties]]
```

- *Type:* typing.Union[cdktf.IResolvable, typing.List[<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties">ServiceIncidentRuleIncidentRuleIncidentProperties</a>]]

---

##### `condition_match_type`<sup>Required</sup> <a name="condition_match_type" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditionMatchType"></a>

```python
condition_match_type: str
```

- *Type:* str

---

##### `internal_value`<sup>Optional</sup> <a name="internal_value" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.internalValue"></a>

```python
internal_value: typing.Union[IResolvable, ServiceIncidentRuleIncidentRule]
```

- *Type:* typing.Union[cdktf.IResolvable, <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule">ServiceIncidentRuleIncidentRule</a>]

---



