# `data_opsgenie_escalation`

Refer to the Terraform Registory for docs: [`data_opsgenie_escalation`](https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation).

# `dataOpsgenieEscalation` Submodule <a name="`dataOpsgenieEscalation` Submodule" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### DataOpsgenieEscalation <a name="DataOpsgenieEscalation" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation"></a>

Represents a {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation opsgenie_escalation}.

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/dataopsgenieescalation"

dataopsgenieescalation.NewDataOpsgenieEscalation(scope Construct, id *string, config DataOpsgenieEscalationConfig) DataOpsgenieEscalation
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.scope">scope</a></code> | <code>github.com/aws/constructs-go/constructs/v10.Construct</code> | The scope in which to define this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.id">id</a></code> | <code>*string</code> | The scoped construct ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.config">config</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig">DataOpsgenieEscalationConfig</a></code> | *No description.* |

---

##### `scope`<sup>Required</sup> <a name="scope" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.scope"></a>

- *Type:* github.com/aws/constructs-go/constructs/v10.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.id"></a>

- *Type:* *string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Required</sup> <a name="config" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.config"></a>

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig">DataOpsgenieEscalationConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.toString">ToString</a></code> | Returns a string representation of this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.addOverride">AddOverride</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.overrideLogicalId">OverrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetOverrideLogicalId">ResetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.toMetadata">ToMetadata</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.toTerraform">ToTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.putRepeat">PutRepeat</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.putRules">PutRules</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetDescription">ResetDescription</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetId">ResetId</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetOwnerTeamId">ResetOwnerTeamId</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetRepeat">ResetRepeat</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetRules">ResetRules</a></code> | *No description.* |

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.toString"></a>

```go
func ToString() *string
```

Returns a string representation of this construct.

##### `AddOverride` <a name="AddOverride" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.addOverride"></a>

```go
func AddOverride(path *string, value interface{})
```

###### `path`<sup>Required</sup> <a name="path" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.addOverride.parameter.path"></a>

- *Type:* *string

---

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.addOverride.parameter.value"></a>

- *Type:* interface{}

---

##### `OverrideLogicalId` <a name="OverrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.overrideLogicalId"></a>

```go
func OverrideLogicalId(newLogicalId *string)
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* *string

The new logical ID to use for this stack element.

---

##### `ResetOverrideLogicalId` <a name="ResetOverrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetOverrideLogicalId"></a>

```go
func ResetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `ToMetadata` <a name="ToMetadata" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.toMetadata"></a>

```go
func ToMetadata() interface{}
```

##### `ToTerraform` <a name="ToTerraform" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.toTerraform"></a>

```go
func ToTerraform() interface{}
```

Adds this resource to the terraform JSON output.

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `PutRepeat` <a name="PutRepeat" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.putRepeat"></a>

```go
func PutRepeat(value interface{})
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.putRepeat.parameter.value"></a>

- *Type:* interface{}

---

##### `PutRules` <a name="PutRules" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.putRules"></a>

```go
func PutRules(value interface{})
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.putRules.parameter.value"></a>

- *Type:* interface{}

---

##### `ResetDescription` <a name="ResetDescription" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetDescription"></a>

```go
func ResetDescription()
```

##### `ResetId` <a name="ResetId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetId"></a>

```go
func ResetId()
```

##### `ResetOwnerTeamId` <a name="ResetOwnerTeamId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetOwnerTeamId"></a>

```go
func ResetOwnerTeamId()
```

##### `ResetRepeat` <a name="ResetRepeat" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetRepeat"></a>

```go
func ResetRepeat()
```

##### `ResetRules` <a name="ResetRules" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetRules"></a>

