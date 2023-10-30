# `opsgenie_team_routing_rule`

Refer to the Terraform Registory for docs: [`opsgenie_team_routing_rule`](https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule).

# `teamRoutingRule` Submodule <a name="`teamRoutingRule` Submodule" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### TeamRoutingRule <a name="TeamRoutingRule" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule"></a>

Represents a {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule opsgenie_team_routing_rule}.

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/teamroutingrule"

teamroutingrule.NewTeamRoutingRule(scope Construct, id *string, config TeamRoutingRuleConfig) TeamRoutingRule
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.scope">scope</a></code> | <code>github.com/aws/constructs-go/constructs/v10.Construct</code> | The scope in which to define this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.id">id</a></code> | <code>*string</code> | The scoped construct ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.config">config</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig">TeamRoutingRuleConfig</a></code> | *No description.* |

---

##### `scope`<sup>Required</sup> <a name="scope" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.scope"></a>

- *Type:* github.com/aws/constructs-go/constructs/v10.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.id"></a>

- *Type:* *string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Required</sup> <a name="config" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.config"></a>

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig">TeamRoutingRuleConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.toString">ToString</a></code> | Returns a string representation of this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.addOverride">AddOverride</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.overrideLogicalId">OverrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetOverrideLogicalId">ResetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.toMetadata">ToMetadata</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.toTerraform">ToTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putCriteria">PutCriteria</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putNotify">PutNotify</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putTimeRestriction">PutTimeRestriction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetCriteria">ResetCriteria</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetId">ResetId</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetIsDefault">ResetIsDefault</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetName">ResetName</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetOrder">ResetOrder</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetTimeRestriction">ResetTimeRestriction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetTimezone">ResetTimezone</a></code> | *No description.* |

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.toString"></a>

```go
func ToString() *string
```

Returns a string representation of this construct.

##### `AddOverride` <a name="AddOverride" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.addOverride"></a>

```go
func AddOverride(path *string, value interface{})
```

###### `path`<sup>Required</sup> <a name="path" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.addOverride.parameter.path"></a>

- *Type:* *string

---

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.addOverride.parameter.value"></a>

- *Type:* interface{}

---

##### `OverrideLogicalId` <a name="OverrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.overrideLogicalId"></a>

```go
func OverrideLogicalId(newLogicalId *string)
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* *string

The new logical ID to use for this stack element.

---

##### `ResetOverrideLogicalId` <a name="ResetOverrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetOverrideLogicalId"></a>

```go
func ResetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `ToMetadata` <a name="ToMetadata" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.toMetadata"></a>

```go
func ToMetadata() interface{}
```

##### `ToTerraform` <a name="ToTerraform" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.toTerraform"></a>

```go
func ToTerraform() interface{}
```

Adds this resource to the terraform JSON output.

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `PutCriteria` <a name="PutCriteria" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putCriteria"></a>

```go
func PutCriteria(value interface{})
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putCriteria.parameter.value"></a>

- *Type:* interface{}

---

##### `PutNotify` <a name="PutNotify" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putNotify"></a>

```go
func PutNotify(value interface{})
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putNotify.parameter.value"></a>

- *Type:* interface{}

---

##### `PutTimeRestriction` <a name="PutTimeRestriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putTimeRestriction"></a>

```go
func PutTimeRestriction(value interface{})
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putTimeRestriction.parameter.value"></a>

- *Type:* interface{}

---

##### `ResetCriteria` <a name="ResetCriteria" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetCriteria"></a>

```go
func ResetCriteria()
```

##### `ResetId` <a name="ResetId" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetId"></a>

```go
func ResetId()
```

##### `ResetIsDefault` <a name="ResetIsDefault" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetIsDefault"></a>

```go
func ResetIsDefault()
```

##### `ResetName` <a name="ResetName" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetName"></a>

```go
func ResetName()
```

##### `ResetOrder` <a name="ResetOrder" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetOrder"></a>

```go
func ResetOrder()
```

##### `ResetTimeRestriction` <a name="ResetTimeRestriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetTimeRestriction"></a>

```go
func ResetTimeRestriction()
```

##### `ResetTimezone` <a name="ResetTimezone" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetTimezone"></a>

```go
func ResetTimezone()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isConstruct">IsConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isTerraformElement">IsTerraformElement</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isTerraformResource">IsTerraformResource</a></code> | *No description.* |

---

##### `IsConstruct` <a name="IsConstruct" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isConstruct"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/teamroutingrule"

teamroutingrule.TeamRoutingRule_IsConstruct(x interface{}) *bool
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

- *Type:* interface{}

Any object.

---

##### `IsTerraformElement` <a name="IsTerraformElement" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isTerraformElement"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/teamroutingrule"

teamroutingrule.TeamRoutingRule_IsTerraformElement(x interface{}) *bool
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isTerraformElement.parameter.x"></a>

- *Type:* interface{}

---

##### `IsTerraformResource` <a name="IsTerraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isTerraformResource"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/teamroutingrule"

teamroutingrule.TeamRoutingRule_IsTerraformResource(x interface{}) *bool
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isTerraformResource.parameter.x"></a>

