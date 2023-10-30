# `opsgenie_alert_policy`

Refer to the Terraform Registory for docs: [`opsgenie_alert_policy`](https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy).

# `alertPolicy` Submodule <a name="`alertPolicy` Submodule" id="rhizo-co-terraform-provider-opsgenie.alertPolicy"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### AlertPolicy <a name="AlertPolicy" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy"></a>

Represents a {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy opsgenie_alert_policy}.

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/alertpolicy"

alertpolicy.NewAlertPolicy(scope Construct, id *string, config AlertPolicyConfig) AlertPolicy
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.scope">scope</a></code> | <code>github.com/aws/constructs-go/constructs/v10.Construct</code> | The scope in which to define this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.id">id</a></code> | <code>*string</code> | The scoped construct ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.config">config</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig">AlertPolicyConfig</a></code> | *No description.* |

---

##### `scope`<sup>Required</sup> <a name="scope" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.scope"></a>

- *Type:* github.com/aws/constructs-go/constructs/v10.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.id"></a>

- *Type:* *string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Required</sup> <a name="config" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.config"></a>

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig">AlertPolicyConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.toString">ToString</a></code> | Returns a string representation of this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.addOverride">AddOverride</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.overrideLogicalId">OverrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetOverrideLogicalId">ResetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.toMetadata">ToMetadata</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.toTerraform">ToTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.putFilter">PutFilter</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.putResponders">PutResponders</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.putTimeRestriction">PutTimeRestriction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetActions">ResetActions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetAlertDescription">ResetAlertDescription</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetAlias">ResetAlias</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetContinuePolicy">ResetContinuePolicy</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetEnabled">ResetEnabled</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetEntity">ResetEntity</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetFilter">ResetFilter</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetId">ResetId</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetIgnoreOriginalActions">ResetIgnoreOriginalActions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetIgnoreOriginalDetails">ResetIgnoreOriginalDetails</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetIgnoreOriginalResponders">ResetIgnoreOriginalResponders</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetIgnoreOriginalTags">ResetIgnoreOriginalTags</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetPolicyDescription">ResetPolicyDescription</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetPriority">ResetPriority</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetResponders">ResetResponders</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetSource">ResetSource</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetTags">ResetTags</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetTeamId">ResetTeamId</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetTimeRestriction">ResetTimeRestriction</a></code> | *No description.* |

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.toString"></a>

```go
func ToString() *string
```

Returns a string representation of this construct.

##### `AddOverride` <a name="AddOverride" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.addOverride"></a>

```go
func AddOverride(path *string, value interface{})
```

###### `path`<sup>Required</sup> <a name="path" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.addOverride.parameter.path"></a>

- *Type:* *string

---

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.addOverride.parameter.value"></a>

- *Type:* interface{}

---

##### `OverrideLogicalId` <a name="OverrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.overrideLogicalId"></a>

```go
func OverrideLogicalId(newLogicalId *string)
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* *string

The new logical ID to use for this stack element.

---

##### `ResetOverrideLogicalId` <a name="ResetOverrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetOverrideLogicalId"></a>

```go
func ResetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `ToMetadata` <a name="ToMetadata" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.toMetadata"></a>

```go
func ToMetadata() interface{}
```

##### `ToTerraform` <a name="ToTerraform" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.toTerraform"></a>

```go
func ToTerraform() interface{}
```

Adds this resource to the terraform JSON output.

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `PutFilter` <a name="PutFilter" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.putFilter"></a>

```go
func PutFilter(value interface{})
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.putFilter.parameter.value"></a>

- *Type:* interface{}

---

##### `PutResponders` <a name="PutResponders" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.putResponders"></a>

```go
func PutResponders(value interface{})
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.putResponders.parameter.value"></a>

- *Type:* interface{}

---

##### `PutTimeRestriction` <a name="PutTimeRestriction" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.putTimeRestriction"></a>

```go
func PutTimeRestriction(value interface{})
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.putTimeRestriction.parameter.value"></a>

- *Type:* interface{}

---

##### `ResetActions` <a name="ResetActions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetActions"></a>

```go
func ResetActions()
```

##### `ResetAlertDescription` <a name="ResetAlertDescription" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetAlertDescription"></a>

```go
func ResetAlertDescription()
```

##### `ResetAlias` <a name="ResetAlias" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetAlias"></a>

```go
func ResetAlias()
```

##### `ResetContinuePolicy` <a name="ResetContinuePolicy" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetContinuePolicy"></a>

```go
func ResetContinuePolicy()
```

##### `ResetEnabled` <a name="ResetEnabled" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetEnabled"></a>

```go
func ResetEnabled()
```

##### `ResetEntity` <a name="ResetEntity" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetEntity"></a>

```go
func ResetEntity()
```

##### `ResetFilter` <a name="ResetFilter" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetFilter"></a>

```go
func ResetFilter()
```

##### `ResetId` <a name="ResetId" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetId"></a>

```go
func ResetId()
```

##### `ResetIgnoreOriginalActions` <a name="ResetIgnoreOriginalActions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetIgnoreOriginalActions"></a>

```go
func ResetIgnoreOriginalActions()
```

##### `ResetIgnoreOriginalDetails` <a name="ResetIgnoreOriginalDetails" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetIgnoreOriginalDetails"></a>

```go
func ResetIgnoreOriginalDetails()
```

##### `ResetIgnoreOriginalResponders` <a name="ResetIgnoreOriginalResponders" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetIgnoreOriginalResponders"></a>

```go
func ResetIgnoreOriginalResponders()
```

##### `ResetIgnoreOriginalTags` <a name="ResetIgnoreOriginalTags" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetIgnoreOriginalTags"></a>

```go
func ResetIgnoreOriginalTags()
```

##### `ResetPolicyDescription` <a name="ResetPolicyDescription" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetPolicyDescription"></a>

```go
func ResetPolicyDescription()
```

##### `ResetPriority` <a name="ResetPriority" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetPriority"></a>

```go
func ResetPriority()
```

##### `ResetResponders` <a name="ResetResponders" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetResponders"></a>

```go
func ResetResponders()
```

##### `ResetSource` <a name="ResetSource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetSource"></a>

```go
func ResetSource()
```

##### `ResetTags` <a name="ResetTags" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetTags"></a>

```go
func ResetTags()
```

##### `ResetTeamId` <a name="ResetTeamId" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetTeamId"></a>

```go
func ResetTeamId()
```

##### `ResetTimeRestriction` <a name="ResetTimeRestriction" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetTimeRestriction"></a>

```go
func ResetTimeRestriction()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.isConstruct">IsConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.isTerraformElement">IsTerraformElement</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.isTerraformResource">IsTerraformResource</a></code> | *No description.* |

---

##### `IsConstruct` <a name="IsConstruct" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.isConstruct"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/alertpolicy"