```go
func ResetRules()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.isConstruct">IsConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.isTerraformElement">IsTerraformElement</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.isTerraformDataSource">IsTerraformDataSource</a></code> | *No description.* |

---

##### `IsConstruct` <a name="IsConstruct" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.isConstruct"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/dataopsgenieescalation"

dataopsgenieescalation.DataOpsgenieEscalation_IsConstruct(x interface{}) *bool
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

- *Type:* interface{}

Any object.

---

##### `IsTerraformElement` <a name="IsTerraformElement" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.isTerraformElement"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/dataopsgenieescalation"

dataopsgenieescalation.DataOpsgenieEscalation_IsTerraformElement(x interface{}) *bool
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.isTerraformElement.parameter.x"></a>

- *Type:* interface{}

---

##### `IsTerraformDataSource` <a name="IsTerraformDataSource" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.isTerraformDataSource"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/dataopsgenieescalation"

dataopsgenieescalation.DataOpsgenieEscalation_IsTerraformDataSource(x interface{}) *bool
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.isTerraformDataSource.parameter.x"></a>

- *Type:* interface{}

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.node">Node</a></code> | <code>github.com/aws/constructs-go/constructs/v10.Node</code> | The tree node. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.cdktfStack">CdktfStack</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.friendlyUniqueId">FriendlyUniqueId</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.terraformMetaArguments">TerraformMetaArguments</a></code> | <code>*map[string]interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.terraformResourceType">TerraformResourceType</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.terraformGeneratorMetadata">TerraformGeneratorMetadata</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.count">Count</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.dependsOn">DependsOn</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.forEach">ForEach</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.lifecycle">Lifecycle</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.provider">Provider</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.repeat">Repeat</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList">DataOpsgenieEscalationRepeatList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.rules">Rules</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList">DataOpsgenieEscalationRulesList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.descriptionInput">DescriptionInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.idInput">IdInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.nameInput">NameInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.ownerTeamIdInput">OwnerTeamIdInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.repeatInput">RepeatInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.rulesInput">RulesInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.description">Description</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.id">Id</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.name">Name</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.ownerTeamId">OwnerTeamId</a></code> | <code>*string</code> | *No description.* |

---

##### `Node`<sup>Required</sup> <a name="Node" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.node"></a>

```go
func Node() Node
```

- *Type:* github.com/aws/constructs-go/constructs/v10.Node

The tree node.

---

##### `CdktfStack`<sup>Required</sup> <a name="CdktfStack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.cdktfStack"></a>

```go
func CdktfStack() TerraformStack
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformStack

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `FriendlyUniqueId`<sup>Required</sup> <a name="FriendlyUniqueId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.friendlyUniqueId"></a>

```go
func FriendlyUniqueId() *string
```

- *Type:* *string

---

##### `TerraformMetaArguments`<sup>Required</sup> <a name="TerraformMetaArguments" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.terraformMetaArguments"></a>

```go
func TerraformMetaArguments() *map[string]interface{}
```

- *Type:* *map[string]interface{}

---

##### `TerraformResourceType`<sup>Required</sup> <a name="TerraformResourceType" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.terraformResourceType"></a>

```go
func TerraformResourceType() *string
```

- *Type:* *string

---

##### `TerraformGeneratorMetadata`<sup>Optional</sup> <a name="TerraformGeneratorMetadata" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.terraformGeneratorMetadata"></a>

```go
func TerraformGeneratorMetadata() TerraformProviderGeneratorMetadata
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProviderGeneratorMetadata

---

##### `Count`<sup>Optional</sup> <a name="Count" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.count"></a>

```go
func Count() interface{}
```

- *Type:* interface{}

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.dependsOn"></a>

```go
func DependsOn() *[]*string
```

- *Type:* *[]*string

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.forEach"></a>

```go
func ForEach() ITerraformIterator
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.lifecycle"></a>

```go
func Lifecycle() TerraformResourceLifecycle
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.provider"></a>

```go
func Provider() TerraformProvider
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider

---

##### `Repeat`<sup>Required</sup> <a name="Repeat" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.repeat"></a>

```go
func Repeat() DataOpsgenieEscalationRepeatList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList">DataOpsgenieEscalationRepeatList</a>

---

##### `Rules`<sup>Required</sup> <a name="Rules" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.rules"></a>

```go
func Rules() DataOpsgenieEscalationRulesList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList">DataOpsgenieEscalationRulesList</a>

---

##### `DescriptionInput`<sup>Optional</sup> <a name="DescriptionInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.descriptionInput"></a>

```go
func DescriptionInput() *string
```

- *Type:* *string

---

##### `IdInput`<sup>Optional</sup> <a name="IdInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.idInput"></a>

```go
func IdInput() *string
```

- *Type:* *string

---

##### `NameInput`<sup>Optional</sup> <a name="NameInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.nameInput"></a>

```go
func NameInput() *string
```

- *Type:* *string

---