- *Type:* interface{}

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.node">Node</a></code> | <code>github.com/aws/constructs-go/constructs/v10.Node</code> | The tree node. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.cdktfStack">CdktfStack</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.friendlyUniqueId">FriendlyUniqueId</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.terraformMetaArguments">TerraformMetaArguments</a></code> | <code>*map[string]interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.terraformResourceType">TerraformResourceType</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.terraformGeneratorMetadata">TerraformGeneratorMetadata</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.connection">Connection</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.count">Count</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.dependsOn">DependsOn</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.forEach">ForEach</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.lifecycle">Lifecycle</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.provider">Provider</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.provisioners">Provisioners</a></code> | <code>*[]interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.criteria">Criteria</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList">TeamRoutingRuleCriteriaList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.notify">Notify</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList">TeamRoutingRuleNotifyList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timeRestriction">TimeRestriction</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList">TeamRoutingRuleTimeRestrictionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.criteriaInput">CriteriaInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.idInput">IdInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.isDefaultInput">IsDefaultInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.nameInput">NameInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.notifyInput">NotifyInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.orderInput">OrderInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.teamIdInput">TeamIdInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timeRestrictionInput">TimeRestrictionInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timezoneInput">TimezoneInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.id">Id</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.isDefault">IsDefault</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.name">Name</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.order">Order</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.teamId">TeamId</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timezone">Timezone</a></code> | <code>*string</code> | *No description.* |

---

##### `Node`<sup>Required</sup> <a name="Node" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.node"></a>

```go
func Node() Node
```

- *Type:* github.com/aws/constructs-go/constructs/v10.Node

The tree node.

---

##### `CdktfStack`<sup>Required</sup> <a name="CdktfStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.cdktfStack"></a>

```go
func CdktfStack() TerraformStack
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformStack

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `FriendlyUniqueId`<sup>Required</sup> <a name="FriendlyUniqueId" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.friendlyUniqueId"></a>

```go
func FriendlyUniqueId() *string
```

- *Type:* *string

---

##### `TerraformMetaArguments`<sup>Required</sup> <a name="TerraformMetaArguments" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.terraformMetaArguments"></a>

```go
func TerraformMetaArguments() *map[string]interface{}
```

- *Type:* *map[string]interface{}

---

##### `TerraformResourceType`<sup>Required</sup> <a name="TerraformResourceType" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.terraformResourceType"></a>

```go
func TerraformResourceType() *string
```

- *Type:* *string

---

##### `TerraformGeneratorMetadata`<sup>Optional</sup> <a name="TerraformGeneratorMetadata" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.terraformGeneratorMetadata"></a>

```go
func TerraformGeneratorMetadata() TerraformProviderGeneratorMetadata
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProviderGeneratorMetadata

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.connection"></a>

```go
func Connection() interface{}
```

- *Type:* interface{}

---

##### `Count`<sup>Optional</sup> <a name="Count" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.count"></a>

```go
func Count() interface{}
```

- *Type:* interface{}

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.dependsOn"></a>

```go
func DependsOn() *[]*string
```

- *Type:* *[]*string

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.forEach"></a>

```go
func ForEach() ITerraformIterator
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.lifecycle"></a>

```go
func Lifecycle() TerraformResourceLifecycle
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.provider"></a>

```go
func Provider() TerraformProvider
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.provisioners"></a>

```go
func Provisioners() *[]interface{}
```

- *Type:* *[]interface{}

---

##### `Criteria`<sup>Required</sup> <a name="Criteria" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.criteria"></a>

```go
func Criteria() TeamRoutingRuleCriteriaList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList">TeamRoutingRuleCriteriaList</a>

---

##### `Notify`<sup>Required</sup> <a name="Notify" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.notify"></a>

```go
func Notify() TeamRoutingRuleNotifyList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList">TeamRoutingRuleNotifyList</a>

---

##### `TimeRestriction`<sup>Required</sup> <a name="TimeRestriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timeRestriction"></a>

```go
func TimeRestriction() TeamRoutingRuleTimeRestrictionList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList">TeamRoutingRuleTimeRestrictionList</a>

---

##### `CriteriaInput`<sup>Optional</sup> <a name="CriteriaInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.criteriaInput"></a>

```go
func CriteriaInput() interface{}
```

- *Type:* interface{}

---

##### `IdInput`<sup>Optional</sup> <a name="IdInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.idInput"></a>

```go
func IdInput() *string
```

- *Type:* *string

---

##### `IsDefaultInput`<sup>Optional</sup> <a name="IsDefaultInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.isDefaultInput"></a>

```go
func IsDefaultInput() interface{}
```

- *Type:* interface{}

---

##### `NameInput`<sup>Optional</sup> <a name="NameInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.nameInput"></a>

```go
func NameInput() *string
```

- *Type:* *string

---

##### `NotifyInput`<sup>Optional</sup> <a name="NotifyInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.notifyInput"></a>

```go
func NotifyInput() interface{}
```

- *Type:* interface{}

---

##### `OrderInput`<sup>Optional</sup> <a name="OrderInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.orderInput"></a>

```go
func OrderInput() *f64
```

- *Type:* *f64

---

##### `TeamIdInput`<sup>Optional</sup> <a name="TeamIdInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.teamIdInput"></a>

```go
func TeamIdInput() *string
```

- *Type:* *string

---

