# `opsgenie_service_incident_rule`

Refer to the Terraform Registory for docs: [`opsgenie_service_incident_rule`](https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule).

# `serviceIncidentRule` Submodule <a name="`serviceIncidentRule` Submodule" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### ServiceIncidentRule <a name="ServiceIncidentRule" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule"></a>

Represents a {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule opsgenie_service_incident_rule}.

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/serviceincidentrule"

serviceincidentrule.NewServiceIncidentRule(scope Construct, id *string, config ServiceIncidentRuleConfig) ServiceIncidentRule
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.scope">scope</a></code> | <code>github.com/aws/constructs-go/constructs/v10.Construct</code> | The scope in which to define this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.id">id</a></code> | <code>*string</code> | The scoped construct ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.config">config</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig">ServiceIncidentRuleConfig</a></code> | *No description.* |

---

##### `scope`<sup>Required</sup> <a name="scope" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.scope"></a>

- *Type:* github.com/aws/constructs-go/constructs/v10.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.id"></a>

- *Type:* *string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Required</sup> <a name="config" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.config"></a>

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig">ServiceIncidentRuleConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.toString">ToString</a></code> | Returns a string representation of this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.addOverride">AddOverride</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.overrideLogicalId">OverrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.resetOverrideLogicalId">ResetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.toMetadata">ToMetadata</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.toTerraform">ToTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.putIncidentRule">PutIncidentRule</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.resetId">ResetId</a></code> | *No description.* |

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.toString"></a>

```go
func ToString() *string
```

Returns a string representation of this construct.

##### `AddOverride` <a name="AddOverride" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.addOverride"></a>

```go
func AddOverride(path *string, value interface{})
```

###### `path`<sup>Required</sup> <a name="path" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.addOverride.parameter.path"></a>

- *Type:* *string

---

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.addOverride.parameter.value"></a>

- *Type:* interface{}

---

##### `OverrideLogicalId` <a name="OverrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.overrideLogicalId"></a>

```go
func OverrideLogicalId(newLogicalId *string)
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* *string

The new logical ID to use for this stack element.

---

##### `ResetOverrideLogicalId` <a name="ResetOverrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.resetOverrideLogicalId"></a>

```go
func ResetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `ToMetadata` <a name="ToMetadata" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.toMetadata"></a>

```go
func ToMetadata() interface{}
```

##### `ToTerraform` <a name="ToTerraform" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.toTerraform"></a>

```go
func ToTerraform() interface{}
```

Adds this resource to the terraform JSON output.

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `PutIncidentRule` <a name="PutIncidentRule" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.putIncidentRule"></a>

```go
func PutIncidentRule(value interface{})
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.putIncidentRule.parameter.value"></a>

- *Type:* interface{}

---

##### `ResetId` <a name="ResetId" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.resetId"></a>

```go
func ResetId()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isConstruct">IsConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isTerraformElement">IsTerraformElement</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isTerraformResource">IsTerraformResource</a></code> | *No description.* |

---

##### `IsConstruct` <a name="IsConstruct" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isConstruct"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/serviceincidentrule"

serviceincidentrule.ServiceIncidentRule_IsConstruct(x interface{}) *bool
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

- *Type:* interface{}

Any object.

---

##### `IsTerraformElement` <a name="IsTerraformElement" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isTerraformElement"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/serviceincidentrule"

serviceincidentrule.ServiceIncidentRule_IsTerraformElement(x interface{}) *bool
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isTerraformElement.parameter.x"></a>

- *Type:* interface{}

---

##### `IsTerraformResource` <a name="IsTerraformResource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isTerraformResource"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/serviceincidentrule"

serviceincidentrule.ServiceIncidentRule_IsTerraformResource(x interface{}) *bool
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isTerraformResource.parameter.x"></a>