alertpolicy.AlertPolicy_IsConstruct(x interface{}) *bool
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

- *Type:* interface{}

Any object.

---

##### `IsTerraformElement` <a name="IsTerraformElement" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.isTerraformElement"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/alertpolicy"

alertpolicy.AlertPolicy_IsTerraformElement(x interface{}) *bool
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.isTerraformElement.parameter.x"></a>

- *Type:* interface{}

---

##### `IsTerraformResource` <a name="IsTerraformResource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.isTerraformResource"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/alertpolicy"

alertpolicy.AlertPolicy_IsTerraformResource(x interface{}) *bool
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.isTerraformResource.parameter.x"></a>

- *Type:* interface{}

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.node">Node</a></code> | <code>github.com/aws/constructs-go/constructs/v10.Node</code> | The tree node. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.cdktfStack">CdktfStack</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.friendlyUniqueId">FriendlyUniqueId</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.terraformMetaArguments">TerraformMetaArguments</a></code> | <code>*map[string]interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.terraformResourceType">TerraformResourceType</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.terraformGeneratorMetadata">TerraformGeneratorMetadata</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.connection">Connection</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.count">Count</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.dependsOn">DependsOn</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.forEach">ForEach</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.lifecycle">Lifecycle</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.provider">Provider</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.provisioners">Provisioners</a></code> | <code>*[]interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.filter">Filter</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList">AlertPolicyFilterList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.responders">Responders</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList">AlertPolicyRespondersList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.timeRestriction">TimeRestriction</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList">AlertPolicyTimeRestrictionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.actionsInput">ActionsInput</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.alertDescriptionInput">AlertDescriptionInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.aliasInput">AliasInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.continuePolicyInput">ContinuePolicyInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.enabledInput">EnabledInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.entityInput">EntityInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.filterInput">FilterInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.idInput">IdInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalActionsInput">IgnoreOriginalActionsInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalDetailsInput">IgnoreOriginalDetailsInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalRespondersInput">IgnoreOriginalRespondersInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalTagsInput">IgnoreOriginalTagsInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.messageInput">MessageInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.nameInput">NameInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.policyDescriptionInput">PolicyDescriptionInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.priorityInput">PriorityInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.respondersInput">RespondersInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.sourceInput">SourceInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.tagsInput">TagsInput</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.teamIdInput">TeamIdInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.timeRestrictionInput">TimeRestrictionInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.actions">Actions</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.alertDescription">AlertDescription</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.alias">Alias</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.continuePolicy">ContinuePolicy</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.enabled">Enabled</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.entity">Entity</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.id">Id</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalActions">IgnoreOriginalActions</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalDetails">IgnoreOriginalDetails</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalResponders">IgnoreOriginalResponders</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalTags">IgnoreOriginalTags</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.message">Message</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.name">Name</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.policyDescription">PolicyDescription</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.priority">Priority</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.source">Source</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.tags">Tags</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.teamId">TeamId</a></code> | <code>*string</code> | *No description.* |

---

##### `Node`<sup>Required</sup> <a name="Node" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.node"></a>

```go
func Node() Node
```

- *Type:* github.com/aws/constructs-go/constructs/v10.Node

The tree node.

---

##### `CdktfStack`<sup>Required</sup> <a name="CdktfStack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.cdktfStack"></a>

```go
func CdktfStack() TerraformStack
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformStack

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `FriendlyUniqueId`<sup>Required</sup> <a name="FriendlyUniqueId" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.friendlyUniqueId"></a>

```go
func FriendlyUniqueId() *string
```

- *Type:* *string

---

##### `TerraformMetaArguments`<sup>Required</sup> <a name="TerraformMetaArguments" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.terraformMetaArguments"></a>

```go
func TerraformMetaArguments() *map[string]interface{}
```

- *Type:* *map[string]interface{}

---

##### `TerraformResourceType`<sup>Required</sup> <a name="TerraformResourceType" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.terraformResourceType"></a>

```go
func TerraformResourceType() *string
```

- *Type:* *string

---

##### `TerraformGeneratorMetadata`<sup>Optional</sup> <a name="TerraformGeneratorMetadata" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.terraformGeneratorMetadata"></a>

```go
func TerraformGeneratorMetadata() TerraformProviderGeneratorMetadata
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProviderGeneratorMetadata

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.connection"></a>

```go
func Connection() interface{}
```

- *Type:* interface{}

---

##### `Count`<sup>Optional</sup> <a name="Count" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.count"></a>

```go
func Count() interface{}
```

- *Type:* interface{}

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.dependsOn"></a>

```go
func DependsOn() *[]*string
```

- *Type:* *[]*string

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.forEach"></a>

```go
func ForEach() ITerraformIterator
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.lifecycle"></a>

```go
func Lifecycle() TerraformResourceLifecycle
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.provider"></a>

```go
func Provider() TerraformProvider
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.provisioners"></a>

```go
func Provisioners() *[]interface{}
```

- *Type:* *[]interface{}

---

##### `Filter`<sup>Required</sup> <a name="Filter" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.filter"></a>

```go
func Filter() AlertPolicyFilterList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList">AlertPolicyFilterList</a>

---

##### `Responders`<sup>Required</sup> <a name="Responders" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.responders"></a>

```go
func Responders() AlertPolicyRespondersList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList">AlertPolicyRespondersList</a>

---

##### `TimeRestriction`<sup>Required</sup> <a name="TimeRestriction" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.timeRestriction"></a>

```go
func TimeRestriction() AlertPolicyTimeRestrictionList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList">AlertPolicyTimeRestrictionList</a>

---

##### `ActionsInput`<sup>Optional</sup> <a name="ActionsInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.actionsInput"></a>

```go
func ActionsInput() *[]*string
```

- *Type:* *[]*string

---

##### `AlertDescriptionInput`<sup>Optional</sup> <a name="AlertDescriptionInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.alertDescriptionInput"></a>

```go
func AlertDescriptionInput() *string
```

- *Type:* *string

---

##### `AliasInput`<sup>Optional</sup> <a name="AliasInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.aliasInput"></a>

```go
func AliasInput() *string
```

- *Type:* *string

---

##### `ContinuePolicyInput`<sup>Optional</sup> <a name="ContinuePolicyInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.continuePolicyInput"></a>

```go
func ContinuePolicyInput() interface{}
```

- *Type:* interface{}

---

##### `EnabledInput`<sup>Optional</sup> <a name="EnabledInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.enabledInput"></a>

```go
func EnabledInput() interface{}
```

- *Type:* interface{}

---

##### `EntityInput`<sup>Optional</sup> <a name="EntityInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.entityInput"></a>

```go
func EntityInput() *string
```