##### `TimeRestrictionInput`<sup>Optional</sup> <a name="TimeRestrictionInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timeRestrictionInput"></a>

```go
func TimeRestrictionInput() interface{}
```

- *Type:* interface{}

---

##### `TimezoneInput`<sup>Optional</sup> <a name="TimezoneInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timezoneInput"></a>

```go
func TimezoneInput() *string
```

- *Type:* *string

---

##### `Id`<sup>Required</sup> <a name="Id" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.id"></a>

```go
func Id() *string
```

- *Type:* *string

---

##### `IsDefault`<sup>Required</sup> <a name="IsDefault" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.isDefault"></a>

```go
func IsDefault() interface{}
```

- *Type:* interface{}

---

##### `Name`<sup>Required</sup> <a name="Name" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.name"></a>

```go
func Name() *string
```

- *Type:* *string

---

##### `Order`<sup>Required</sup> <a name="Order" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.order"></a>

```go
func Order() *f64
```

- *Type:* *f64

---

##### `TeamId`<sup>Required</sup> <a name="TeamId" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.teamId"></a>

```go
func TeamId() *string
```

- *Type:* *string

---

##### `Timezone`<sup>Required</sup> <a name="Timezone" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timezone"></a>

```go
func Timezone() *string
```

- *Type:* *string

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.tfResourceType">TfResourceType</a></code> | <code>*string</code> | *No description.* |

---

##### `TfResourceType`<sup>Required</sup> <a name="TfResourceType" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.tfResourceType"></a>

```go
func TfResourceType() *string
```

- *Type:* *string

---

## Structs <a name="Structs" id="Structs"></a>

### TeamRoutingRuleConfig <a name="TeamRoutingRuleConfig" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/teamroutingrule"