##### `OwnerTeamIdInput`<sup>Optional</sup> <a name="OwnerTeamIdInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.ownerTeamIdInput"></a>

```go
func OwnerTeamIdInput() *string
```

- *Type:* *string

---

##### `RepeatInput`<sup>Optional</sup> <a name="RepeatInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.repeatInput"></a>

```go
func RepeatInput() interface{}
```

- *Type:* interface{}

---

##### `RulesInput`<sup>Optional</sup> <a name="RulesInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.rulesInput"></a>

```go
func RulesInput() interface{}
```

- *Type:* interface{}

---

##### `Description`<sup>Required</sup> <a name="Description" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.description"></a>

```go
func Description() *string
```

- *Type:* *string

---

##### `Id`<sup>Required</sup> <a name="Id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.id"></a>

```go
func Id() *string
```

- *Type:* *string

---

##### `Name`<sup>Required</sup> <a name="Name" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.name"></a>

```go
func Name() *string
```

- *Type:* *string

---

##### `OwnerTeamId`<sup>Required</sup> <a name="OwnerTeamId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.ownerTeamId"></a>

```go
func OwnerTeamId() *string
```

- *Type:* *string

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.tfResourceType">TfResourceType</a></code> | <code>*string</code> | *No description.* |

---

##### `TfResourceType`<sup>Required</sup> <a name="TfResourceType" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.tfResourceType"></a>

```go
func TfResourceType() *string
```

- *Type:* *string

---

## Structs <a name="Structs" id="Structs"></a>

### DataOpsgenieEscalationConfig <a name="DataOpsgenieEscalationConfig" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/dataopsgenieescalation"