- *Type:* interface{}

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.node">Node</a></code> | <code>github.com/aws/constructs-go/constructs/v10.Node</code> | The tree node. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.cdktfStack">CdktfStack</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.friendlyUniqueId">FriendlyUniqueId</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.terraformMetaArguments">TerraformMetaArguments</a></code> | <code>*map[string]interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.terraformResourceType">TerraformResourceType</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.terraformGeneratorMetadata">TerraformGeneratorMetadata</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.connection">Connection</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.count">Count</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.dependsOn">DependsOn</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.forEach">ForEach</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.lifecycle">Lifecycle</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.provider">Provider</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.provisioners">Provisioners</a></code> | <code>*[]interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.incidentRule">IncidentRule</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList">ServiceIncidentRuleIncidentRuleList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.idInput">IdInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.incidentRuleInput">IncidentRuleInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.serviceIdInput">ServiceIdInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.id">Id</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.serviceId">ServiceId</a></code> | <code>*string</code> | *No description.* |

---

##### `Node`<sup>Required</sup> <a name="Node" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.node"></a>

```go
func Node() Node
```

- *Type:* github.com/aws/constructs-go/constructs/v10.Node

The tree node.

---

##### `CdktfStack`<sup>Required</sup> <a name="CdktfStack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.cdktfStack"></a>

```go
func CdktfStack() TerraformStack
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformStack

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `FriendlyUniqueId`<sup>Required</sup> <a name="FriendlyUniqueId" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.friendlyUniqueId"></a>

```go
func FriendlyUniqueId() *string
```

- *Type:* *string

---

##### `TerraformMetaArguments`<sup>Required</sup> <a name="TerraformMetaArguments" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.terraformMetaArguments"></a>

```go
func TerraformMetaArguments() *map[string]interface{}
```

- *Type:* *map[string]interface{}

---

##### `TerraformResourceType`<sup>Required</sup> <a name="TerraformResourceType" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.terraformResourceType"></a>

```go
func TerraformResourceType() *string
```

- *Type:* *string

---

##### `TerraformGeneratorMetadata`<sup>Optional</sup> <a name="TerraformGeneratorMetadata" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.terraformGeneratorMetadata"></a>

```go
func TerraformGeneratorMetadata() TerraformProviderGeneratorMetadata
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProviderGeneratorMetadata

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.connection"></a>

```go
func Connection() interface{}
```

- *Type:* interface{}

---

##### `Count`<sup>Optional</sup> <a name="Count" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.count"></a>

```go
func Count() interface{}
```

- *Type:* interface{}

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.dependsOn"></a>

```go
func DependsOn() *[]*string
```

- *Type:* *[]*string

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.forEach"></a>

```go
func ForEach() ITerraformIterator
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.lifecycle"></a>

```go
func Lifecycle() TerraformResourceLifecycle
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.provider"></a>

```go
func Provider() TerraformProvider
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.provisioners"></a>

```go
func Provisioners() *[]interface{}
```

- *Type:* *[]interface{}

---

##### `IncidentRule`<sup>Required</sup> <a name="IncidentRule" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.incidentRule"></a>

```go
func IncidentRule() ServiceIncidentRuleIncidentRuleList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList">ServiceIncidentRuleIncidentRuleList</a>

---

##### `IdInput`<sup>Optional</sup> <a name="IdInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.idInput"></a>

```go
func IdInput() *string
```

- *Type:* *string

---

##### `IncidentRuleInput`<sup>Optional</sup> <a name="IncidentRuleInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.incidentRuleInput"></a>

```go
func IncidentRuleInput() interface{}
```

- *Type:* interface{}

---

##### `ServiceIdInput`<sup>Optional</sup> <a name="ServiceIdInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.serviceIdInput"></a>

```go
func ServiceIdInput() *string
```

- *Type:* *string

---

##### `Id`<sup>Required</sup> <a name="Id" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.id"></a>

```go
func Id() *string
```

- *Type:* *string

---

##### `ServiceId`<sup>Required</sup> <a name="ServiceId" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.serviceId"></a>

```go
func ServiceId() *string
```

- *Type:* *string

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.tfResourceType">TfResourceType</a></code> | <code>*string</code> | *No description.* |

---

##### `TfResourceType`<sup>Required</sup> <a name="TfResourceType" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.tfResourceType"></a>

```go
func TfResourceType() *string
```

- *Type:* *string

---

## Structs <a name="Structs" id="Structs"></a>

### ServiceIncidentRuleConfig <a name="ServiceIncidentRuleConfig" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/serviceincidentrule"