- *Type:* *string

---

##### `FilterInput`<sup>Optional</sup> <a name="FilterInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.filterInput"></a>

```go
func FilterInput() interface{}
```

- *Type:* interface{}

---

##### `IdInput`<sup>Optional</sup> <a name="IdInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.idInput"></a>

```go
func IdInput() *string
```

- *Type:* *string

---

##### `IgnoreOriginalActionsInput`<sup>Optional</sup> <a name="IgnoreOriginalActionsInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalActionsInput"></a>

```go
func IgnoreOriginalActionsInput() interface{}
```

- *Type:* interface{}

---

##### `IgnoreOriginalDetailsInput`<sup>Optional</sup> <a name="IgnoreOriginalDetailsInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalDetailsInput"></a>

```go
func IgnoreOriginalDetailsInput() interface{}
```

- *Type:* interface{}

---

##### `IgnoreOriginalRespondersInput`<sup>Optional</sup> <a name="IgnoreOriginalRespondersInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalRespondersInput"></a>

```go
func IgnoreOriginalRespondersInput() interface{}
```

- *Type:* interface{}

---

##### `IgnoreOriginalTagsInput`<sup>Optional</sup> <a name="IgnoreOriginalTagsInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalTagsInput"></a>

```go
func IgnoreOriginalTagsInput() interface{}
```

- *Type:* interface{}

---

##### `MessageInput`<sup>Optional</sup> <a name="MessageInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.messageInput"></a>

```go
func MessageInput() *string
```

- *Type:* *string

---

##### `NameInput`<sup>Optional</sup> <a name="NameInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.nameInput"></a>

```go
func NameInput() *string
```

- *Type:* *string

---

##### `PolicyDescriptionInput`<sup>Optional</sup> <a name="PolicyDescriptionInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.policyDescriptionInput"></a>

```go
func PolicyDescriptionInput() *string
```

- *Type:* *string

---

##### `PriorityInput`<sup>Optional</sup> <a name="PriorityInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.priorityInput"></a>

```go
func PriorityInput() *string
```

- *Type:* *string

---

##### `RespondersInput`<sup>Optional</sup> <a name="RespondersInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.respondersInput"></a>

```go
func RespondersInput() interface{}
```

- *Type:* interface{}

---

##### `SourceInput`<sup>Optional</sup> <a name="SourceInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.sourceInput"></a>

```go
func SourceInput() *string
```

- *Type:* *string

---

##### `TagsInput`<sup>Optional</sup> <a name="TagsInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.tagsInput"></a>

```go
func TagsInput() *[]*string
```

- *Type:* *[]*string

---

##### `TeamIdInput`<sup>Optional</sup> <a name="TeamIdInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.teamIdInput"></a>

```go
func TeamIdInput() *string
```

- *Type:* *string

---

##### `TimeRestrictionInput`<sup>Optional</sup> <a name="TimeRestrictionInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.timeRestrictionInput"></a>

```go
func TimeRestrictionInput() interface{}
```

- *Type:* interface{}

---

##### `Actions`<sup>Required</sup> <a name="Actions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.actions"></a>

```go
func Actions() *[]*string
```

- *Type:* *[]*string

---

##### `AlertDescription`<sup>Required</sup> <a name="AlertDescription" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.alertDescription"></a>

```go
func AlertDescription() *string
```

- *Type:* *string

---

##### `Alias`<sup>Required</sup> <a name="Alias" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.alias"></a>

```go
func Alias() *string
```

- *Type:* *string

---

##### `ContinuePolicy`<sup>Required</sup> <a name="ContinuePolicy" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.continuePolicy"></a>

```go
func ContinuePolicy() interface{}
```

- *Type:* interface{}

---

##### `Enabled`<sup>Required</sup> <a name="Enabled" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.enabled"></a>

```go
func Enabled() interface{}
```

- *Type:* interface{}

---

##### `Entity`<sup>Required</sup> <a name="Entity" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.entity"></a>

```go
func Entity() *string
```

- *Type:* *string

---

##### `Id`<sup>Required</sup> <a name="Id" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.id"></a>

```go
func Id() *string
```

- *Type:* *string

---

##### `IgnoreOriginalActions`<sup>Required</sup> <a name="IgnoreOriginalActions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalActions"></a>

```go
func IgnoreOriginalActions() interface{}
```

- *Type:* interface{}

---

##### `IgnoreOriginalDetails`<sup>Required</sup> <a name="IgnoreOriginalDetails" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalDetails"></a>

```go
func IgnoreOriginalDetails() interface{}
```

- *Type:* interface{}

---

##### `IgnoreOriginalResponders`<sup>Required</sup> <a name="IgnoreOriginalResponders" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalResponders"></a>

```go
func IgnoreOriginalResponders() interface{}
```

- *Type:* interface{}

---

##### `IgnoreOriginalTags`<sup>Required</sup> <a name="IgnoreOriginalTags" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalTags"></a>

```go
func IgnoreOriginalTags() interface{}
```

- *Type:* interface{}

---

##### `Message`<sup>Required</sup> <a name="Message" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.message"></a>

```go
func Message() *string
```

- *Type:* *string

---

##### `Name`<sup>Required</sup> <a name="Name" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.name"></a>

```go
func Name() *string
```

- *Type:* *string

---

##### `PolicyDescription`<sup>Required</sup> <a name="PolicyDescription" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.policyDescription"></a>

```go
func PolicyDescription() *string
```

- *Type:* *string

---

##### `Priority`<sup>Required</sup> <a name="Priority" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.priority"></a>

```go
func Priority() *string
```

- *Type:* *string

---

##### `Source`<sup>Required</sup> <a name="Source" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.source"></a>

```go
func Source() *string
```

- *Type:* *string

---

##### `Tags`<sup>Required</sup> <a name="Tags" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.tags"></a>

```go
func Tags() *[]*string
```

- *Type:* *[]*string

---

##### `TeamId`<sup>Required</sup> <a name="TeamId" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.teamId"></a>

```go
func TeamId() *string
```

- *Type:* *string

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.tfResourceType">TfResourceType</a></code> | <code>*string</code> | *No description.* |

---

##### `TfResourceType`<sup>Required</sup> <a name="TfResourceType" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.tfResourceType"></a>

```go
func TfResourceType() *string
```

- *Type:* *string

---

## Structs <a name="Structs" id="Structs"></a>

### AlertPolicyConfig <a name="AlertPolicyConfig" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/alertpolicy"