&dataopsgenieescalation.DataOpsgenieEscalationConfig {
	Connection: interface{},
	Count: interface{},
	DependsOn: *[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable,
	ForEach: github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator,
	Lifecycle: github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle,
	Provider: github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider,
	Provisioners: *[]interface{},
	Name: *string,
	Description: *string,
	Id: *string,
	OwnerTeamId: *string,
	Repeat: interface{},
	Rules: interface{},
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.connection">Connection</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.count">Count</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.dependsOn">DependsOn</a></code> | <code>*[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.forEach">ForEach</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.lifecycle">Lifecycle</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.provider">Provider</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.provisioners">Provisioners</a></code> | <code>*[]interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.name">Name</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#name DataOpsgenieEscalation#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.description">Description</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#description DataOpsgenieEscalation#description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.id">Id</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#id DataOpsgenieEscalation#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.ownerTeamId">OwnerTeamId</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#owner_team_id DataOpsgenieEscalation#owner_team_id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.repeat">Repeat</a></code> | <code>interface{}</code> | repeat block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.rules">Rules</a></code> | <code>interface{}</code> | rules block. |

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.connection"></a>

```go
Connection interface{}
```

- *Type:* interface{}

---

##### `Count`<sup>Optional</sup> <a name="Count" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.count"></a>

```go
Count interface{}
```

- *Type:* interface{}

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.dependsOn"></a>

```go
DependsOn *[]ITerraformDependable
```

- *Type:* *[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.forEach"></a>

```go
ForEach ITerraformIterator
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.lifecycle"></a>

```go
Lifecycle TerraformResourceLifecycle
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.provider"></a>

```go
Provider TerraformProvider
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.provisioners"></a>

```go
Provisioners *[]interface{}
```

- *Type:* *[]interface{}

---

##### `Name`<sup>Required</sup> <a name="Name" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.name"></a>

```go
Name *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#name DataOpsgenieEscalation#name}.

---

##### `Description`<sup>Optional</sup> <a name="Description" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.description"></a>

```go
Description *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#description DataOpsgenieEscalation#description}.

---

##### `Id`<sup>Optional</sup> <a name="Id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.id"></a>

```go
Id *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#id DataOpsgenieEscalation#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `OwnerTeamId`<sup>Optional</sup> <a name="OwnerTeamId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.ownerTeamId"></a>

```go
OwnerTeamId *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#owner_team_id DataOpsgenieEscalation#owner_team_id}.

---

##### `Repeat`<sup>Optional</sup> <a name="Repeat" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.repeat"></a>

```go
Repeat interface{}
```

- *Type:* interface{}

repeat block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#repeat DataOpsgenieEscalation#repeat}

---

##### `Rules`<sup>Optional</sup> <a name="Rules" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.rules"></a>

```go
Rules interface{}
```

- *Type:* interface{}

rules block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#rules DataOpsgenieEscalation#rules}

---

### DataOpsgenieEscalationRepeat <a name="DataOpsgenieEscalationRepeat" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/dataopsgenieescalation"

&dataopsgenieescalation.DataOpsgenieEscalationRepeat {
	CloseAlertAfterAll: interface{},
	Count: *f64,
	ResetRecipientStates: interface{},
	WaitInterval: *f64,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat.property.closeAlertAfterAll">CloseAlertAfterAll</a></code> | <code>interface{}</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#close_alert_after_all DataOpsgenieEscalation#close_alert_after_all}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat.property.count">Count</a></code> | <code>*f64</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#count DataOpsgenieEscalation#count}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat.property.resetRecipientStates">ResetRecipientStates</a></code> | <code>interface{}</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#reset_recipient_states DataOpsgenieEscalation#reset_recipient_states}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat.property.waitInterval">WaitInterval</a></code> | <code>*f64</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#wait_interval DataOpsgenieEscalation#wait_interval}. |

---

##### `CloseAlertAfterAll`<sup>Optional</sup> <a name="CloseAlertAfterAll" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat.property.closeAlertAfterAll"></a>

```go
CloseAlertAfterAll interface{}
```

- *Type:* interface{}

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#close_alert_after_all DataOpsgenieEscalation#close_alert_after_all}.

---

##### `Count`<sup>Optional</sup> <a name="Count" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat.property.count"></a>

```go
Count *f64
```

- *Type:* *f64

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#count DataOpsgenieEscalation#count}.

---

##### `ResetRecipientStates`<sup>Optional</sup> <a name="ResetRecipientStates" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat.property.resetRecipientStates"></a>

```go
ResetRecipientStates interface{}
```

- *Type:* interface{}

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#reset_recipient_states DataOpsgenieEscalation#reset_recipient_states}.

---

##### `WaitInterval`<sup>Optional</sup> <a name="WaitInterval" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat.property.waitInterval"></a>

```go
WaitInterval *f64
```

- *Type:* *f64

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#wait_interval DataOpsgenieEscalation#wait_interval}.

---

### DataOpsgenieEscalationRules <a name="DataOpsgenieEscalationRules" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/dataopsgenieescalation"

&dataopsgenieescalation.DataOpsgenieEscalationRules {
	Condition: *string,
	Delay: *f64,
	NotifyType: *string,
	Recipient: interface{},
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules.property.condition">Condition</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#condition DataOpsgenieEscalation#condition}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules.property.delay">Delay</a></code> | <code>*f64</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#delay DataOpsgenieEscalation#delay}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules.property.notifyType">NotifyType</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#notify_type DataOpsgenieEscalation#notify_type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules.property.recipient">Recipient</a></code> | <code>interface{}</code> | recipient block. |

---

##### `Condition`<sup>Required</sup> <a name="Condition" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules.property.condition"></a>

```go
Condition *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#condition DataOpsgenieEscalation#condition}.

---

##### `Delay`<sup>Required</sup> <a name="Delay" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules.property.delay"></a>

```go
Delay *f64
```

- *Type:* *f64

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#delay DataOpsgenieEscalation#delay}.

---

##### `NotifyType`<sup>Required</sup> <a name="NotifyType" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules.property.notifyType"></a>

```go
NotifyType *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#notify_type DataOpsgenieEscalation#notify_type}.

---

##### `Recipient`<sup>Required</sup> <a name="Recipient" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules.property.recipient"></a>

```go
Recipient interface{}
```

- *Type:* interface{}

recipient block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#recipient DataOpsgenieEscalation#recipient}

---

### DataOpsgenieEscalationRulesRecipient <a name="DataOpsgenieEscalationRulesRecipient" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/dataopsgenieescalation"

&dataopsgenieescalation.DataOpsgenieEscalationRulesRecipient {
	Id: *string,
	Type: *string,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient.property.id">Id</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#id DataOpsgenieEscalation#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient.property.type">Type</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#type DataOpsgenieEscalation#type}. |

---

##### `Id`<sup>Optional</sup> <a name="Id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient.property.id"></a>

```go
Id *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#id DataOpsgenieEscalation#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `Type`<sup>Optional</sup> <a name="Type" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient.property.type"></a>

```go
Type *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#type DataOpsgenieEscalation#type}.

---

## Classes <a name="Classes" id="Classes"></a>

### DataOpsgenieEscalationRepeatList <a name="DataOpsgenieEscalationRepeatList" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/dataopsgenieescalation"

dataopsgenieescalation.NewDataOpsgenieEscalationRepeatList(terraformResource IInterpolatingParent, terraformAttribute *string, wrapsSet *bool) DataOpsgenieEscalationRepeatList
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.Initializer.parameter.wrapsSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.get">Get</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.get"></a>

```go
func Get(index *f64) DataOpsgenieEscalationRepeatOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.get.parameter.index"></a>

- *Type:* *f64

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### DataOpsgenieEscalationRepeatOutputReference <a name="DataOpsgenieEscalationRepeatOutputReference" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/dataopsgenieescalation"

dataopsgenieescalation.NewDataOpsgenieEscalationRepeatOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string, complexObjectIndex *f64, complexObjectIsFromSet *bool) DataOpsgenieEscalationRepeatOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>*f64</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* *f64

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resetCloseAlertAfterAll">ResetCloseAlertAfterAll</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resetCount">ResetCount</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resetResetRecipientStates">ResetResetRecipientStates</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resetWaitInterval">ResetWaitInterval</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetCloseAlertAfterAll` <a name="ResetCloseAlertAfterAll" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resetCloseAlertAfterAll"></a>

```go
func ResetCloseAlertAfterAll()
```

##### `ResetCount` <a name="ResetCount" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resetCount"></a>

```go
func ResetCount()
```

##### `ResetResetRecipientStates` <a name="ResetResetRecipientStates" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resetResetRecipientStates"></a>

```go
func ResetResetRecipientStates()
```

##### `ResetWaitInterval` <a name="ResetWaitInterval" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resetWaitInterval"></a>

```go
func ResetWaitInterval()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.closeAlertAfterAllInput">CloseAlertAfterAllInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.countInput">CountInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.resetRecipientStatesInput">ResetRecipientStatesInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.waitIntervalInput">WaitIntervalInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.closeAlertAfterAll">CloseAlertAfterAll</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.count">Count</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.resetRecipientStates">ResetRecipientStates</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.waitInterval">WaitInterval</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `CloseAlertAfterAllInput`<sup>Optional</sup> <a name="CloseAlertAfterAllInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.closeAlertAfterAllInput"></a>

```go
func CloseAlertAfterAllInput() interface{}
```

- *Type:* interface{}

---

##### `CountInput`<sup>Optional</sup> <a name="CountInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.countInput"></a>

```go
func CountInput() *f64
```

- *Type:* *f64

---

##### `ResetRecipientStatesInput`<sup>Optional</sup> <a name="ResetRecipientStatesInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.resetRecipientStatesInput"></a>

```go
func ResetRecipientStatesInput() interface{}
```

- *Type:* interface{}

---

##### `WaitIntervalInput`<sup>Optional</sup> <a name="WaitIntervalInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.waitIntervalInput"></a>

```go
func WaitIntervalInput() *f64
```

- *Type:* *f64

---

##### `CloseAlertAfterAll`<sup>Required</sup> <a name="CloseAlertAfterAll" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.closeAlertAfterAll"></a>

```go
func CloseAlertAfterAll() interface{}
```

- *Type:* interface{}

---

##### `Count`<sup>Required</sup> <a name="Count" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.count"></a>

```go
func Count() *f64
```

- *Type:* *f64

---

##### `ResetRecipientStates`<sup>Required</sup> <a name="ResetRecipientStates" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.resetRecipientStates"></a>

```go
func ResetRecipientStates() interface{}
```

- *Type:* interface{}

---

##### `WaitInterval`<sup>Required</sup> <a name="WaitInterval" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.waitInterval"></a>

```go
func WaitInterval() *f64
```

- *Type:* *f64

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### DataOpsgenieEscalationRulesList <a name="DataOpsgenieEscalationRulesList" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/dataopsgenieescalation"

dataopsgenieescalation.NewDataOpsgenieEscalationRulesList(terraformResource IInterpolatingParent, terraformAttribute *string, wrapsSet *bool) DataOpsgenieEscalationRulesList
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.Initializer.parameter.wrapsSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.get">Get</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.get"></a>

```go
func Get(index *f64) DataOpsgenieEscalationRulesOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.get.parameter.index"></a>

- *Type:* *f64

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### DataOpsgenieEscalationRulesOutputReference <a name="DataOpsgenieEscalationRulesOutputReference" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/dataopsgenieescalation"

dataopsgenieescalation.NewDataOpsgenieEscalationRulesOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string, complexObjectIndex *f64, complexObjectIsFromSet *bool) DataOpsgenieEscalationRulesOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>*f64</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* *f64

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.putRecipient">PutRecipient</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `PutRecipient` <a name="PutRecipient" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.putRecipient"></a>

```go
func PutRecipient(value interface{})
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.putRecipient.parameter.value"></a>

- *Type:* interface{}

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.recipient">Recipient</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList">DataOpsgenieEscalationRulesRecipientList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.conditionInput">ConditionInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.delayInput">DelayInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.notifyTypeInput">NotifyTypeInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.recipientInput">RecipientInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.condition">Condition</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.delay">Delay</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.notifyType">NotifyType</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `Recipient`<sup>Required</sup> <a name="Recipient" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.recipient"></a>

```go
func Recipient() DataOpsgenieEscalationRulesRecipientList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList">DataOpsgenieEscalationRulesRecipientList</a>

---

##### `ConditionInput`<sup>Optional</sup> <a name="ConditionInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.conditionInput"></a>

```go
func ConditionInput() *string
```

- *Type:* *string

---

##### `DelayInput`<sup>Optional</sup> <a name="DelayInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.delayInput"></a>

```go
func DelayInput() *f64
```

- *Type:* *f64

---

##### `NotifyTypeInput`<sup>Optional</sup> <a name="NotifyTypeInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.notifyTypeInput"></a>

```go
func NotifyTypeInput() *string
```

- *Type:* *string

---

##### `RecipientInput`<sup>Optional</sup> <a name="RecipientInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.recipientInput"></a>

```go
func RecipientInput() interface{}
```

- *Type:* interface{}

---

##### `Condition`<sup>Required</sup> <a name="Condition" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.condition"></a>

```go
func Condition() *string
```

- *Type:* *string

---

##### `Delay`<sup>Required</sup> <a name="Delay" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.delay"></a>

```go
func Delay() *f64
```

- *Type:* *f64

---

##### `NotifyType`<sup>Required</sup> <a name="NotifyType" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.notifyType"></a>

```go
func NotifyType() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### DataOpsgenieEscalationRulesRecipientList <a name="DataOpsgenieEscalationRulesRecipientList" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/dataopsgenieescalation"

dataopsgenieescalation.NewDataOpsgenieEscalationRulesRecipientList(terraformResource IInterpolatingParent, terraformAttribute *string, wrapsSet *bool) DataOpsgenieEscalationRulesRecipientList
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.Initializer.parameter.wrapsSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.get">Get</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.get"></a>

```go
func Get(index *f64) DataOpsgenieEscalationRulesRecipientOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.get.parameter.index"></a>

- *Type:* *f64

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### DataOpsgenieEscalationRulesRecipientOutputReference <a name="DataOpsgenieEscalationRulesRecipientOutputReference" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/dataopsgenieescalation"

dataopsgenieescalation.NewDataOpsgenieEscalationRulesRecipientOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string, complexObjectIndex *f64, complexObjectIsFromSet *bool) DataOpsgenieEscalationRulesRecipientOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>*f64</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* *f64

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.resetId">ResetId</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.resetType">ResetType</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetId` <a name="ResetId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.resetId"></a>

```go
func ResetId()
```

##### `ResetType` <a name="ResetType" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.resetType"></a>

```go
func ResetType()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.idInput">IdInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.typeInput">TypeInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.id">Id</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.type">Type</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `IdInput`<sup>Optional</sup> <a name="IdInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.idInput"></a>

```go
func IdInput() *string
```

- *Type:* *string

---

##### `TypeInput`<sup>Optional</sup> <a name="TypeInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.typeInput"></a>

```go
func TypeInput() *string
```

- *Type:* *string

---

##### `Id`<sup>Required</sup> <a name="Id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.id"></a>

```go
func Id() *string
```

- *Type:* *string

---

##### `Type`<sup>Required</sup> <a name="Type" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.type"></a>

```go
func Type() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---