&serviceincidentrule.ServiceIncidentRuleConfig {
	Connection: interface{},
	Count: interface{},
	DependsOn: *[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable,
	ForEach: github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator,
	Lifecycle: github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle,
	Provider: github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider,
	Provisioners: *[]interface{},
	IncidentRule: interface{},
	ServiceId: *string,
	Id: *string,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.connection">Connection</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.count">Count</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.dependsOn">DependsOn</a></code> | <code>*[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.forEach">ForEach</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.lifecycle">Lifecycle</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.provider">Provider</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.provisioners">Provisioners</a></code> | <code>*[]interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.incidentRule">IncidentRule</a></code> | <code>interface{}</code> | incident_rule block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.serviceId">ServiceId</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#service_id ServiceIncidentRule#service_id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.id">Id</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#id ServiceIncidentRule#id}. |

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.connection"></a>

```go
Connection interface{}
```

- *Type:* interface{}

---

##### `Count`<sup>Optional</sup> <a name="Count" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.count"></a>

```go
Count interface{}
```

- *Type:* interface{}

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.dependsOn"></a>

```go
DependsOn *[]ITerraformDependable
```

- *Type:* *[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.forEach"></a>

```go
ForEach ITerraformIterator
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.lifecycle"></a>

```go
Lifecycle TerraformResourceLifecycle
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.provider"></a>

```go
Provider TerraformProvider
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.provisioners"></a>

```go
Provisioners *[]interface{}
```

- *Type:* *[]interface{}

---

##### `IncidentRule`<sup>Required</sup> <a name="IncidentRule" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.incidentRule"></a>

```go
IncidentRule interface{}
```

- *Type:* interface{}

incident_rule block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#incident_rule ServiceIncidentRule#incident_rule}

---

##### `ServiceId`<sup>Required</sup> <a name="ServiceId" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.serviceId"></a>

```go
ServiceId *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#service_id ServiceIncidentRule#service_id}.

---

##### `Id`<sup>Optional</sup> <a name="Id" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.id"></a>

```go
Id *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#id ServiceIncidentRule#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

### ServiceIncidentRuleIncidentRule <a name="ServiceIncidentRuleIncidentRule" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/serviceincidentrule"

&serviceincidentrule.ServiceIncidentRuleIncidentRule {
	IncidentProperties: interface{},
	ConditionMatchType: *string,
	Conditions: interface{},
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule.property.incidentProperties">IncidentProperties</a></code> | <code>interface{}</code> | incident_properties block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule.property.conditionMatchType">ConditionMatchType</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#condition_match_type ServiceIncidentRule#condition_match_type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule.property.conditions">Conditions</a></code> | <code>interface{}</code> | conditions block. |

---

##### `IncidentProperties`<sup>Required</sup> <a name="IncidentProperties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule.property.incidentProperties"></a>

```go
IncidentProperties interface{}
```

- *Type:* interface{}

incident_properties block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#incident_properties ServiceIncidentRule#incident_properties}

---

##### `ConditionMatchType`<sup>Optional</sup> <a name="ConditionMatchType" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule.property.conditionMatchType"></a>

```go
ConditionMatchType *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#condition_match_type ServiceIncidentRule#condition_match_type}.

---

##### `Conditions`<sup>Optional</sup> <a name="Conditions" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule.property.conditions"></a>

```go
Conditions interface{}
```

- *Type:* interface{}

conditions block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#conditions ServiceIncidentRule#conditions}

---

### ServiceIncidentRuleIncidentRuleConditions <a name="ServiceIncidentRuleIncidentRuleConditions" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/serviceincidentrule"

&serviceincidentrule.ServiceIncidentRuleIncidentRuleConditions {
	Field: *string,
	Operation: *string,
	ExpectedValue: *string,
	Key: *string,
	Not: interface{},
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.field">Field</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#field ServiceIncidentRule#field}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.operation">Operation</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#operation ServiceIncidentRule#operation}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.expectedValue">ExpectedValue</a></code> | <code>*string</code> | User defined value that will be compared with alert field according to the operation. Default value is empty string. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.key">Key</a></code> | <code>*string</code> | If 'field' is set as 'extra-properties', key could be used for key-value pair. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.not">Not</a></code> | <code>interface{}</code> | Indicates behaviour of the given operation. Default value is false. |

---

##### `Field`<sup>Required</sup> <a name="Field" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.field"></a>

```go
Field *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#field ServiceIncidentRule#field}.

---

##### `Operation`<sup>Required</sup> <a name="Operation" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.operation"></a>

```go
Operation *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#operation ServiceIncidentRule#operation}.

---

##### `ExpectedValue`<sup>Optional</sup> <a name="ExpectedValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.expectedValue"></a>

```go
ExpectedValue *string
```

- *Type:* *string

User defined value that will be compared with alert field according to the operation. Default value is empty string.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#expected_value ServiceIncidentRule#expected_value}

---

##### `Key`<sup>Optional</sup> <a name="Key" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.key"></a>

```go
Key *string
```

- *Type:* *string

If 'field' is set as 'extra-properties', key could be used for key-value pair.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#key ServiceIncidentRule#key}

---

##### `Not`<sup>Optional</sup> <a name="Not" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.not"></a>

```go
Not interface{}
```

- *Type:* interface{}

Indicates behaviour of the given operation. Default value is false.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#not ServiceIncidentRule#not}

---

### ServiceIncidentRuleIncidentRuleIncidentProperties <a name="ServiceIncidentRuleIncidentRuleIncidentProperties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/serviceincidentrule"

&serviceincidentrule.ServiceIncidentRuleIncidentRuleIncidentProperties {
	Message: *string,
	Priority: *string,
	StakeholderProperties: interface{},
	Description: *string,
	Details: *map[string]*string,
	Tags: *[]*string,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.message">Message</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#message ServiceIncidentRule#message}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.priority">Priority</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#priority ServiceIncidentRule#priority}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.stakeholderProperties">StakeholderProperties</a></code> | <code>interface{}</code> | stakeholder_properties block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.description">Description</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#description ServiceIncidentRule#description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.details">Details</a></code> | <code>*map[string]*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#details ServiceIncidentRule#details}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.tags">Tags</a></code> | <code>*[]*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#tags ServiceIncidentRule#tags}. |

---

##### `Message`<sup>Required</sup> <a name="Message" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.message"></a>

```go
Message *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#message ServiceIncidentRule#message}.

---

##### `Priority`<sup>Required</sup> <a name="Priority" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.priority"></a>

```go
Priority *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#priority ServiceIncidentRule#priority}.

---

##### `StakeholderProperties`<sup>Required</sup> <a name="StakeholderProperties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.stakeholderProperties"></a>

```go
StakeholderProperties interface{}
```

- *Type:* interface{}

stakeholder_properties block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#stakeholder_properties ServiceIncidentRule#stakeholder_properties}

---

##### `Description`<sup>Optional</sup> <a name="Description" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.description"></a>

```go
Description *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#description ServiceIncidentRule#description}.

---

##### `Details`<sup>Optional</sup> <a name="Details" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.details"></a>

```go
Details *map[string]*string
```

- *Type:* *map[string]*string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#details ServiceIncidentRule#details}.

---

##### `Tags`<sup>Optional</sup> <a name="Tags" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.tags"></a>

```go
Tags *[]*string
```

- *Type:* *[]*string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#tags ServiceIncidentRule#tags}.

---

### ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties <a name="ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/serviceincidentrule"

&serviceincidentrule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties {
	Message: *string,
	Description: *string,
	Enable: interface{},
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties.property.message">Message</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#message ServiceIncidentRule#message}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties.property.description">Description</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#description ServiceIncidentRule#description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties.property.enable">Enable</a></code> | <code>interface{}</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#enable ServiceIncidentRule#enable}. |

---

##### `Message`<sup>Required</sup> <a name="Message" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties.property.message"></a>

```go
Message *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#message ServiceIncidentRule#message}.

---

##### `Description`<sup>Optional</sup> <a name="Description" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties.property.description"></a>

```go
Description *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#description ServiceIncidentRule#description}.

---

##### `Enable`<sup>Optional</sup> <a name="Enable" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties.property.enable"></a>

```go
Enable interface{}
```

- *Type:* interface{}

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#enable ServiceIncidentRule#enable}.

---

## Classes <a name="Classes" id="Classes"></a>

### ServiceIncidentRuleIncidentRuleConditionsList <a name="ServiceIncidentRuleIncidentRuleConditionsList" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/serviceincidentrule"

serviceincidentrule.NewServiceIncidentRuleIncidentRuleConditionsList(terraformResource IInterpolatingParent, terraformAttribute *string, wrapsSet *bool) ServiceIncidentRuleIncidentRuleConditionsList
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.Initializer.parameter.wrapsSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.get">Get</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.get"></a>

```go
func Get(index *f64) ServiceIncidentRuleIncidentRuleConditionsOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.get.parameter.index"></a>

- *Type:* *f64

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### ServiceIncidentRuleIncidentRuleConditionsOutputReference <a name="ServiceIncidentRuleIncidentRuleConditionsOutputReference" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/serviceincidentrule"

serviceincidentrule.NewServiceIncidentRuleIncidentRuleConditionsOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string, complexObjectIndex *f64, complexObjectIsFromSet *bool) ServiceIncidentRuleIncidentRuleConditionsOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>*f64</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* *f64

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.resetExpectedValue">ResetExpectedValue</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.resetKey">ResetKey</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.resetNot">ResetNot</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetExpectedValue` <a name="ResetExpectedValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.resetExpectedValue"></a>

```go
func ResetExpectedValue()
```

##### `ResetKey` <a name="ResetKey" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.resetKey"></a>

```go
func ResetKey()
```

##### `ResetNot` <a name="ResetNot" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.resetNot"></a>

```go
func ResetNot()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.expectedValueInput">ExpectedValueInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.fieldInput">FieldInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.keyInput">KeyInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.notInput">NotInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.operationInput">OperationInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.expectedValue">ExpectedValue</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.field">Field</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.key">Key</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.not">Not</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.operation">Operation</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `ExpectedValueInput`<sup>Optional</sup> <a name="ExpectedValueInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.expectedValueInput"></a>

```go
func ExpectedValueInput() *string
```

- *Type:* *string

---

##### `FieldInput`<sup>Optional</sup> <a name="FieldInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.fieldInput"></a>

```go
func FieldInput() *string
```

- *Type:* *string

---

##### `KeyInput`<sup>Optional</sup> <a name="KeyInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.keyInput"></a>

```go
func KeyInput() *string
```

- *Type:* *string

---

##### `NotInput`<sup>Optional</sup> <a name="NotInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.notInput"></a>

```go
func NotInput() interface{}
```

- *Type:* interface{}

---

##### `OperationInput`<sup>Optional</sup> <a name="OperationInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.operationInput"></a>

```go
func OperationInput() *string
```

- *Type:* *string

---

##### `ExpectedValue`<sup>Required</sup> <a name="ExpectedValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.expectedValue"></a>

```go
func ExpectedValue() *string
```

- *Type:* *string

---

##### `Field`<sup>Required</sup> <a name="Field" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.field"></a>

```go
func Field() *string
```

- *Type:* *string

---

##### `Key`<sup>Required</sup> <a name="Key" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.key"></a>

```go
func Key() *string
```

- *Type:* *string

---

##### `Not`<sup>Required</sup> <a name="Not" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.not"></a>

```go
func Not() interface{}
```

- *Type:* interface{}

---

##### `Operation`<sup>Required</sup> <a name="Operation" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.operation"></a>

```go
func Operation() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### ServiceIncidentRuleIncidentRuleIncidentPropertiesList <a name="ServiceIncidentRuleIncidentRuleIncidentPropertiesList" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/serviceincidentrule"

serviceincidentrule.NewServiceIncidentRuleIncidentRuleIncidentPropertiesList(terraformResource IInterpolatingParent, terraformAttribute *string, wrapsSet *bool) ServiceIncidentRuleIncidentRuleIncidentPropertiesList
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.Initializer.parameter.wrapsSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.get">Get</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.get"></a>

```go
func Get(index *f64) ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.get.parameter.index"></a>

- *Type:* *f64

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference <a name="ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/serviceincidentrule"

serviceincidentrule.NewServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string, complexObjectIndex *f64, complexObjectIsFromSet *bool) ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>*f64</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* *f64

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.putStakeholderProperties">PutStakeholderProperties</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.resetDescription">ResetDescription</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.resetDetails">ResetDetails</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.resetTags">ResetTags</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `PutStakeholderProperties` <a name="PutStakeholderProperties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.putStakeholderProperties"></a>

```go
func PutStakeholderProperties(value interface{})
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.putStakeholderProperties.parameter.value"></a>

- *Type:* interface{}

---

##### `ResetDescription` <a name="ResetDescription" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.resetDescription"></a>

```go
func ResetDescription()
```

##### `ResetDetails` <a name="ResetDetails" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.resetDetails"></a>

```go
func ResetDetails()
```

##### `ResetTags` <a name="ResetTags" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.resetTags"></a>

```go
func ResetTags()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.stakeholderProperties">StakeholderProperties</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList">ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.descriptionInput">DescriptionInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.detailsInput">DetailsInput</a></code> | <code>*map[string]*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.messageInput">MessageInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.priorityInput">PriorityInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.stakeholderPropertiesInput">StakeholderPropertiesInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.tagsInput">TagsInput</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.description">Description</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.details">Details</a></code> | <code>*map[string]*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.message">Message</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.priority">Priority</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.tags">Tags</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `StakeholderProperties`<sup>Required</sup> <a name="StakeholderProperties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.stakeholderProperties"></a>

```go
func StakeholderProperties() ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList">ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList</a>

---

##### `DescriptionInput`<sup>Optional</sup> <a name="DescriptionInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.descriptionInput"></a>

```go
func DescriptionInput() *string
```

- *Type:* *string

---

##### `DetailsInput`<sup>Optional</sup> <a name="DetailsInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.detailsInput"></a>

```go
func DetailsInput() *map[string]*string
```

- *Type:* *map[string]*string

---

##### `MessageInput`<sup>Optional</sup> <a name="MessageInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.messageInput"></a>

```go
func MessageInput() *string
```

- *Type:* *string

---

##### `PriorityInput`<sup>Optional</sup> <a name="PriorityInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.priorityInput"></a>

```go
func PriorityInput() *string
```

- *Type:* *string

---

##### `StakeholderPropertiesInput`<sup>Optional</sup> <a name="StakeholderPropertiesInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.stakeholderPropertiesInput"></a>

```go
func StakeholderPropertiesInput() interface{}
```

- *Type:* interface{}

---

##### `TagsInput`<sup>Optional</sup> <a name="TagsInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.tagsInput"></a>

```go
func TagsInput() *[]*string
```

- *Type:* *[]*string

---

##### `Description`<sup>Required</sup> <a name="Description" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.description"></a>

```go
func Description() *string
```

- *Type:* *string

---

##### `Details`<sup>Required</sup> <a name="Details" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.details"></a>

```go
func Details() *map[string]*string
```

- *Type:* *map[string]*string

---

##### `Message`<sup>Required</sup> <a name="Message" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.message"></a>

```go
func Message() *string
```

- *Type:* *string

---

##### `Priority`<sup>Required</sup> <a name="Priority" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.priority"></a>

```go
func Priority() *string
```

- *Type:* *string

---

##### `Tags`<sup>Required</sup> <a name="Tags" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.tags"></a>

```go
func Tags() *[]*string
```

- *Type:* *[]*string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList <a name="ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/serviceincidentrule"

serviceincidentrule.NewServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList(terraformResource IInterpolatingParent, terraformAttribute *string, wrapsSet *bool) ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.Initializer.parameter.wrapsSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.get">Get</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.get"></a>

```go
func Get(index *f64) ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.get.parameter.index"></a>

- *Type:* *f64

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference <a name="ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/serviceincidentrule"

serviceincidentrule.NewServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string, complexObjectIndex *f64, complexObjectIsFromSet *bool) ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>*f64</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* *f64

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.resetDescription">ResetDescription</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.resetEnable">ResetEnable</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetDescription` <a name="ResetDescription" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.resetDescription"></a>

```go
func ResetDescription()
```

##### `ResetEnable` <a name="ResetEnable" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.resetEnable"></a>

```go
func ResetEnable()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.descriptionInput">DescriptionInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.enableInput">EnableInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.messageInput">MessageInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.description">Description</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.enable">Enable</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.message">Message</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `DescriptionInput`<sup>Optional</sup> <a name="DescriptionInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.descriptionInput"></a>

```go
func DescriptionInput() *string
```

- *Type:* *string

---

##### `EnableInput`<sup>Optional</sup> <a name="EnableInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.enableInput"></a>

```go
func EnableInput() interface{}
```

- *Type:* interface{}

---

##### `MessageInput`<sup>Optional</sup> <a name="MessageInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.messageInput"></a>

```go
func MessageInput() *string
```

- *Type:* *string

---

##### `Description`<sup>Required</sup> <a name="Description" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.description"></a>

```go
func Description() *string
```

- *Type:* *string

---

##### `Enable`<sup>Required</sup> <a name="Enable" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.enable"></a>

```go
func Enable() interface{}
```

- *Type:* interface{}

---

##### `Message`<sup>Required</sup> <a name="Message" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.message"></a>

```go
func Message() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### ServiceIncidentRuleIncidentRuleList <a name="ServiceIncidentRuleIncidentRuleList" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/serviceincidentrule"

serviceincidentrule.NewServiceIncidentRuleIncidentRuleList(terraformResource IInterpolatingParent, terraformAttribute *string, wrapsSet *bool) ServiceIncidentRuleIncidentRuleList
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.Initializer.parameter.wrapsSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.get">Get</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.get"></a>

```go
func Get(index *f64) ServiceIncidentRuleIncidentRuleOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.get.parameter.index"></a>

- *Type:* *f64

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### ServiceIncidentRuleIncidentRuleOutputReference <a name="ServiceIncidentRuleIncidentRuleOutputReference" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/serviceincidentrule"

serviceincidentrule.NewServiceIncidentRuleIncidentRuleOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string, complexObjectIndex *f64, complexObjectIsFromSet *bool) ServiceIncidentRuleIncidentRuleOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>*f64</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* *f64

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.putConditions">PutConditions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.putIncidentProperties">PutIncidentProperties</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.resetConditionMatchType">ResetConditionMatchType</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.resetConditions">ResetConditions</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `PutConditions` <a name="PutConditions" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.putConditions"></a>

```go
func PutConditions(value interface{})
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.putConditions.parameter.value"></a>

- *Type:* interface{}

---

##### `PutIncidentProperties` <a name="PutIncidentProperties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.putIncidentProperties"></a>

```go
func PutIncidentProperties(value interface{})
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.putIncidentProperties.parameter.value"></a>

- *Type:* interface{}

---

##### `ResetConditionMatchType` <a name="ResetConditionMatchType" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.resetConditionMatchType"></a>

```go
func ResetConditionMatchType()
```

##### `ResetConditions` <a name="ResetConditions" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.resetConditions"></a>

```go
func ResetConditions()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditions">Conditions</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList">ServiceIncidentRuleIncidentRuleConditionsList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.incidentProperties">IncidentProperties</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList">ServiceIncidentRuleIncidentRuleIncidentPropertiesList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditionMatchTypeInput">ConditionMatchTypeInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditionsInput">ConditionsInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.incidentPropertiesInput">IncidentPropertiesInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditionMatchType">ConditionMatchType</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `Conditions`<sup>Required</sup> <a name="Conditions" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditions"></a>

```go
func Conditions() ServiceIncidentRuleIncidentRuleConditionsList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList">ServiceIncidentRuleIncidentRuleConditionsList</a>

---

##### `IncidentProperties`<sup>Required</sup> <a name="IncidentProperties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.incidentProperties"></a>

```go
func IncidentProperties() ServiceIncidentRuleIncidentRuleIncidentPropertiesList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList">ServiceIncidentRuleIncidentRuleIncidentPropertiesList</a>

---

##### `ConditionMatchTypeInput`<sup>Optional</sup> <a name="ConditionMatchTypeInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditionMatchTypeInput"></a>

```go
func ConditionMatchTypeInput() *string
```

- *Type:* *string

---

##### `ConditionsInput`<sup>Optional</sup> <a name="ConditionsInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditionsInput"></a>

```go
func ConditionsInput() interface{}
```

- *Type:* interface{}

---

##### `IncidentPropertiesInput`<sup>Optional</sup> <a name="IncidentPropertiesInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.incidentPropertiesInput"></a>

```go
func IncidentPropertiesInput() interface{}
```

- *Type:* interface{}

---

##### `ConditionMatchType`<sup>Required</sup> <a name="ConditionMatchType" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditionMatchType"></a>

```go
func ConditionMatchType() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---