&alertpolicy.AlertPolicyConfig {
	Connection: interface{},
	Count: interface{},
	DependsOn: *[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable,
	ForEach: github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator,
	Lifecycle: github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle,
	Provider: github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider,
	Provisioners: *[]interface{},
	Message: *string,
	Name: *string,
	Actions: *[]*string,
	AlertDescription: *string,
	Alias: *string,
	ContinuePolicy: interface{},
	Enabled: interface{},
	Entity: *string,
	Filter: interface{},
	Id: *string,
	IgnoreOriginalActions: interface{},
	IgnoreOriginalDetails: interface{},
	IgnoreOriginalResponders: interface{},
	IgnoreOriginalTags: interface{},
	PolicyDescription: *string,
	Priority: *string,
	Responders: interface{},
	Source: *string,
	Tags: *[]*string,
	TeamId: *string,
	TimeRestriction: interface{},
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.connection">Connection</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.count">Count</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.dependsOn">DependsOn</a></code> | <code>*[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.forEach">ForEach</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.lifecycle">Lifecycle</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.provider">Provider</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.provisioners">Provisioners</a></code> | <code>*[]interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.message">Message</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#message AlertPolicy#message}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.name">Name</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#name AlertPolicy#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.actions">Actions</a></code> | <code>*[]*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#actions AlertPolicy#actions}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.alertDescription">AlertDescription</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#alert_description AlertPolicy#alert_description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.alias">Alias</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#alias AlertPolicy#alias}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.continuePolicy">ContinuePolicy</a></code> | <code>interface{}</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#continue_policy AlertPolicy#continue_policy}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.enabled">Enabled</a></code> | <code>interface{}</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#enabled AlertPolicy#enabled}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.entity">Entity</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#entity AlertPolicy#entity}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.filter">Filter</a></code> | <code>interface{}</code> | filter block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.id">Id</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#id AlertPolicy#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.ignoreOriginalActions">IgnoreOriginalActions</a></code> | <code>interface{}</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#ignore_original_actions AlertPolicy#ignore_original_actions}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.ignoreOriginalDetails">IgnoreOriginalDetails</a></code> | <code>interface{}</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#ignore_original_details AlertPolicy#ignore_original_details}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.ignoreOriginalResponders">IgnoreOriginalResponders</a></code> | <code>interface{}</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#ignore_original_responders AlertPolicy#ignore_original_responders}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.ignoreOriginalTags">IgnoreOriginalTags</a></code> | <code>interface{}</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#ignore_original_tags AlertPolicy#ignore_original_tags}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.policyDescription">PolicyDescription</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#policy_description AlertPolicy#policy_description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.priority">Priority</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#priority AlertPolicy#priority}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.responders">Responders</a></code> | <code>interface{}</code> | responders block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.source">Source</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#source AlertPolicy#source}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.tags">Tags</a></code> | <code>*[]*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#tags AlertPolicy#tags}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.teamId">TeamId</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#team_id AlertPolicy#team_id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.timeRestriction">TimeRestriction</a></code> | <code>interface{}</code> | time_restriction block. |

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.connection"></a>

```go
Connection interface{}
```

- *Type:* interface{}

---

##### `Count`<sup>Optional</sup> <a name="Count" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.count"></a>

```go
Count interface{}
```

- *Type:* interface{}

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.dependsOn"></a>

```go
DependsOn *[]ITerraformDependable
```

- *Type:* *[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.forEach"></a>

```go
ForEach ITerraformIterator
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.lifecycle"></a>

```go
Lifecycle TerraformResourceLifecycle
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.provider"></a>

```go
Provider TerraformProvider
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.provisioners"></a>

```go
Provisioners *[]interface{}
```

- *Type:* *[]interface{}

---

##### `Message`<sup>Required</sup> <a name="Message" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.message"></a>

```go
Message *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#message AlertPolicy#message}.

---

##### `Name`<sup>Required</sup> <a name="Name" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.name"></a>

```go
Name *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#name AlertPolicy#name}.

---

##### `Actions`<sup>Optional</sup> <a name="Actions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.actions"></a>

```go
Actions *[]*string
```

- *Type:* *[]*string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#actions AlertPolicy#actions}.

---

##### `AlertDescription`<sup>Optional</sup> <a name="AlertDescription" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.alertDescription"></a>

```go
AlertDescription *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#alert_description AlertPolicy#alert_description}.

---

##### `Alias`<sup>Optional</sup> <a name="Alias" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.alias"></a>

```go
Alias *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#alias AlertPolicy#alias}.

---

##### `ContinuePolicy`<sup>Optional</sup> <a name="ContinuePolicy" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.continuePolicy"></a>

```go
ContinuePolicy interface{}
```

- *Type:* interface{}

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#continue_policy AlertPolicy#continue_policy}.

---

##### `Enabled`<sup>Optional</sup> <a name="Enabled" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.enabled"></a>

```go
Enabled interface{}
```

- *Type:* interface{}

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#enabled AlertPolicy#enabled}.

---

##### `Entity`<sup>Optional</sup> <a name="Entity" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.entity"></a>

```go
Entity *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#entity AlertPolicy#entity}.

---

##### `Filter`<sup>Optional</sup> <a name="Filter" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.filter"></a>

```go
Filter interface{}
```

- *Type:* interface{}

filter block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#filter AlertPolicy#filter}

---

##### `Id`<sup>Optional</sup> <a name="Id" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.id"></a>

```go
Id *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#id AlertPolicy#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `IgnoreOriginalActions`<sup>Optional</sup> <a name="IgnoreOriginalActions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.ignoreOriginalActions"></a>

```go
IgnoreOriginalActions interface{}
```

- *Type:* interface{}

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#ignore_original_actions AlertPolicy#ignore_original_actions}.

---

##### `IgnoreOriginalDetails`<sup>Optional</sup> <a name="IgnoreOriginalDetails" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.ignoreOriginalDetails"></a>

```go
IgnoreOriginalDetails interface{}
```

- *Type:* interface{}

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#ignore_original_details AlertPolicy#ignore_original_details}.

---

##### `IgnoreOriginalResponders`<sup>Optional</sup> <a name="IgnoreOriginalResponders" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.ignoreOriginalResponders"></a>

```go
IgnoreOriginalResponders interface{}
```

- *Type:* interface{}

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#ignore_original_responders AlertPolicy#ignore_original_responders}.

---

##### `IgnoreOriginalTags`<sup>Optional</sup> <a name="IgnoreOriginalTags" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.ignoreOriginalTags"></a>

```go
IgnoreOriginalTags interface{}
```

- *Type:* interface{}

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#ignore_original_tags AlertPolicy#ignore_original_tags}.

---

##### `PolicyDescription`<sup>Optional</sup> <a name="PolicyDescription" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.policyDescription"></a>

```go
PolicyDescription *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#policy_description AlertPolicy#policy_description}.

---

##### `Priority`<sup>Optional</sup> <a name="Priority" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.priority"></a>

```go
Priority *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#priority AlertPolicy#priority}.

---

##### `Responders`<sup>Optional</sup> <a name="Responders" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.responders"></a>

```go
Responders interface{}
```

- *Type:* interface{}

responders block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#responders AlertPolicy#responders}

---

##### `Source`<sup>Optional</sup> <a name="Source" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.source"></a>

```go
Source *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#source AlertPolicy#source}.

---

##### `Tags`<sup>Optional</sup> <a name="Tags" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.tags"></a>

```go
Tags *[]*string
```

- *Type:* *[]*string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#tags AlertPolicy#tags}.

---

##### `TeamId`<sup>Optional</sup> <a name="TeamId" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.teamId"></a>

```go
TeamId *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#team_id AlertPolicy#team_id}.

---

##### `TimeRestriction`<sup>Optional</sup> <a name="TimeRestriction" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.timeRestriction"></a>

```go
TimeRestriction interface{}
```

- *Type:* interface{}

time_restriction block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#time_restriction AlertPolicy#time_restriction}

---

### AlertPolicyFilter <a name="AlertPolicyFilter" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilter"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilter.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/alertpolicy"

&alertpolicy.AlertPolicyFilter {
	Conditions: interface{},
	Type: *string,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilter.property.conditions">Conditions</a></code> | <code>interface{}</code> | conditions block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilter.property.type">Type</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#type AlertPolicy#type}. |

---

##### `Conditions`<sup>Optional</sup> <a name="Conditions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilter.property.conditions"></a>

```go
Conditions interface{}
```

- *Type:* interface{}

conditions block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#conditions AlertPolicy#conditions}

---

##### `Type`<sup>Optional</sup> <a name="Type" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilter.property.type"></a>

```go
Type *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#type AlertPolicy#type}.

---

### AlertPolicyFilterConditions <a name="AlertPolicyFilterConditions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/alertpolicy"

&alertpolicy.AlertPolicyFilterConditions {
	Field: *string,
	Operation: *string,
	ExpectedValue: *string,
	Key: *string,
	Not: interface{},
	Order: *f64,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.property.field">Field</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#field AlertPolicy#field}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.property.operation">Operation</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#operation AlertPolicy#operation}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.property.expectedValue">ExpectedValue</a></code> | <code>*string</code> | User defined value that will be compared with alert field according to the operation. Default value is empty string. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.property.key">Key</a></code> | <code>*string</code> | If 'field' is set as 'extra-properties', key could be used for key-value pair. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.property.not">Not</a></code> | <code>interface{}</code> | Indicates behaviour of the given operation. Default value is false. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.property.order">Order</a></code> | <code>*f64</code> | Order of the condition in conditions list. |

---

##### `Field`<sup>Required</sup> <a name="Field" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.property.field"></a>

```go
Field *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#field AlertPolicy#field}.

---

##### `Operation`<sup>Required</sup> <a name="Operation" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.property.operation"></a>

```go
Operation *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#operation AlertPolicy#operation}.

---

##### `ExpectedValue`<sup>Optional</sup> <a name="ExpectedValue" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.property.expectedValue"></a>

```go
ExpectedValue *string
```

- *Type:* *string

User defined value that will be compared with alert field according to the operation. Default value is empty string.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#expected_value AlertPolicy#expected_value}

---

##### `Key`<sup>Optional</sup> <a name="Key" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.property.key"></a>

```go
Key *string
```

- *Type:* *string

If 'field' is set as 'extra-properties', key could be used for key-value pair.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#key AlertPolicy#key}

---

##### `Not`<sup>Optional</sup> <a name="Not" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.property.not"></a>

```go
Not interface{}
```

- *Type:* interface{}

Indicates behaviour of the given operation. Default value is false.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#not AlertPolicy#not}

---

##### `Order`<sup>Optional</sup> <a name="Order" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.property.order"></a>

```go
Order *f64
```

- *Type:* *f64

Order of the condition in conditions list.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#order AlertPolicy#order}

---

### AlertPolicyResponders <a name="AlertPolicyResponders" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/alertpolicy"

&alertpolicy.AlertPolicyResponders {
	Id: *string,
	Type: *string,
	Name: *string,
	Username: *string,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders.property.id">Id</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#id AlertPolicy#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders.property.type">Type</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#type AlertPolicy#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders.property.name">Name</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#name AlertPolicy#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders.property.username">Username</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#username AlertPolicy#username}. |

---

##### `Id`<sup>Required</sup> <a name="Id" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders.property.id"></a>

```go
Id *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#id AlertPolicy#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `Type`<sup>Required</sup> <a name="Type" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders.property.type"></a>

```go
Type *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#type AlertPolicy#type}.

---

##### `Name`<sup>Optional</sup> <a name="Name" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders.property.name"></a>

```go
Name *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#name AlertPolicy#name}.

---

##### `Username`<sup>Optional</sup> <a name="Username" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders.property.username"></a>

```go
Username *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#username AlertPolicy#username}.

---

### AlertPolicyTimeRestriction <a name="AlertPolicyTimeRestriction" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/alertpolicy"

&alertpolicy.AlertPolicyTimeRestriction {
	Type: *string,
	Restriction: interface{},
	Restrictions: interface{},
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction.property.type">Type</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#type AlertPolicy#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction.property.restriction">Restriction</a></code> | <code>interface{}</code> | restriction block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction.property.restrictions">Restrictions</a></code> | <code>interface{}</code> | restrictions block. |

---

##### `Type`<sup>Required</sup> <a name="Type" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction.property.type"></a>

```go
Type *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#type AlertPolicy#type}.

---

##### `Restriction`<sup>Optional</sup> <a name="Restriction" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction.property.restriction"></a>

```go
Restriction interface{}
```

- *Type:* interface{}

restriction block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#restriction AlertPolicy#restriction}

---

##### `Restrictions`<sup>Optional</sup> <a name="Restrictions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction.property.restrictions"></a>

```go
Restrictions interface{}
```

- *Type:* interface{}

restrictions block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#restrictions AlertPolicy#restrictions}

---

### AlertPolicyTimeRestrictionRestriction <a name="AlertPolicyTimeRestrictionRestriction" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/alertpolicy"

&alertpolicy.AlertPolicyTimeRestrictionRestriction {
	EndHour: *f64,
	EndMin: *f64,
	StartHour: *f64,
	StartMin: *f64,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction.property.endHour">EndHour</a></code> | <code>*f64</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#end_hour AlertPolicy#end_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction.property.endMin">EndMin</a></code> | <code>*f64</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#end_min AlertPolicy#end_min}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction.property.startHour">StartHour</a></code> | <code>*f64</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#start_hour AlertPolicy#start_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction.property.startMin">StartMin</a></code> | <code>*f64</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#start_min AlertPolicy#start_min}. |

---

##### `EndHour`<sup>Required</sup> <a name="EndHour" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction.property.endHour"></a>

```go
EndHour *f64
```

- *Type:* *f64

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#end_hour AlertPolicy#end_hour}.

---

##### `EndMin`<sup>Required</sup> <a name="EndMin" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction.property.endMin"></a>

```go
EndMin *f64
```

- *Type:* *f64

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#end_min AlertPolicy#end_min}.

---

##### `StartHour`<sup>Required</sup> <a name="StartHour" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction.property.startHour"></a>

```go
StartHour *f64
```

- *Type:* *f64

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#start_hour AlertPolicy#start_hour}.

---

##### `StartMin`<sup>Required</sup> <a name="StartMin" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction.property.startMin"></a>

```go
StartMin *f64
```

- *Type:* *f64

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#start_min AlertPolicy#start_min}.

---

### AlertPolicyTimeRestrictionRestrictions <a name="AlertPolicyTimeRestrictionRestrictions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/alertpolicy"

&alertpolicy.AlertPolicyTimeRestrictionRestrictions {
	EndDay: *string,
	EndHour: *f64,
	EndMin: *f64,
	StartDay: *string,
	StartHour: *f64,
	StartMin: *f64,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.property.endDay">EndDay</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#end_day AlertPolicy#end_day}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.property.endHour">EndHour</a></code> | <code>*f64</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#end_hour AlertPolicy#end_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.property.endMin">EndMin</a></code> | <code>*f64</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#end_min AlertPolicy#end_min}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.property.startDay">StartDay</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#start_day AlertPolicy#start_day}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.property.startHour">StartHour</a></code> | <code>*f64</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#start_hour AlertPolicy#start_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.property.startMin">StartMin</a></code> | <code>*f64</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#start_min AlertPolicy#start_min}. |

---

##### `EndDay`<sup>Required</sup> <a name="EndDay" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.property.endDay"></a>

```go
EndDay *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#end_day AlertPolicy#end_day}.

---

##### `EndHour`<sup>Required</sup> <a name="EndHour" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.property.endHour"></a>

```go
EndHour *f64
```

- *Type:* *f64

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#end_hour AlertPolicy#end_hour}.

---

##### `EndMin`<sup>Required</sup> <a name="EndMin" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.property.endMin"></a>

```go
EndMin *f64
```

- *Type:* *f64

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#end_min AlertPolicy#end_min}.

---

##### `StartDay`<sup>Required</sup> <a name="StartDay" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.property.startDay"></a>

```go
StartDay *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#start_day AlertPolicy#start_day}.

---

##### `StartHour`<sup>Required</sup> <a name="StartHour" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.property.startHour"></a>

```go
StartHour *f64
```

- *Type:* *f64

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#start_hour AlertPolicy#start_hour}.

---

##### `StartMin`<sup>Required</sup> <a name="StartMin" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.property.startMin"></a>

```go
StartMin *f64
```

- *Type:* *f64

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#start_min AlertPolicy#start_min}.

---

## Classes <a name="Classes" id="Classes"></a>

### AlertPolicyFilterConditionsList <a name="AlertPolicyFilterConditionsList" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/alertpolicy"

alertpolicy.NewAlertPolicyFilterConditionsList(terraformResource IInterpolatingParent, terraformAttribute *string, wrapsSet *bool) AlertPolicyFilterConditionsList
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.Initializer.parameter.wrapsSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.get">Get</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.get"></a>

```go
func Get(index *f64) AlertPolicyFilterConditionsOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.get.parameter.index"></a>

- *Type:* *f64

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### AlertPolicyFilterConditionsOutputReference <a name="AlertPolicyFilterConditionsOutputReference" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/alertpolicy"

alertpolicy.NewAlertPolicyFilterConditionsOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string, complexObjectIndex *f64, complexObjectIsFromSet *bool) AlertPolicyFilterConditionsOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>*f64</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* *f64

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.resetExpectedValue">ResetExpectedValue</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.resetKey">ResetKey</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.resetNot">ResetNot</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.resetOrder">ResetOrder</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetExpectedValue` <a name="ResetExpectedValue" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.resetExpectedValue"></a>

```go
func ResetExpectedValue()
```

##### `ResetKey` <a name="ResetKey" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.resetKey"></a>

```go
func ResetKey()
```

##### `ResetNot` <a name="ResetNot" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.resetNot"></a>

```go
func ResetNot()
```

##### `ResetOrder` <a name="ResetOrder" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.resetOrder"></a>

```go
func ResetOrder()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.expectedValueInput">ExpectedValueInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.fieldInput">FieldInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.keyInput">KeyInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.notInput">NotInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.operationInput">OperationInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.orderInput">OrderInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.expectedValue">ExpectedValue</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.field">Field</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.key">Key</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.not">Not</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.operation">Operation</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.order">Order</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `ExpectedValueInput`<sup>Optional</sup> <a name="ExpectedValueInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.expectedValueInput"></a>

```go
func ExpectedValueInput() *string
```

- *Type:* *string

---

##### `FieldInput`<sup>Optional</sup> <a name="FieldInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.fieldInput"></a>

```go
func FieldInput() *string
```

- *Type:* *string

---

##### `KeyInput`<sup>Optional</sup> <a name="KeyInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.keyInput"></a>

```go
func KeyInput() *string
```

- *Type:* *string

---

##### `NotInput`<sup>Optional</sup> <a name="NotInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.notInput"></a>

```go
func NotInput() interface{}
```

- *Type:* interface{}

---

##### `OperationInput`<sup>Optional</sup> <a name="OperationInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.operationInput"></a>

```go
func OperationInput() *string
```

- *Type:* *string

---

##### `OrderInput`<sup>Optional</sup> <a name="OrderInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.orderInput"></a>

```go
func OrderInput() *f64
```

- *Type:* *f64

---

##### `ExpectedValue`<sup>Required</sup> <a name="ExpectedValue" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.expectedValue"></a>

```go
func ExpectedValue() *string
```

- *Type:* *string

---

##### `Field`<sup>Required</sup> <a name="Field" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.field"></a>

```go
func Field() *string
```

- *Type:* *string

---

##### `Key`<sup>Required</sup> <a name="Key" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.key"></a>

```go
func Key() *string
```

- *Type:* *string

---

##### `Not`<sup>Required</sup> <a name="Not" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.not"></a>

```go
func Not() interface{}
```

- *Type:* interface{}

---

##### `Operation`<sup>Required</sup> <a name="Operation" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.operation"></a>

```go
func Operation() *string
```

- *Type:* *string

---

##### `Order`<sup>Required</sup> <a name="Order" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.order"></a>

```go
func Order() *f64
```

- *Type:* *f64

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### AlertPolicyFilterList <a name="AlertPolicyFilterList" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/alertpolicy"

alertpolicy.NewAlertPolicyFilterList(terraformResource IInterpolatingParent, terraformAttribute *string, wrapsSet *bool) AlertPolicyFilterList
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.Initializer.parameter.wrapsSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.get">Get</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.get"></a>

```go
func Get(index *f64) AlertPolicyFilterOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.get.parameter.index"></a>

- *Type:* *f64

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### AlertPolicyFilterOutputReference <a name="AlertPolicyFilterOutputReference" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/alertpolicy"

alertpolicy.NewAlertPolicyFilterOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string, complexObjectIndex *f64, complexObjectIsFromSet *bool) AlertPolicyFilterOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>*f64</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* *f64

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.putConditions">PutConditions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.resetConditions">ResetConditions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.resetType">ResetType</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `PutConditions` <a name="PutConditions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.putConditions"></a>

```go
func PutConditions(value interface{})
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.putConditions.parameter.value"></a>

- *Type:* interface{}

---

##### `ResetConditions` <a name="ResetConditions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.resetConditions"></a>

```go
func ResetConditions()
```

##### `ResetType` <a name="ResetType" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.resetType"></a>

```go
func ResetType()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.conditions">Conditions</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList">AlertPolicyFilterConditionsList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.conditionsInput">ConditionsInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.typeInput">TypeInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.type">Type</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `Conditions`<sup>Required</sup> <a name="Conditions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.conditions"></a>

```go
func Conditions() AlertPolicyFilterConditionsList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList">AlertPolicyFilterConditionsList</a>

---

##### `ConditionsInput`<sup>Optional</sup> <a name="ConditionsInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.conditionsInput"></a>

```go
func ConditionsInput() interface{}
```

- *Type:* interface{}

---

##### `TypeInput`<sup>Optional</sup> <a name="TypeInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.typeInput"></a>

```go
func TypeInput() *string
```

- *Type:* *string

---

##### `Type`<sup>Required</sup> <a name="Type" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.type"></a>

```go
func Type() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### AlertPolicyRespondersList <a name="AlertPolicyRespondersList" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/alertpolicy"

alertpolicy.NewAlertPolicyRespondersList(terraformResource IInterpolatingParent, terraformAttribute *string, wrapsSet *bool) AlertPolicyRespondersList
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.Initializer.parameter.wrapsSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.get">Get</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.get"></a>

```go
func Get(index *f64) AlertPolicyRespondersOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.get.parameter.index"></a>

- *Type:* *f64

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### AlertPolicyRespondersOutputReference <a name="AlertPolicyRespondersOutputReference" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/alertpolicy"

alertpolicy.NewAlertPolicyRespondersOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string, complexObjectIndex *f64, complexObjectIsFromSet *bool) AlertPolicyRespondersOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>*f64</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* *f64

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.resetName">ResetName</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.resetUsername">ResetUsername</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetName` <a name="ResetName" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.resetName"></a>

```go
func ResetName()
```

##### `ResetUsername` <a name="ResetUsername" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.resetUsername"></a>

```go
func ResetUsername()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.idInput">IdInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.nameInput">NameInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.typeInput">TypeInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.usernameInput">UsernameInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.id">Id</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.name">Name</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.type">Type</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.username">Username</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `IdInput`<sup>Optional</sup> <a name="IdInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.idInput"></a>

```go
func IdInput() *string
```

- *Type:* *string

---

##### `NameInput`<sup>Optional</sup> <a name="NameInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.nameInput"></a>

```go
func NameInput() *string
```

- *Type:* *string

---

##### `TypeInput`<sup>Optional</sup> <a name="TypeInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.typeInput"></a>

```go
func TypeInput() *string
```

- *Type:* *string

---

##### `UsernameInput`<sup>Optional</sup> <a name="UsernameInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.usernameInput"></a>

```go
func UsernameInput() *string
```

- *Type:* *string

---

##### `Id`<sup>Required</sup> <a name="Id" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.id"></a>

```go
func Id() *string
```

- *Type:* *string

---

##### `Name`<sup>Required</sup> <a name="Name" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.name"></a>

```go
func Name() *string
```

- *Type:* *string

---

##### `Type`<sup>Required</sup> <a name="Type" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.type"></a>

```go
func Type() *string
```

- *Type:* *string

---

##### `Username`<sup>Required</sup> <a name="Username" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.username"></a>

```go
func Username() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### AlertPolicyTimeRestrictionList <a name="AlertPolicyTimeRestrictionList" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/alertpolicy"

alertpolicy.NewAlertPolicyTimeRestrictionList(terraformResource IInterpolatingParent, terraformAttribute *string, wrapsSet *bool) AlertPolicyTimeRestrictionList
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.Initializer.parameter.wrapsSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.get">Get</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.get"></a>

```go
func Get(index *f64) AlertPolicyTimeRestrictionOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.get.parameter.index"></a>

- *Type:* *f64

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### AlertPolicyTimeRestrictionOutputReference <a name="AlertPolicyTimeRestrictionOutputReference" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/alertpolicy"

alertpolicy.NewAlertPolicyTimeRestrictionOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string, complexObjectIndex *f64, complexObjectIsFromSet *bool) AlertPolicyTimeRestrictionOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>*f64</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* *f64

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.putRestriction">PutRestriction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.putRestrictions">PutRestrictions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.resetRestriction">ResetRestriction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.resetRestrictions">ResetRestrictions</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `PutRestriction` <a name="PutRestriction" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.putRestriction"></a>

```go
func PutRestriction(value interface{})
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.putRestriction.parameter.value"></a>

- *Type:* interface{}

---

##### `PutRestrictions` <a name="PutRestrictions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.putRestrictions"></a>

```go
func PutRestrictions(value interface{})
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.putRestrictions.parameter.value"></a>

- *Type:* interface{}

---

##### `ResetRestriction` <a name="ResetRestriction" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.resetRestriction"></a>

```go
func ResetRestriction()
```

##### `ResetRestrictions` <a name="ResetRestrictions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.resetRestrictions"></a>

```go
func ResetRestrictions()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.restriction">Restriction</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList">AlertPolicyTimeRestrictionRestrictionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.restrictions">Restrictions</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList">AlertPolicyTimeRestrictionRestrictionsList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.restrictionInput">RestrictionInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.restrictionsInput">RestrictionsInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.typeInput">TypeInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.type">Type</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `Restriction`<sup>Required</sup> <a name="Restriction" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.restriction"></a>

```go
func Restriction() AlertPolicyTimeRestrictionRestrictionList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList">AlertPolicyTimeRestrictionRestrictionList</a>

---

##### `Restrictions`<sup>Required</sup> <a name="Restrictions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.restrictions"></a>

```go
func Restrictions() AlertPolicyTimeRestrictionRestrictionsList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList">AlertPolicyTimeRestrictionRestrictionsList</a>

---

##### `RestrictionInput`<sup>Optional</sup> <a name="RestrictionInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.restrictionInput"></a>

```go
func RestrictionInput() interface{}
```

- *Type:* interface{}

---

##### `RestrictionsInput`<sup>Optional</sup> <a name="RestrictionsInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.restrictionsInput"></a>

```go
func RestrictionsInput() interface{}
```

- *Type:* interface{}

---

##### `TypeInput`<sup>Optional</sup> <a name="TypeInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.typeInput"></a>

```go
func TypeInput() *string
```

- *Type:* *string

---

##### `Type`<sup>Required</sup> <a name="Type" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.type"></a>

```go
func Type() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### AlertPolicyTimeRestrictionRestrictionList <a name="AlertPolicyTimeRestrictionRestrictionList" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/alertpolicy"

alertpolicy.NewAlertPolicyTimeRestrictionRestrictionList(terraformResource IInterpolatingParent, terraformAttribute *string, wrapsSet *bool) AlertPolicyTimeRestrictionRestrictionList
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.Initializer.parameter.wrapsSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.get">Get</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.get"></a>

```go
func Get(index *f64) AlertPolicyTimeRestrictionRestrictionOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.get.parameter.index"></a>

- *Type:* *f64

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### AlertPolicyTimeRestrictionRestrictionOutputReference <a name="AlertPolicyTimeRestrictionRestrictionOutputReference" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/alertpolicy"

alertpolicy.NewAlertPolicyTimeRestrictionRestrictionOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string, complexObjectIndex *f64, complexObjectIsFromSet *bool) AlertPolicyTimeRestrictionRestrictionOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>*f64</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* *f64

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.endHourInput">EndHourInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.endMinInput">EndMinInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.startHourInput">StartHourInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.startMinInput">StartMinInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.endHour">EndHour</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.endMin">EndMin</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.startHour">StartHour</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.startMin">StartMin</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `EndHourInput`<sup>Optional</sup> <a name="EndHourInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.endHourInput"></a>

```go
func EndHourInput() *f64
```

- *Type:* *f64

---

##### `EndMinInput`<sup>Optional</sup> <a name="EndMinInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.endMinInput"></a>

```go
func EndMinInput() *f64
```

- *Type:* *f64

---

##### `StartHourInput`<sup>Optional</sup> <a name="StartHourInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.startHourInput"></a>

```go
func StartHourInput() *f64
```

- *Type:* *f64

---

##### `StartMinInput`<sup>Optional</sup> <a name="StartMinInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.startMinInput"></a>

```go
func StartMinInput() *f64
```

- *Type:* *f64

---

##### `EndHour`<sup>Required</sup> <a name="EndHour" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.endHour"></a>

```go
func EndHour() *f64
```

- *Type:* *f64

---

##### `EndMin`<sup>Required</sup> <a name="EndMin" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.endMin"></a>

```go
func EndMin() *f64
```

- *Type:* *f64

---

##### `StartHour`<sup>Required</sup> <a name="StartHour" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.startHour"></a>

```go
func StartHour() *f64
```

- *Type:* *f64

---

##### `StartMin`<sup>Required</sup> <a name="StartMin" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.startMin"></a>

```go
func StartMin() *f64
```

- *Type:* *f64

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### AlertPolicyTimeRestrictionRestrictionsList <a name="AlertPolicyTimeRestrictionRestrictionsList" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/alertpolicy"

alertpolicy.NewAlertPolicyTimeRestrictionRestrictionsList(terraformResource IInterpolatingParent, terraformAttribute *string, wrapsSet *bool) AlertPolicyTimeRestrictionRestrictionsList
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.Initializer.parameter.wrapsSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.get">Get</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.get"></a>

```go
func Get(index *f64) AlertPolicyTimeRestrictionRestrictionsOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.get.parameter.index"></a>

- *Type:* *f64

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### AlertPolicyTimeRestrictionRestrictionsOutputReference <a name="AlertPolicyTimeRestrictionRestrictionsOutputReference" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/alertpolicy"

alertpolicy.NewAlertPolicyTimeRestrictionRestrictionsOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string, complexObjectIndex *f64, complexObjectIsFromSet *bool) AlertPolicyTimeRestrictionRestrictionsOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>*f64</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* *f64

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.endDayInput">EndDayInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.endHourInput">EndHourInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.endMinInput">EndMinInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.startDayInput">StartDayInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.startHourInput">StartHourInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.startMinInput">StartMinInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.endDay">EndDay</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.endHour">EndHour</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.endMin">EndMin</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.startDay">StartDay</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.startHour">StartHour</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.startMin">StartMin</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `EndDayInput`<sup>Optional</sup> <a name="EndDayInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.endDayInput"></a>

```go
func EndDayInput() *string
```

- *Type:* *string

---

##### `EndHourInput`<sup>Optional</sup> <a name="EndHourInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.endHourInput"></a>

```go
func EndHourInput() *f64
```

- *Type:* *f64

---

##### `EndMinInput`<sup>Optional</sup> <a name="EndMinInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.endMinInput"></a>

```go
func EndMinInput() *f64
```

- *Type:* *f64

---

##### `StartDayInput`<sup>Optional</sup> <a name="StartDayInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.startDayInput"></a>

```go
func StartDayInput() *string
```

- *Type:* *string

---

##### `StartHourInput`<sup>Optional</sup> <a name="StartHourInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.startHourInput"></a>

```go
func StartHourInput() *f64
```

- *Type:* *f64

---

##### `StartMinInput`<sup>Optional</sup> <a name="StartMinInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.startMinInput"></a>

```go
func StartMinInput() *f64
```

- *Type:* *f64

---

##### `EndDay`<sup>Required</sup> <a name="EndDay" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.endDay"></a>

```go
func EndDay() *string
```

- *Type:* *string

---

##### `EndHour`<sup>Required</sup> <a name="EndHour" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.endHour"></a>

```go
func EndHour() *f64
```

- *Type:* *f64

---

##### `EndMin`<sup>Required</sup> <a name="EndMin" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.endMin"></a>

```go
func EndMin() *f64
```

- *Type:* *f64

---

##### `StartDay`<sup>Required</sup> <a name="StartDay" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.startDay"></a>

```go
func StartDay() *string
```

- *Type:* *string

---

##### `StartHour`<sup>Required</sup> <a name="StartHour" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.startHour"></a>

```go
func StartHour() *f64
```

- *Type:* *f64

---

##### `StartMin`<sup>Required</sup> <a name="StartMin" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.startMin"></a>

```go
func StartMin() *f64
```

- *Type:* *f64

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---