&teamroutingrule.TeamRoutingRuleConfig {
	Connection: interface{},
	Count: interface{},
	DependsOn: *[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable,
	ForEach: github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator,
	Lifecycle: github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle,
	Provider: github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider,
	Provisioners: *[]interface{},
	Notify: interface{},
	TeamId: *string,
	Criteria: interface{},
	Id: *string,
	IsDefault: interface{},
	Name: *string,
	Order: *f64,
	TimeRestriction: interface{},
	Timezone: *string,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.connection">Connection</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.count">Count</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.dependsOn">DependsOn</a></code> | <code>*[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.forEach">ForEach</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.lifecycle">Lifecycle</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.provider">Provider</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.provisioners">Provisioners</a></code> | <code>*[]interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.notify">Notify</a></code> | <code>interface{}</code> | notify block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.teamId">TeamId</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#team_id TeamRoutingRule#team_id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.criteria">Criteria</a></code> | <code>interface{}</code> | criteria block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.id">Id</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#id TeamRoutingRule#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.isDefault">IsDefault</a></code> | <code>interface{}</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#is_default TeamRoutingRule#is_default}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.name">Name</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#name TeamRoutingRule#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.order">Order</a></code> | <code>*f64</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#order TeamRoutingRule#order}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.timeRestriction">TimeRestriction</a></code> | <code>interface{}</code> | time_restriction block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.timezone">Timezone</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#timezone TeamRoutingRule#timezone}. |

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.connection"></a>

```go
Connection interface{}
```

- *Type:* interface{}

---

##### `Count`<sup>Optional</sup> <a name="Count" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.count"></a>

```go
Count interface{}
```

- *Type:* interface{}

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.dependsOn"></a>

```go
DependsOn *[]ITerraformDependable
```

- *Type:* *[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.forEach"></a>

```go
ForEach ITerraformIterator
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.lifecycle"></a>

```go
Lifecycle TerraformResourceLifecycle
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.provider"></a>

```go
Provider TerraformProvider
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.provisioners"></a>

```go
Provisioners *[]interface{}
```

- *Type:* *[]interface{}

---

##### `Notify`<sup>Required</sup> <a name="Notify" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.notify"></a>

```go
Notify interface{}
```

- *Type:* interface{}

notify block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#notify TeamRoutingRule#notify}

---

##### `TeamId`<sup>Required</sup> <a name="TeamId" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.teamId"></a>

```go
TeamId *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#team_id TeamRoutingRule#team_id}.

---

##### `Criteria`<sup>Optional</sup> <a name="Criteria" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.criteria"></a>

```go
Criteria interface{}
```

- *Type:* interface{}

criteria block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#criteria TeamRoutingRule#criteria}

---

##### `Id`<sup>Optional</sup> <a name="Id" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.id"></a>

```go
Id *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#id TeamRoutingRule#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `IsDefault`<sup>Optional</sup> <a name="IsDefault" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.isDefault"></a>

```go
IsDefault interface{}
```

- *Type:* interface{}

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#is_default TeamRoutingRule#is_default}.

---

##### `Name`<sup>Optional</sup> <a name="Name" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.name"></a>

```go
Name *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#name TeamRoutingRule#name}.

---

##### `Order`<sup>Optional</sup> <a name="Order" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.order"></a>

```go
Order *f64
```

- *Type:* *f64

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#order TeamRoutingRule#order}.

---

##### `TimeRestriction`<sup>Optional</sup> <a name="TimeRestriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.timeRestriction"></a>

```go
TimeRestriction interface{}
```

- *Type:* interface{}

time_restriction block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#time_restriction TeamRoutingRule#time_restriction}

---

##### `Timezone`<sup>Optional</sup> <a name="Timezone" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.timezone"></a>

```go
Timezone *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#timezone TeamRoutingRule#timezone}.

---

### TeamRoutingRuleCriteria <a name="TeamRoutingRuleCriteria" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/teamroutingrule"

&teamroutingrule.TeamRoutingRuleCriteria {
	Type: *string,
	Conditions: interface{},
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria.property.type">Type</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#type TeamRoutingRule#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria.property.conditions">Conditions</a></code> | <code>interface{}</code> | conditions block. |

---

##### `Type`<sup>Required</sup> <a name="Type" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria.property.type"></a>

```go
Type *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#type TeamRoutingRule#type}.

---

##### `Conditions`<sup>Optional</sup> <a name="Conditions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria.property.conditions"></a>

```go
Conditions interface{}
```

- *Type:* interface{}

conditions block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#conditions TeamRoutingRule#conditions}

---

### TeamRoutingRuleCriteriaConditions <a name="TeamRoutingRuleCriteriaConditions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/teamroutingrule"

&teamroutingrule.TeamRoutingRuleCriteriaConditions {
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
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.field">Field</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#field TeamRoutingRule#field}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.operation">Operation</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#operation TeamRoutingRule#operation}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.expectedValue">ExpectedValue</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#expected_value TeamRoutingRule#expected_value}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.key">Key</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#key TeamRoutingRule#key}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.not">Not</a></code> | <code>interface{}</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#not TeamRoutingRule#not}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.order">Order</a></code> | <code>*f64</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#order TeamRoutingRule#order}. |

---

##### `Field`<sup>Required</sup> <a name="Field" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.field"></a>

```go
Field *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#field TeamRoutingRule#field}.

---

##### `Operation`<sup>Required</sup> <a name="Operation" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.operation"></a>

```go
Operation *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#operation TeamRoutingRule#operation}.

---

##### `ExpectedValue`<sup>Optional</sup> <a name="ExpectedValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.expectedValue"></a>

```go
ExpectedValue *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#expected_value TeamRoutingRule#expected_value}.

---

##### `Key`<sup>Optional</sup> <a name="Key" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.key"></a>

```go
Key *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#key TeamRoutingRule#key}.

---

##### `Not`<sup>Optional</sup> <a name="Not" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.not"></a>

```go
Not interface{}
```

- *Type:* interface{}

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#not TeamRoutingRule#not}.

---

##### `Order`<sup>Optional</sup> <a name="Order" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.order"></a>

```go
Order *f64
```

- *Type:* *f64

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#order TeamRoutingRule#order}.

---

### TeamRoutingRuleNotify <a name="TeamRoutingRuleNotify" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/teamroutingrule"

&teamroutingrule.TeamRoutingRuleNotify {
	Type: *string,
	Id: *string,
	Name: *string,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify.property.type">Type</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#type TeamRoutingRule#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify.property.id">Id</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#id TeamRoutingRule#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify.property.name">Name</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#name TeamRoutingRule#name}. |

---

##### `Type`<sup>Required</sup> <a name="Type" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify.property.type"></a>

```go
Type *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#type TeamRoutingRule#type}.

---

##### `Id`<sup>Optional</sup> <a name="Id" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify.property.id"></a>

```go
Id *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#id TeamRoutingRule#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `Name`<sup>Optional</sup> <a name="Name" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify.property.name"></a>

```go
Name *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#name TeamRoutingRule#name}.

---

### TeamRoutingRuleTimeRestriction <a name="TeamRoutingRuleTimeRestriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/teamroutingrule"

&teamroutingrule.TeamRoutingRuleTimeRestriction {
	Type: *string,
	Restriction: interface{},
	Restrictions: interface{},
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction.property.type">Type</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#type TeamRoutingRule#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction.property.restriction">Restriction</a></code> | <code>interface{}</code> | restriction block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction.property.restrictions">Restrictions</a></code> | <code>interface{}</code> | restrictions block. |

---

##### `Type`<sup>Required</sup> <a name="Type" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction.property.type"></a>

```go
Type *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#type TeamRoutingRule#type}.

---

##### `Restriction`<sup>Optional</sup> <a name="Restriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction.property.restriction"></a>

```go
Restriction interface{}
```

- *Type:* interface{}

restriction block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#restriction TeamRoutingRule#restriction}

---

##### `Restrictions`<sup>Optional</sup> <a name="Restrictions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction.property.restrictions"></a>

```go
Restrictions interface{}
```

- *Type:* interface{}

restrictions block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#restrictions TeamRoutingRule#restrictions}

---

### TeamRoutingRuleTimeRestrictionRestriction <a name="TeamRoutingRuleTimeRestrictionRestriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/teamroutingrule"

&teamroutingrule.TeamRoutingRuleTimeRestrictionRestriction {
	EndHour: *f64,
	EndMin: *f64,
	StartHour: *f64,
	StartMin: *f64,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.endHour">EndHour</a></code> | <code>*f64</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_hour TeamRoutingRule#end_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.endMin">EndMin</a></code> | <code>*f64</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_min TeamRoutingRule#end_min}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.startHour">StartHour</a></code> | <code>*f64</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_hour TeamRoutingRule#start_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.startMin">StartMin</a></code> | <code>*f64</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_min TeamRoutingRule#start_min}. |

---

##### `EndHour`<sup>Required</sup> <a name="EndHour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.endHour"></a>

```go
EndHour *f64
```

- *Type:* *f64

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_hour TeamRoutingRule#end_hour}.

---

##### `EndMin`<sup>Required</sup> <a name="EndMin" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.endMin"></a>

```go
EndMin *f64
```

- *Type:* *f64

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_min TeamRoutingRule#end_min}.

---

##### `StartHour`<sup>Required</sup> <a name="StartHour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.startHour"></a>

```go
StartHour *f64
```

- *Type:* *f64

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_hour TeamRoutingRule#start_hour}.

---

##### `StartMin`<sup>Required</sup> <a name="StartMin" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.startMin"></a>

```go
StartMin *f64
```

- *Type:* *f64

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_min TeamRoutingRule#start_min}.

---

### TeamRoutingRuleTimeRestrictionRestrictions <a name="TeamRoutingRuleTimeRestrictionRestrictions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/teamroutingrule"

&teamroutingrule.TeamRoutingRuleTimeRestrictionRestrictions {
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
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.endDay">EndDay</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_day TeamRoutingRule#end_day}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.endHour">EndHour</a></code> | <code>*f64</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_hour TeamRoutingRule#end_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.endMin">EndMin</a></code> | <code>*f64</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_min TeamRoutingRule#end_min}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.startDay">StartDay</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_day TeamRoutingRule#start_day}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.startHour">StartHour</a></code> | <code>*f64</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_hour TeamRoutingRule#start_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.startMin">StartMin</a></code> | <code>*f64</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_min TeamRoutingRule#start_min}. |

---

##### `EndDay`<sup>Required</sup> <a name="EndDay" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.endDay"></a>

```go
EndDay *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_day TeamRoutingRule#end_day}.

---

##### `EndHour`<sup>Required</sup> <a name="EndHour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.endHour"></a>

```go
EndHour *f64
```

- *Type:* *f64

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_hour TeamRoutingRule#end_hour}.

---

##### `EndMin`<sup>Required</sup> <a name="EndMin" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.endMin"></a>

```go
EndMin *f64
```

- *Type:* *f64

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_min TeamRoutingRule#end_min}.

---

##### `StartDay`<sup>Required</sup> <a name="StartDay" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.startDay"></a>

```go
StartDay *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_day TeamRoutingRule#start_day}.

---

##### `StartHour`<sup>Required</sup> <a name="StartHour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.startHour"></a>

```go
StartHour *f64
```

- *Type:* *f64

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_hour TeamRoutingRule#start_hour}.

---

##### `StartMin`<sup>Required</sup> <a name="StartMin" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.startMin"></a>

```go
StartMin *f64
```

- *Type:* *f64

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_min TeamRoutingRule#start_min}.

---

## Classes <a name="Classes" id="Classes"></a>

### TeamRoutingRuleCriteriaConditionsList <a name="TeamRoutingRuleCriteriaConditionsList" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/teamroutingrule"

teamroutingrule.NewTeamRoutingRuleCriteriaConditionsList(terraformResource IInterpolatingParent, terraformAttribute *string, wrapsSet *bool) TeamRoutingRuleCriteriaConditionsList
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.Initializer.parameter.wrapsSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.get">Get</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.get"></a>

```go
func Get(index *f64) TeamRoutingRuleCriteriaConditionsOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.get.parameter.index"></a>

- *Type:* *f64

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### TeamRoutingRuleCriteriaConditionsOutputReference <a name="TeamRoutingRuleCriteriaConditionsOutputReference" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/teamroutingrule"

teamroutingrule.NewTeamRoutingRuleCriteriaConditionsOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string, complexObjectIndex *f64, complexObjectIsFromSet *bool) TeamRoutingRuleCriteriaConditionsOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>*f64</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* *f64

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resetExpectedValue">ResetExpectedValue</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resetKey">ResetKey</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resetNot">ResetNot</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resetOrder">ResetOrder</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetExpectedValue` <a name="ResetExpectedValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resetExpectedValue"></a>

```go
func ResetExpectedValue()
```

##### `ResetKey` <a name="ResetKey" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resetKey"></a>

```go
func ResetKey()
```

##### `ResetNot` <a name="ResetNot" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resetNot"></a>

```go
func ResetNot()
```

##### `ResetOrder` <a name="ResetOrder" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resetOrder"></a>

```go
func ResetOrder()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.expectedValueInput">ExpectedValueInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.fieldInput">FieldInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.keyInput">KeyInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.notInput">NotInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.operationInput">OperationInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.orderInput">OrderInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.expectedValue">ExpectedValue</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.field">Field</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.key">Key</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.not">Not</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.operation">Operation</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.order">Order</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `ExpectedValueInput`<sup>Optional</sup> <a name="ExpectedValueInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.expectedValueInput"></a>

```go
func ExpectedValueInput() *string
```

- *Type:* *string

---

##### `FieldInput`<sup>Optional</sup> <a name="FieldInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.fieldInput"></a>

```go
func FieldInput() *string
```

- *Type:* *string

---

##### `KeyInput`<sup>Optional</sup> <a name="KeyInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.keyInput"></a>

```go
func KeyInput() *string
```

- *Type:* *string

---

##### `NotInput`<sup>Optional</sup> <a name="NotInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.notInput"></a>

```go
func NotInput() interface{}
```

- *Type:* interface{}

---

##### `OperationInput`<sup>Optional</sup> <a name="OperationInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.operationInput"></a>

```go
func OperationInput() *string
```

- *Type:* *string

---

##### `OrderInput`<sup>Optional</sup> <a name="OrderInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.orderInput"></a>

```go
func OrderInput() *f64
```

- *Type:* *f64

---

##### `ExpectedValue`<sup>Required</sup> <a name="ExpectedValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.expectedValue"></a>

```go
func ExpectedValue() *string
```

- *Type:* *string

---

##### `Field`<sup>Required</sup> <a name="Field" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.field"></a>

```go
func Field() *string
```

- *Type:* *string

---

##### `Key`<sup>Required</sup> <a name="Key" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.key"></a>

```go
func Key() *string
```

- *Type:* *string

---

##### `Not`<sup>Required</sup> <a name="Not" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.not"></a>

```go
func Not() interface{}
```

- *Type:* interface{}

---

##### `Operation`<sup>Required</sup> <a name="Operation" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.operation"></a>

```go
func Operation() *string
```

- *Type:* *string

---

##### `Order`<sup>Required</sup> <a name="Order" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.order"></a>

```go
func Order() *f64
```

- *Type:* *f64

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### TeamRoutingRuleCriteriaList <a name="TeamRoutingRuleCriteriaList" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/teamroutingrule"

teamroutingrule.NewTeamRoutingRuleCriteriaList(terraformResource IInterpolatingParent, terraformAttribute *string, wrapsSet *bool) TeamRoutingRuleCriteriaList
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.Initializer.parameter.wrapsSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.get">Get</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.get"></a>

```go
func Get(index *f64) TeamRoutingRuleCriteriaOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.get.parameter.index"></a>

- *Type:* *f64

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### TeamRoutingRuleCriteriaOutputReference <a name="TeamRoutingRuleCriteriaOutputReference" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/teamroutingrule"

teamroutingrule.NewTeamRoutingRuleCriteriaOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string, complexObjectIndex *f64, complexObjectIsFromSet *bool) TeamRoutingRuleCriteriaOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>*f64</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* *f64

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.putConditions">PutConditions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.resetConditions">ResetConditions</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `PutConditions` <a name="PutConditions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.putConditions"></a>

```go
func PutConditions(value interface{})
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.putConditions.parameter.value"></a>

- *Type:* interface{}

---

##### `ResetConditions` <a name="ResetConditions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.resetConditions"></a>

```go
func ResetConditions()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.conditions">Conditions</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList">TeamRoutingRuleCriteriaConditionsList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.conditionsInput">ConditionsInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.typeInput">TypeInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.type">Type</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `Conditions`<sup>Required</sup> <a name="Conditions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.conditions"></a>

```go
func Conditions() TeamRoutingRuleCriteriaConditionsList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList">TeamRoutingRuleCriteriaConditionsList</a>

---

##### `ConditionsInput`<sup>Optional</sup> <a name="ConditionsInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.conditionsInput"></a>

```go
func ConditionsInput() interface{}
```

- *Type:* interface{}

---

##### `TypeInput`<sup>Optional</sup> <a name="TypeInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.typeInput"></a>

```go
func TypeInput() *string
```

- *Type:* *string

---

##### `Type`<sup>Required</sup> <a name="Type" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.type"></a>

```go
func Type() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### TeamRoutingRuleNotifyList <a name="TeamRoutingRuleNotifyList" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/teamroutingrule"

teamroutingrule.NewTeamRoutingRuleNotifyList(terraformResource IInterpolatingParent, terraformAttribute *string, wrapsSet *bool) TeamRoutingRuleNotifyList
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.Initializer.parameter.wrapsSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.get">Get</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.get"></a>

```go
func Get(index *f64) TeamRoutingRuleNotifyOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.get.parameter.index"></a>

- *Type:* *f64

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### TeamRoutingRuleNotifyOutputReference <a name="TeamRoutingRuleNotifyOutputReference" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/teamroutingrule"

teamroutingrule.NewTeamRoutingRuleNotifyOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string, complexObjectIndex *f64, complexObjectIsFromSet *bool) TeamRoutingRuleNotifyOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>*f64</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* *f64

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.resetId">ResetId</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.resetName">ResetName</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetId` <a name="ResetId" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.resetId"></a>

```go
func ResetId()
```

##### `ResetName` <a name="ResetName" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.resetName"></a>

```go
func ResetName()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.idInput">IdInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.nameInput">NameInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.typeInput">TypeInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.id">Id</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.name">Name</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.type">Type</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `IdInput`<sup>Optional</sup> <a name="IdInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.idInput"></a>

```go
func IdInput() *string
```

- *Type:* *string

---

##### `NameInput`<sup>Optional</sup> <a name="NameInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.nameInput"></a>

```go
func NameInput() *string
```

- *Type:* *string

---

##### `TypeInput`<sup>Optional</sup> <a name="TypeInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.typeInput"></a>

```go
func TypeInput() *string
```

- *Type:* *string

---

##### `Id`<sup>Required</sup> <a name="Id" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.id"></a>

```go
func Id() *string
```

- *Type:* *string

---

##### `Name`<sup>Required</sup> <a name="Name" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.name"></a>

```go
func Name() *string
```

- *Type:* *string

---

##### `Type`<sup>Required</sup> <a name="Type" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.type"></a>

```go
func Type() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### TeamRoutingRuleTimeRestrictionList <a name="TeamRoutingRuleTimeRestrictionList" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/teamroutingrule"

teamroutingrule.NewTeamRoutingRuleTimeRestrictionList(terraformResource IInterpolatingParent, terraformAttribute *string, wrapsSet *bool) TeamRoutingRuleTimeRestrictionList
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.Initializer.parameter.wrapsSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.get">Get</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.get"></a>

```go
func Get(index *f64) TeamRoutingRuleTimeRestrictionOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.get.parameter.index"></a>

- *Type:* *f64

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### TeamRoutingRuleTimeRestrictionOutputReference <a name="TeamRoutingRuleTimeRestrictionOutputReference" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/teamroutingrule"

teamroutingrule.NewTeamRoutingRuleTimeRestrictionOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string, complexObjectIndex *f64, complexObjectIsFromSet *bool) TeamRoutingRuleTimeRestrictionOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>*f64</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* *f64

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.putRestriction">PutRestriction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.putRestrictions">PutRestrictions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.resetRestriction">ResetRestriction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.resetRestrictions">ResetRestrictions</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `PutRestriction` <a name="PutRestriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.putRestriction"></a>

```go
func PutRestriction(value interface{})
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.putRestriction.parameter.value"></a>

- *Type:* interface{}

---

##### `PutRestrictions` <a name="PutRestrictions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.putRestrictions"></a>

```go
func PutRestrictions(value interface{})
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.putRestrictions.parameter.value"></a>

- *Type:* interface{}

---

##### `ResetRestriction` <a name="ResetRestriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.resetRestriction"></a>

```go
func ResetRestriction()
```

##### `ResetRestrictions` <a name="ResetRestrictions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.resetRestrictions"></a>

```go
func ResetRestrictions()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restriction">Restriction</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList">TeamRoutingRuleTimeRestrictionRestrictionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restrictions">Restrictions</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList">TeamRoutingRuleTimeRestrictionRestrictionsList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restrictionInput">RestrictionInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restrictionsInput">RestrictionsInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.typeInput">TypeInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.type">Type</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `Restriction`<sup>Required</sup> <a name="Restriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restriction"></a>

```go
func Restriction() TeamRoutingRuleTimeRestrictionRestrictionList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList">TeamRoutingRuleTimeRestrictionRestrictionList</a>

---

##### `Restrictions`<sup>Required</sup> <a name="Restrictions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restrictions"></a>

```go
func Restrictions() TeamRoutingRuleTimeRestrictionRestrictionsList
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList">TeamRoutingRuleTimeRestrictionRestrictionsList</a>

---

##### `RestrictionInput`<sup>Optional</sup> <a name="RestrictionInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restrictionInput"></a>

```go
func RestrictionInput() interface{}
```

- *Type:* interface{}

---

##### `RestrictionsInput`<sup>Optional</sup> <a name="RestrictionsInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restrictionsInput"></a>

```go
func RestrictionsInput() interface{}
```

- *Type:* interface{}

---

##### `TypeInput`<sup>Optional</sup> <a name="TypeInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.typeInput"></a>

```go
func TypeInput() *string
```

- *Type:* *string

---

##### `Type`<sup>Required</sup> <a name="Type" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.type"></a>

```go
func Type() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### TeamRoutingRuleTimeRestrictionRestrictionList <a name="TeamRoutingRuleTimeRestrictionRestrictionList" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/teamroutingrule"

teamroutingrule.NewTeamRoutingRuleTimeRestrictionRestrictionList(terraformResource IInterpolatingParent, terraformAttribute *string, wrapsSet *bool) TeamRoutingRuleTimeRestrictionRestrictionList
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.Initializer.parameter.wrapsSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.get">Get</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.get"></a>

```go
func Get(index *f64) TeamRoutingRuleTimeRestrictionRestrictionOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.get.parameter.index"></a>

- *Type:* *f64

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### TeamRoutingRuleTimeRestrictionRestrictionOutputReference <a name="TeamRoutingRuleTimeRestrictionRestrictionOutputReference" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/teamroutingrule"

teamroutingrule.NewTeamRoutingRuleTimeRestrictionRestrictionOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string, complexObjectIndex *f64, complexObjectIsFromSet *bool) TeamRoutingRuleTimeRestrictionRestrictionOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>*f64</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* *f64

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endHourInput">EndHourInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endMinInput">EndMinInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startHourInput">StartHourInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startMinInput">StartMinInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endHour">EndHour</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endMin">EndMin</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startHour">StartHour</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startMin">StartMin</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `EndHourInput`<sup>Optional</sup> <a name="EndHourInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endHourInput"></a>

```go
func EndHourInput() *f64
```

- *Type:* *f64

---

##### `EndMinInput`<sup>Optional</sup> <a name="EndMinInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endMinInput"></a>

```go
func EndMinInput() *f64
```

- *Type:* *f64

---

##### `StartHourInput`<sup>Optional</sup> <a name="StartHourInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startHourInput"></a>

```go
func StartHourInput() *f64
```

- *Type:* *f64

---

##### `StartMinInput`<sup>Optional</sup> <a name="StartMinInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startMinInput"></a>

```go
func StartMinInput() *f64
```

- *Type:* *f64

---

##### `EndHour`<sup>Required</sup> <a name="EndHour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endHour"></a>

```go
func EndHour() *f64
```

- *Type:* *f64

---

##### `EndMin`<sup>Required</sup> <a name="EndMin" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endMin"></a>

```go
func EndMin() *f64
```

- *Type:* *f64

---

##### `StartHour`<sup>Required</sup> <a name="StartHour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startHour"></a>

```go
func StartHour() *f64
```

- *Type:* *f64

---

##### `StartMin`<sup>Required</sup> <a name="StartMin" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startMin"></a>

```go
func StartMin() *f64
```

- *Type:* *f64

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### TeamRoutingRuleTimeRestrictionRestrictionsList <a name="TeamRoutingRuleTimeRestrictionRestrictionsList" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/teamroutingrule"

teamroutingrule.NewTeamRoutingRuleTimeRestrictionRestrictionsList(terraformResource IInterpolatingParent, terraformAttribute *string, wrapsSet *bool) TeamRoutingRuleTimeRestrictionRestrictionsList
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.Initializer.parameter.wrapsSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.get">Get</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.get"></a>

```go
func Get(index *f64) TeamRoutingRuleTimeRestrictionRestrictionsOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.get.parameter.index"></a>

- *Type:* *f64

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---


### TeamRoutingRuleTimeRestrictionRestrictionsOutputReference <a name="TeamRoutingRuleTimeRestrictionRestrictionsOutputReference" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/teamroutingrule"

teamroutingrule.NewTeamRoutingRuleTimeRestrictionRestrictionsOutputReference(terraformResource IInterpolatingParent, terraformAttribute *string, complexObjectIndex *f64, complexObjectIsFromSet *bool) TeamRoutingRuleTimeRestrictionRestrictionsOutputReference
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>*string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>*f64</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>*bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* *string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* *f64

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* *bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.computeFqn"></a>

```go
func ComputeFqn() *string
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(property *string) IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* *string

---

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.resolve"></a>

```go
func Resolve(_context IResolveContext) interface{}
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.resolve.parameter._context"></a>

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.toString"></a>

```go
func ToString() *string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.creationStack">CreationStack</a></code> | <code>*[]*string</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endDayInput">EndDayInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endHourInput">EndHourInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endMinInput">EndMinInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startDayInput">StartDayInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startHourInput">StartHourInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startMinInput">StartMinInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endDay">EndDay</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endHour">EndHour</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endMin">EndMin</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startDay">StartDay</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startHour">StartHour</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startMin">StartMin</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.internalValue">InternalValue</a></code> | <code>interface{}</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.creationStack"></a>

```go
func CreationStack() *[]*string
```

- *Type:* *[]*string

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `EndDayInput`<sup>Optional</sup> <a name="EndDayInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endDayInput"></a>

```go
func EndDayInput() *string
```

- *Type:* *string

---

##### `EndHourInput`<sup>Optional</sup> <a name="EndHourInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endHourInput"></a>

```go
func EndHourInput() *f64
```

- *Type:* *f64

---

##### `EndMinInput`<sup>Optional</sup> <a name="EndMinInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endMinInput"></a>

```go
func EndMinInput() *f64
```

- *Type:* *f64

---

##### `StartDayInput`<sup>Optional</sup> <a name="StartDayInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startDayInput"></a>

```go
func StartDayInput() *string
```

- *Type:* *string

---

##### `StartHourInput`<sup>Optional</sup> <a name="StartHourInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startHourInput"></a>

```go
func StartHourInput() *f64
```

- *Type:* *f64

---

##### `StartMinInput`<sup>Optional</sup> <a name="StartMinInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startMinInput"></a>

```go
func StartMinInput() *f64
```

- *Type:* *f64

---

##### `EndDay`<sup>Required</sup> <a name="EndDay" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endDay"></a>

```go
func EndDay() *string
```

- *Type:* *string

---

##### `EndHour`<sup>Required</sup> <a name="EndHour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endHour"></a>

```go
func EndHour() *f64
```

- *Type:* *f64

---

##### `EndMin`<sup>Required</sup> <a name="EndMin" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endMin"></a>

```go
func EndMin() *f64
```

- *Type:* *f64

---

##### `StartDay`<sup>Required</sup> <a name="StartDay" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startDay"></a>

```go
func StartDay() *string
```

- *Type:* *string

---

##### `StartHour`<sup>Required</sup> <a name="StartHour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startHour"></a>

```go
func StartHour() *f64
```

- *Type:* *f64

---

##### `StartMin`<sup>Required</sup> <a name="StartMin" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startMin"></a>

```go
func StartMin() *f64
```

- *Type:* *f64

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.internalValue"></a>

```go
func InternalValue() interface{}
```

- *Type:* interface{}

---



