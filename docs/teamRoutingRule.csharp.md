# `opsgenie_team_routing_rule`

Refer to the Terraform Registory for docs: [`opsgenie_team_routing_rule`](https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule).

# `teamRoutingRule` Submodule <a name="`teamRoutingRule` Submodule" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### TeamRoutingRule <a name="TeamRoutingRule" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule"></a>

Represents a {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule opsgenie_team_routing_rule}.

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new TeamRoutingRule(Construct Scope, string Id, TeamRoutingRuleConfig Config);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.scope">Scope</a></code> | <code>Constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.id">Id</a></code> | <code>string</code> | The scoped construct ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.config">Config</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig">TeamRoutingRuleConfig</a></code> | *No description.* |

---

##### `Scope`<sup>Required</sup> <a name="Scope" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.scope"></a>

- *Type:* Constructs.Construct

The scope in which to define this construct.

---

##### `Id`<sup>Required</sup> <a name="Id" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.id"></a>

- *Type:* string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `Config`<sup>Required</sup> <a name="Config" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.config"></a>

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

```csharp
private string ToString()
```

Returns a string representation of this construct.

##### `AddOverride` <a name="AddOverride" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.addOverride"></a>

```csharp
private void AddOverride(string Path, object Value)
```

###### `Path`<sup>Required</sup> <a name="Path" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.addOverride.parameter.path"></a>

- *Type:* string

---

###### `Value`<sup>Required</sup> <a name="Value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.addOverride.parameter.value"></a>

- *Type:* object

---

##### `OverrideLogicalId` <a name="OverrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.overrideLogicalId"></a>

```csharp
private void OverrideLogicalId(string NewLogicalId)
```

Overrides the auto-generated logical ID with a specific ID.

###### `NewLogicalId`<sup>Required</sup> <a name="NewLogicalId" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* string

The new logical ID to use for this stack element.

---

##### `ResetOverrideLogicalId` <a name="ResetOverrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetOverrideLogicalId"></a>

```csharp
private void ResetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `ToMetadata` <a name="ToMetadata" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.toMetadata"></a>

```csharp
private object ToMetadata()
```

##### `ToTerraform` <a name="ToTerraform" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.toTerraform"></a>

```csharp
private object ToTerraform()
```

Adds this resource to the terraform JSON output.

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `PutCriteria` <a name="PutCriteria" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putCriteria"></a>

```csharp
private void PutCriteria(object Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putCriteria.parameter.value"></a>

- *Type:* object

---

##### `PutNotify` <a name="PutNotify" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putNotify"></a>

```csharp
private void PutNotify(object Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putNotify.parameter.value"></a>

- *Type:* object

---

##### `PutTimeRestriction` <a name="PutTimeRestriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putTimeRestriction"></a>

```csharp
private void PutTimeRestriction(object Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putTimeRestriction.parameter.value"></a>

- *Type:* object

---

##### `ResetCriteria` <a name="ResetCriteria" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetCriteria"></a>

```csharp
private void ResetCriteria()
```

##### `ResetId` <a name="ResetId" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetId"></a>

```csharp
private void ResetId()
```

##### `ResetIsDefault` <a name="ResetIsDefault" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetIsDefault"></a>

```csharp
private void ResetIsDefault()
```

##### `ResetName` <a name="ResetName" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetName"></a>

```csharp
private void ResetName()
```

##### `ResetOrder` <a name="ResetOrder" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetOrder"></a>

```csharp
private void ResetOrder()
```

##### `ResetTimeRestriction` <a name="ResetTimeRestriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetTimeRestriction"></a>

```csharp
private void ResetTimeRestriction()
```

##### `ResetTimezone` <a name="ResetTimezone" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetTimezone"></a>

```csharp
private void ResetTimezone()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isConstruct">IsConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isTerraformElement">IsTerraformElement</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isTerraformResource">IsTerraformResource</a></code> | *No description.* |

---

##### `IsConstruct` <a name="IsConstruct" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isConstruct"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

TeamRoutingRule.IsConstruct(object X);
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

###### `X`<sup>Required</sup> <a name="X" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isConstruct.parameter.x"></a>

- *Type:* object

Any object.

---

##### `IsTerraformElement` <a name="IsTerraformElement" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isTerraformElement"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

TeamRoutingRule.IsTerraformElement(object X);
```

###### `X`<sup>Required</sup> <a name="X" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isTerraformElement.parameter.x"></a>

- *Type:* object

---

##### `IsTerraformResource` <a name="IsTerraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isTerraformResource"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

TeamRoutingRule.IsTerraformResource(object X);
```

###### `X`<sup>Required</sup> <a name="X" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isTerraformResource.parameter.x"></a>

- *Type:* object

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.node">Node</a></code> | <code>Constructs.Node</code> | The tree node. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.cdktfStack">CdktfStack</a></code> | <code>HashiCorp.Cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.friendlyUniqueId">FriendlyUniqueId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.terraformMetaArguments">TerraformMetaArguments</a></code> | <code>System.Collections.Generic.IDictionary<string, object></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.terraformResourceType">TerraformResourceType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.terraformGeneratorMetadata">TerraformGeneratorMetadata</a></code> | <code>HashiCorp.Cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.connection">Connection</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.count">Count</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.dependsOn">DependsOn</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.forEach">ForEach</a></code> | <code>HashiCorp.Cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.lifecycle">Lifecycle</a></code> | <code>HashiCorp.Cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.provider">Provider</a></code> | <code>HashiCorp.Cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.provisioners">Provisioners</a></code> | <code>object[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.criteria">Criteria</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList">TeamRoutingRuleCriteriaList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.notify">Notify</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList">TeamRoutingRuleNotifyList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timeRestriction">TimeRestriction</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList">TeamRoutingRuleTimeRestrictionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.criteriaInput">CriteriaInput</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.idInput">IdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.isDefaultInput">IsDefaultInput</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.nameInput">NameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.notifyInput">NotifyInput</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.orderInput">OrderInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.teamIdInput">TeamIdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timeRestrictionInput">TimeRestrictionInput</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timezoneInput">TimezoneInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.id">Id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.isDefault">IsDefault</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.name">Name</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.order">Order</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.teamId">TeamId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timezone">Timezone</a></code> | <code>string</code> | *No description.* |

---

##### `Node`<sup>Required</sup> <a name="Node" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.node"></a>

```csharp
public Node Node { get; }
```

- *Type:* Constructs.Node

The tree node.

---

##### `CdktfStack`<sup>Required</sup> <a name="CdktfStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.cdktfStack"></a>

```csharp
public TerraformStack CdktfStack { get; }
```

- *Type:* HashiCorp.Cdktf.TerraformStack

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `FriendlyUniqueId`<sup>Required</sup> <a name="FriendlyUniqueId" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.friendlyUniqueId"></a>

```csharp
public string FriendlyUniqueId { get; }
```

- *Type:* string

---

##### `TerraformMetaArguments`<sup>Required</sup> <a name="TerraformMetaArguments" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.terraformMetaArguments"></a>

```csharp
public System.Collections.Generic.IDictionary<string, object> TerraformMetaArguments { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, object>

---

##### `TerraformResourceType`<sup>Required</sup> <a name="TerraformResourceType" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.terraformResourceType"></a>

```csharp
public string TerraformResourceType { get; }
```

- *Type:* string

---

##### `TerraformGeneratorMetadata`<sup>Optional</sup> <a name="TerraformGeneratorMetadata" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.terraformGeneratorMetadata"></a>

```csharp
public TerraformProviderGeneratorMetadata TerraformGeneratorMetadata { get; }
```

- *Type:* HashiCorp.Cdktf.TerraformProviderGeneratorMetadata

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.connection"></a>

```csharp
public object Connection { get; }
```

- *Type:* object

---

##### `Count`<sup>Optional</sup> <a name="Count" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.count"></a>

```csharp
public object Count { get; }
```

- *Type:* object

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.dependsOn"></a>

```csharp
public string[] DependsOn { get; }
```

- *Type:* string[]

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.forEach"></a>

```csharp
public ITerraformIterator ForEach { get; }
```

- *Type:* HashiCorp.Cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.lifecycle"></a>

```csharp
public TerraformResourceLifecycle Lifecycle { get; }
```

- *Type:* HashiCorp.Cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.provider"></a>

```csharp
public TerraformProvider Provider { get; }
```

- *Type:* HashiCorp.Cdktf.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.provisioners"></a>

```csharp
public object[] Provisioners { get; }
```

- *Type:* object[]

---

##### `Criteria`<sup>Required</sup> <a name="Criteria" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.criteria"></a>

```csharp
public TeamRoutingRuleCriteriaList Criteria { get; }
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList">TeamRoutingRuleCriteriaList</a>

---

##### `Notify`<sup>Required</sup> <a name="Notify" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.notify"></a>

```csharp
public TeamRoutingRuleNotifyList Notify { get; }
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList">TeamRoutingRuleNotifyList</a>

---

##### `TimeRestriction`<sup>Required</sup> <a name="TimeRestriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timeRestriction"></a>

```csharp
public TeamRoutingRuleTimeRestrictionList TimeRestriction { get; }
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList">TeamRoutingRuleTimeRestrictionList</a>

---

##### `CriteriaInput`<sup>Optional</sup> <a name="CriteriaInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.criteriaInput"></a>

```csharp
public object CriteriaInput { get; }
```

- *Type:* object

---

##### `IdInput`<sup>Optional</sup> <a name="IdInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.idInput"></a>

```csharp
public string IdInput { get; }
```

- *Type:* string

---

##### `IsDefaultInput`<sup>Optional</sup> <a name="IsDefaultInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.isDefaultInput"></a>

```csharp
public object IsDefaultInput { get; }
```

- *Type:* object

---

##### `NameInput`<sup>Optional</sup> <a name="NameInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.nameInput"></a>

```csharp
public string NameInput { get; }
```

- *Type:* string

---

##### `NotifyInput`<sup>Optional</sup> <a name="NotifyInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.notifyInput"></a>

```csharp
public object NotifyInput { get; }
```

- *Type:* object

---

##### `OrderInput`<sup>Optional</sup> <a name="OrderInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.orderInput"></a>

```csharp
public double OrderInput { get; }
```

- *Type:* double

---

##### `TeamIdInput`<sup>Optional</sup> <a name="TeamIdInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.teamIdInput"></a>

```csharp
public string TeamIdInput { get; }
```

- *Type:* string

---

##### `TimeRestrictionInput`<sup>Optional</sup> <a name="TimeRestrictionInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timeRestrictionInput"></a>

```csharp
public object TimeRestrictionInput { get; }
```

- *Type:* object

---

##### `TimezoneInput`<sup>Optional</sup> <a name="TimezoneInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timezoneInput"></a>

```csharp
public string TimezoneInput { get; }
```

- *Type:* string

---

##### `Id`<sup>Required</sup> <a name="Id" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.id"></a>

```csharp
public string Id { get; }
```

- *Type:* string

---

##### `IsDefault`<sup>Required</sup> <a name="IsDefault" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.isDefault"></a>

```csharp
public object IsDefault { get; }
```

- *Type:* object

---

##### `Name`<sup>Required</sup> <a name="Name" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.name"></a>

```csharp
public string Name { get; }
```

- *Type:* string

---

##### `Order`<sup>Required</sup> <a name="Order" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.order"></a>

```csharp
public double Order { get; }
```

- *Type:* double

---

##### `TeamId`<sup>Required</sup> <a name="TeamId" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.teamId"></a>

```csharp
public string TeamId { get; }
```

- *Type:* string

---

##### `Timezone`<sup>Required</sup> <a name="Timezone" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timezone"></a>

```csharp
public string Timezone { get; }
```

- *Type:* string

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.tfResourceType">TfResourceType</a></code> | <code>string</code> | *No description.* |

---

##### `TfResourceType`<sup>Required</sup> <a name="TfResourceType" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.tfResourceType"></a>

```csharp
public string TfResourceType { get; }
```

- *Type:* string

---

## Structs <a name="Structs" id="Structs"></a>

### TeamRoutingRuleConfig <a name="TeamRoutingRuleConfig" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new TeamRoutingRuleConfig {
    object Connection = null,
    object Count = null,
    ITerraformDependable[] DependsOn = null,
    ITerraformIterator ForEach = null,
    TerraformResourceLifecycle Lifecycle = null,
    TerraformProvider Provider = null,
    object[] Provisioners = null,
    object Notify,
    string TeamId,
    object Criteria = null,
    string Id = null,
    object IsDefault = null,
    string Name = null,
    double Order = null,
    object TimeRestriction = null,
    string Timezone = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.connection">Connection</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.count">Count</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.dependsOn">DependsOn</a></code> | <code>HashiCorp.Cdktf.ITerraformDependable[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.forEach">ForEach</a></code> | <code>HashiCorp.Cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.lifecycle">Lifecycle</a></code> | <code>HashiCorp.Cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.provider">Provider</a></code> | <code>HashiCorp.Cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.provisioners">Provisioners</a></code> | <code>object[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.notify">Notify</a></code> | <code>object</code> | notify block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.teamId">TeamId</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#team_id TeamRoutingRule#team_id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.criteria">Criteria</a></code> | <code>object</code> | criteria block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.id">Id</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#id TeamRoutingRule#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.isDefault">IsDefault</a></code> | <code>object</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#is_default TeamRoutingRule#is_default}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.name">Name</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#name TeamRoutingRule#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.order">Order</a></code> | <code>double</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#order TeamRoutingRule#order}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.timeRestriction">TimeRestriction</a></code> | <code>object</code> | time_restriction block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.timezone">Timezone</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#timezone TeamRoutingRule#timezone}. |

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.connection"></a>

```csharp
public object Connection { get; set; }
```

- *Type:* object

---

##### `Count`<sup>Optional</sup> <a name="Count" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.count"></a>

```csharp
public object Count { get; set; }
```

- *Type:* object

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.dependsOn"></a>

```csharp
public ITerraformDependable[] DependsOn { get; set; }
```

- *Type:* HashiCorp.Cdktf.ITerraformDependable[]

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.forEach"></a>

```csharp
public ITerraformIterator ForEach { get; set; }
```

- *Type:* HashiCorp.Cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.lifecycle"></a>

```csharp
public TerraformResourceLifecycle Lifecycle { get; set; }
```

- *Type:* HashiCorp.Cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.provider"></a>

```csharp
public TerraformProvider Provider { get; set; }
```

- *Type:* HashiCorp.Cdktf.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.provisioners"></a>

```csharp
public object[] Provisioners { get; set; }
```

- *Type:* object[]

---

##### `Notify`<sup>Required</sup> <a name="Notify" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.notify"></a>

```csharp
public object Notify { get; set; }
```

- *Type:* object

notify block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#notify TeamRoutingRule#notify}

---

##### `TeamId`<sup>Required</sup> <a name="TeamId" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.teamId"></a>

```csharp
public string TeamId { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#team_id TeamRoutingRule#team_id}.

---

##### `Criteria`<sup>Optional</sup> <a name="Criteria" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.criteria"></a>

```csharp
public object Criteria { get; set; }
```

- *Type:* object

criteria block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#criteria TeamRoutingRule#criteria}

---

##### `Id`<sup>Optional</sup> <a name="Id" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.id"></a>

```csharp
public string Id { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#id TeamRoutingRule#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `IsDefault`<sup>Optional</sup> <a name="IsDefault" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.isDefault"></a>

```csharp
public object IsDefault { get; set; }
```

- *Type:* object

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#is_default TeamRoutingRule#is_default}.

---

##### `Name`<sup>Optional</sup> <a name="Name" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.name"></a>

```csharp
public string Name { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#name TeamRoutingRule#name}.

---

##### `Order`<sup>Optional</sup> <a name="Order" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.order"></a>

```csharp
public double Order { get; set; }
```

- *Type:* double

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#order TeamRoutingRule#order}.

---

##### `TimeRestriction`<sup>Optional</sup> <a name="TimeRestriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.timeRestriction"></a>

```csharp
public object TimeRestriction { get; set; }
```

- *Type:* object

time_restriction block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#time_restriction TeamRoutingRule#time_restriction}

---

##### `Timezone`<sup>Optional</sup> <a name="Timezone" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.timezone"></a>

```csharp
public string Timezone { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#timezone TeamRoutingRule#timezone}.

---

### TeamRoutingRuleCriteria <a name="TeamRoutingRuleCriteria" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new TeamRoutingRuleCriteria {
    string Type,
    object Conditions = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria.property.type">Type</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#type TeamRoutingRule#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria.property.conditions">Conditions</a></code> | <code>object</code> | conditions block. |

---

##### `Type`<sup>Required</sup> <a name="Type" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria.property.type"></a>

```csharp
public string Type { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#type TeamRoutingRule#type}.

---

##### `Conditions`<sup>Optional</sup> <a name="Conditions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria.property.conditions"></a>

```csharp
public object Conditions { get; set; }
```

- *Type:* object

conditions block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#conditions TeamRoutingRule#conditions}

---

### TeamRoutingRuleCriteriaConditions <a name="TeamRoutingRuleCriteriaConditions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new TeamRoutingRuleCriteriaConditions {
    string Field,
    string Operation,
    string ExpectedValue = null,
    string Key = null,
    object Not = null,
    double Order = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.field">Field</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#field TeamRoutingRule#field}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.operation">Operation</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#operation TeamRoutingRule#operation}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.expectedValue">ExpectedValue</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#expected_value TeamRoutingRule#expected_value}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.key">Key</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#key TeamRoutingRule#key}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.not">Not</a></code> | <code>object</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#not TeamRoutingRule#not}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.order">Order</a></code> | <code>double</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#order TeamRoutingRule#order}. |

---

##### `Field`<sup>Required</sup> <a name="Field" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.field"></a>

```csharp
public string Field { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#field TeamRoutingRule#field}.

---

##### `Operation`<sup>Required</sup> <a name="Operation" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.operation"></a>

```csharp
public string Operation { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#operation TeamRoutingRule#operation}.

---

##### `ExpectedValue`<sup>Optional</sup> <a name="ExpectedValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.expectedValue"></a>

```csharp
public string ExpectedValue { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#expected_value TeamRoutingRule#expected_value}.

---

##### `Key`<sup>Optional</sup> <a name="Key" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.key"></a>

```csharp
public string Key { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#key TeamRoutingRule#key}.

---

##### `Not`<sup>Optional</sup> <a name="Not" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.not"></a>

```csharp
public object Not { get; set; }
```

- *Type:* object

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#not TeamRoutingRule#not}.

---

##### `Order`<sup>Optional</sup> <a name="Order" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.order"></a>

```csharp
public double Order { get; set; }
```

- *Type:* double

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#order TeamRoutingRule#order}.

---

### TeamRoutingRuleNotify <a name="TeamRoutingRuleNotify" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new TeamRoutingRuleNotify {
    string Type,
    string Id = null,
    string Name = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify.property.type">Type</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#type TeamRoutingRule#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify.property.id">Id</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#id TeamRoutingRule#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify.property.name">Name</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#name TeamRoutingRule#name}. |

---

##### `Type`<sup>Required</sup> <a name="Type" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify.property.type"></a>

```csharp
public string Type { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#type TeamRoutingRule#type}.

---

##### `Id`<sup>Optional</sup> <a name="Id" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify.property.id"></a>

```csharp
public string Id { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#id TeamRoutingRule#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `Name`<sup>Optional</sup> <a name="Name" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify.property.name"></a>

```csharp
public string Name { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#name TeamRoutingRule#name}.

---

### TeamRoutingRuleTimeRestriction <a name="TeamRoutingRuleTimeRestriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new TeamRoutingRuleTimeRestriction {
    string Type,
    object Restriction = null,
    object Restrictions = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction.property.type">Type</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#type TeamRoutingRule#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction.property.restriction">Restriction</a></code> | <code>object</code> | restriction block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction.property.restrictions">Restrictions</a></code> | <code>object</code> | restrictions block. |

---

##### `Type`<sup>Required</sup> <a name="Type" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction.property.type"></a>

```csharp
public string Type { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#type TeamRoutingRule#type}.

---

##### `Restriction`<sup>Optional</sup> <a name="Restriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction.property.restriction"></a>

```csharp
public object Restriction { get; set; }
```

- *Type:* object

restriction block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#restriction TeamRoutingRule#restriction}

---

##### `Restrictions`<sup>Optional</sup> <a name="Restrictions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction.property.restrictions"></a>

```csharp
public object Restrictions { get; set; }
```

- *Type:* object

restrictions block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#restrictions TeamRoutingRule#restrictions}

---

### TeamRoutingRuleTimeRestrictionRestriction <a name="TeamRoutingRuleTimeRestrictionRestriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new TeamRoutingRuleTimeRestrictionRestriction {
    double EndHour,
    double EndMin,
    double StartHour,
    double StartMin
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.endHour">EndHour</a></code> | <code>double</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_hour TeamRoutingRule#end_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.endMin">EndMin</a></code> | <code>double</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_min TeamRoutingRule#end_min}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.startHour">StartHour</a></code> | <code>double</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_hour TeamRoutingRule#start_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.startMin">StartMin</a></code> | <code>double</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_min TeamRoutingRule#start_min}. |

---

##### `EndHour`<sup>Required</sup> <a name="EndHour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.endHour"></a>

```csharp
public double EndHour { get; set; }
```

- *Type:* double

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_hour TeamRoutingRule#end_hour}.

---

##### `EndMin`<sup>Required</sup> <a name="EndMin" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.endMin"></a>

```csharp
public double EndMin { get; set; }
```

- *Type:* double

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_min TeamRoutingRule#end_min}.

---

##### `StartHour`<sup>Required</sup> <a name="StartHour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.startHour"></a>

```csharp
public double StartHour { get; set; }
```

- *Type:* double

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_hour TeamRoutingRule#start_hour}.

---

##### `StartMin`<sup>Required</sup> <a name="StartMin" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.startMin"></a>

```csharp
public double StartMin { get; set; }
```

- *Type:* double

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_min TeamRoutingRule#start_min}.

---

### TeamRoutingRuleTimeRestrictionRestrictions <a name="TeamRoutingRuleTimeRestrictionRestrictions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new TeamRoutingRuleTimeRestrictionRestrictions {
    string EndDay,
    double EndHour,
    double EndMin,
    string StartDay,
    double StartHour,
    double StartMin
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.endDay">EndDay</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_day TeamRoutingRule#end_day}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.endHour">EndHour</a></code> | <code>double</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_hour TeamRoutingRule#end_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.endMin">EndMin</a></code> | <code>double</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_min TeamRoutingRule#end_min}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.startDay">StartDay</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_day TeamRoutingRule#start_day}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.startHour">StartHour</a></code> | <code>double</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_hour TeamRoutingRule#start_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.startMin">StartMin</a></code> | <code>double</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_min TeamRoutingRule#start_min}. |

---

##### `EndDay`<sup>Required</sup> <a name="EndDay" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.endDay"></a>

```csharp
public string EndDay { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_day TeamRoutingRule#end_day}.

---

##### `EndHour`<sup>Required</sup> <a name="EndHour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.endHour"></a>

```csharp
public double EndHour { get; set; }
```

- *Type:* double

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_hour TeamRoutingRule#end_hour}.

---

##### `EndMin`<sup>Required</sup> <a name="EndMin" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.endMin"></a>

```csharp
public double EndMin { get; set; }
```

- *Type:* double

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_min TeamRoutingRule#end_min}.

---

##### `StartDay`<sup>Required</sup> <a name="StartDay" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.startDay"></a>

```csharp
public string StartDay { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_day TeamRoutingRule#start_day}.

---

##### `StartHour`<sup>Required</sup> <a name="StartHour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.startHour"></a>

```csharp
public double StartHour { get; set; }
```

- *Type:* double

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_hour TeamRoutingRule#start_hour}.

---

##### `StartMin`<sup>Required</sup> <a name="StartMin" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.startMin"></a>

```csharp
public double StartMin { get; set; }
```

- *Type:* double

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_min TeamRoutingRule#start_min}.

---

## Classes <a name="Classes" id="Classes"></a>

### TeamRoutingRuleCriteriaConditionsList <a name="TeamRoutingRuleCriteriaConditionsList" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new TeamRoutingRuleCriteriaConditionsList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>HashiCorp.Cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.Initializer.parameter.terraformResource"></a>

- *Type:* HashiCorp.Cdktf.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

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

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.resolve.parameter._context"></a>

- *Type:* HashiCorp.Cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.get"></a>

```csharp
private TeamRoutingRuleCriteriaConditionsOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.property.internalValue">InternalValue</a></code> | <code>object</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.property.internalValue"></a>

```csharp
public object InternalValue { get; }
```

- *Type:* object

---


### TeamRoutingRuleCriteriaConditionsOutputReference <a name="TeamRoutingRuleCriteriaConditionsOutputReference" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new TeamRoutingRuleCriteriaConditionsOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>HashiCorp.Cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* HashiCorp.Cdktf.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

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

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resolve.parameter._context"></a>

- *Type:* HashiCorp.Cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetExpectedValue` <a name="ResetExpectedValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resetExpectedValue"></a>

```csharp
private void ResetExpectedValue()
```

##### `ResetKey` <a name="ResetKey" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resetKey"></a>

```csharp
private void ResetKey()
```

##### `ResetNot` <a name="ResetNot" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resetNot"></a>

```csharp
private void ResetNot()
```

##### `ResetOrder` <a name="ResetOrder" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resetOrder"></a>

```csharp
private void ResetOrder()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.expectedValueInput">ExpectedValueInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.fieldInput">FieldInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.keyInput">KeyInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.notInput">NotInput</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.operationInput">OperationInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.orderInput">OrderInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.expectedValue">ExpectedValue</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.field">Field</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.key">Key</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.not">Not</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.operation">Operation</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.order">Order</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.internalValue">InternalValue</a></code> | <code>object</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `ExpectedValueInput`<sup>Optional</sup> <a name="ExpectedValueInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.expectedValueInput"></a>

```csharp
public string ExpectedValueInput { get; }
```

- *Type:* string

---

##### `FieldInput`<sup>Optional</sup> <a name="FieldInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.fieldInput"></a>

```csharp
public string FieldInput { get; }
```

- *Type:* string

---

##### `KeyInput`<sup>Optional</sup> <a name="KeyInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.keyInput"></a>

```csharp
public string KeyInput { get; }
```

- *Type:* string

---

##### `NotInput`<sup>Optional</sup> <a name="NotInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.notInput"></a>

```csharp
public object NotInput { get; }
```

- *Type:* object

---

##### `OperationInput`<sup>Optional</sup> <a name="OperationInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.operationInput"></a>

```csharp
public string OperationInput { get; }
```

- *Type:* string

---

##### `OrderInput`<sup>Optional</sup> <a name="OrderInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.orderInput"></a>

```csharp
public double OrderInput { get; }
```

- *Type:* double

---

##### `ExpectedValue`<sup>Required</sup> <a name="ExpectedValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.expectedValue"></a>

```csharp
public string ExpectedValue { get; }
```

- *Type:* string

---

##### `Field`<sup>Required</sup> <a name="Field" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.field"></a>

```csharp
public string Field { get; }
```

- *Type:* string

---

##### `Key`<sup>Required</sup> <a name="Key" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.key"></a>

```csharp
public string Key { get; }
```

- *Type:* string

---

##### `Not`<sup>Required</sup> <a name="Not" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.not"></a>

```csharp
public object Not { get; }
```

- *Type:* object

---

##### `Operation`<sup>Required</sup> <a name="Operation" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.operation"></a>

```csharp
public string Operation { get; }
```

- *Type:* string

---

##### `Order`<sup>Required</sup> <a name="Order" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.order"></a>

```csharp
public double Order { get; }
```

- *Type:* double

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.internalValue"></a>

```csharp
public object InternalValue { get; }
```

- *Type:* object

---


### TeamRoutingRuleCriteriaList <a name="TeamRoutingRuleCriteriaList" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new TeamRoutingRuleCriteriaList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>HashiCorp.Cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.Initializer.parameter.terraformResource"></a>

- *Type:* HashiCorp.Cdktf.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

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

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.resolve.parameter._context"></a>

- *Type:* HashiCorp.Cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.get"></a>

```csharp
private TeamRoutingRuleCriteriaOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.property.internalValue">InternalValue</a></code> | <code>object</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.property.internalValue"></a>

```csharp
public object InternalValue { get; }
```

- *Type:* object

---


### TeamRoutingRuleCriteriaOutputReference <a name="TeamRoutingRuleCriteriaOutputReference" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new TeamRoutingRuleCriteriaOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>HashiCorp.Cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* HashiCorp.Cdktf.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

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

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.resolve.parameter._context"></a>

- *Type:* HashiCorp.Cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `PutConditions` <a name="PutConditions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.putConditions"></a>

```csharp
private void PutConditions(object Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.putConditions.parameter.value"></a>

- *Type:* object

---

##### `ResetConditions` <a name="ResetConditions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.resetConditions"></a>

```csharp
private void ResetConditions()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.conditions">Conditions</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList">TeamRoutingRuleCriteriaConditionsList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.conditionsInput">ConditionsInput</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.typeInput">TypeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.type">Type</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.internalValue">InternalValue</a></code> | <code>object</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `Conditions`<sup>Required</sup> <a name="Conditions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.conditions"></a>

```csharp
public TeamRoutingRuleCriteriaConditionsList Conditions { get; }
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList">TeamRoutingRuleCriteriaConditionsList</a>

---

##### `ConditionsInput`<sup>Optional</sup> <a name="ConditionsInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.conditionsInput"></a>

```csharp
public object ConditionsInput { get; }
```

- *Type:* object

---

##### `TypeInput`<sup>Optional</sup> <a name="TypeInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.typeInput"></a>

```csharp
public string TypeInput { get; }
```

- *Type:* string

---

##### `Type`<sup>Required</sup> <a name="Type" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.type"></a>

```csharp
public string Type { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.internalValue"></a>

```csharp
public object InternalValue { get; }
```

- *Type:* object

---


### TeamRoutingRuleNotifyList <a name="TeamRoutingRuleNotifyList" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new TeamRoutingRuleNotifyList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>HashiCorp.Cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.Initializer.parameter.terraformResource"></a>

- *Type:* HashiCorp.Cdktf.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

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

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.resolve.parameter._context"></a>

- *Type:* HashiCorp.Cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.get"></a>

```csharp
private TeamRoutingRuleNotifyOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.property.internalValue">InternalValue</a></code> | <code>object</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.property.internalValue"></a>

```csharp
public object InternalValue { get; }
```

- *Type:* object

---


### TeamRoutingRuleNotifyOutputReference <a name="TeamRoutingRuleNotifyOutputReference" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new TeamRoutingRuleNotifyOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>HashiCorp.Cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* HashiCorp.Cdktf.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

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

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.resolve.parameter._context"></a>

- *Type:* HashiCorp.Cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetId` <a name="ResetId" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.resetId"></a>

```csharp
private void ResetId()
```

##### `ResetName` <a name="ResetName" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.resetName"></a>

```csharp
private void ResetName()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.idInput">IdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.nameInput">NameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.typeInput">TypeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.id">Id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.name">Name</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.type">Type</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.internalValue">InternalValue</a></code> | <code>object</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `IdInput`<sup>Optional</sup> <a name="IdInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.idInput"></a>

```csharp
public string IdInput { get; }
```

- *Type:* string

---

##### `NameInput`<sup>Optional</sup> <a name="NameInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.nameInput"></a>

```csharp
public string NameInput { get; }
```

- *Type:* string

---

##### `TypeInput`<sup>Optional</sup> <a name="TypeInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.typeInput"></a>

```csharp
public string TypeInput { get; }
```

- *Type:* string

---

##### `Id`<sup>Required</sup> <a name="Id" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.id"></a>

```csharp
public string Id { get; }
```

- *Type:* string

---

##### `Name`<sup>Required</sup> <a name="Name" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.name"></a>

```csharp
public string Name { get; }
```

- *Type:* string

---

##### `Type`<sup>Required</sup> <a name="Type" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.type"></a>

```csharp
public string Type { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.internalValue"></a>

```csharp
public object InternalValue { get; }
```

- *Type:* object

---


### TeamRoutingRuleTimeRestrictionList <a name="TeamRoutingRuleTimeRestrictionList" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new TeamRoutingRuleTimeRestrictionList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>HashiCorp.Cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.Initializer.parameter.terraformResource"></a>

- *Type:* HashiCorp.Cdktf.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

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

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.resolve.parameter._context"></a>

- *Type:* HashiCorp.Cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.get"></a>

```csharp
private TeamRoutingRuleTimeRestrictionOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.property.internalValue">InternalValue</a></code> | <code>object</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.property.internalValue"></a>

```csharp
public object InternalValue { get; }
```

- *Type:* object

---


### TeamRoutingRuleTimeRestrictionOutputReference <a name="TeamRoutingRuleTimeRestrictionOutputReference" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new TeamRoutingRuleTimeRestrictionOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>HashiCorp.Cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* HashiCorp.Cdktf.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

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

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.resolve.parameter._context"></a>

- *Type:* HashiCorp.Cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `PutRestriction` <a name="PutRestriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.putRestriction"></a>

```csharp
private void PutRestriction(object Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.putRestriction.parameter.value"></a>

- *Type:* object

---

##### `PutRestrictions` <a name="PutRestrictions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.putRestrictions"></a>

```csharp
private void PutRestrictions(object Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.putRestrictions.parameter.value"></a>

- *Type:* object

---

##### `ResetRestriction` <a name="ResetRestriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.resetRestriction"></a>

```csharp
private void ResetRestriction()
```

##### `ResetRestrictions` <a name="ResetRestrictions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.resetRestrictions"></a>

```csharp
private void ResetRestrictions()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restriction">Restriction</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList">TeamRoutingRuleTimeRestrictionRestrictionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restrictions">Restrictions</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList">TeamRoutingRuleTimeRestrictionRestrictionsList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restrictionInput">RestrictionInput</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restrictionsInput">RestrictionsInput</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.typeInput">TypeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.type">Type</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.internalValue">InternalValue</a></code> | <code>object</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `Restriction`<sup>Required</sup> <a name="Restriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restriction"></a>

```csharp
public TeamRoutingRuleTimeRestrictionRestrictionList Restriction { get; }
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList">TeamRoutingRuleTimeRestrictionRestrictionList</a>

---

##### `Restrictions`<sup>Required</sup> <a name="Restrictions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restrictions"></a>

```csharp
public TeamRoutingRuleTimeRestrictionRestrictionsList Restrictions { get; }
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList">TeamRoutingRuleTimeRestrictionRestrictionsList</a>

---

##### `RestrictionInput`<sup>Optional</sup> <a name="RestrictionInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restrictionInput"></a>

```csharp
public object RestrictionInput { get; }
```

- *Type:* object

---

##### `RestrictionsInput`<sup>Optional</sup> <a name="RestrictionsInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restrictionsInput"></a>

```csharp
public object RestrictionsInput { get; }
```

- *Type:* object

---

##### `TypeInput`<sup>Optional</sup> <a name="TypeInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.typeInput"></a>

```csharp
public string TypeInput { get; }
```

- *Type:* string

---

##### `Type`<sup>Required</sup> <a name="Type" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.type"></a>

```csharp
public string Type { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.internalValue"></a>

```csharp
public object InternalValue { get; }
```

- *Type:* object

---


### TeamRoutingRuleTimeRestrictionRestrictionList <a name="TeamRoutingRuleTimeRestrictionRestrictionList" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new TeamRoutingRuleTimeRestrictionRestrictionList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>HashiCorp.Cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.Initializer.parameter.terraformResource"></a>

- *Type:* HashiCorp.Cdktf.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

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

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.resolve.parameter._context"></a>

- *Type:* HashiCorp.Cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.get"></a>

```csharp
private TeamRoutingRuleTimeRestrictionRestrictionOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.property.internalValue">InternalValue</a></code> | <code>object</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.property.internalValue"></a>

```csharp
public object InternalValue { get; }
```

- *Type:* object

---


### TeamRoutingRuleTimeRestrictionRestrictionOutputReference <a name="TeamRoutingRuleTimeRestrictionRestrictionOutputReference" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new TeamRoutingRuleTimeRestrictionRestrictionOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>HashiCorp.Cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* HashiCorp.Cdktf.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

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

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.resolve.parameter._context"></a>

- *Type:* HashiCorp.Cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endHourInput">EndHourInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endMinInput">EndMinInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startHourInput">StartHourInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startMinInput">StartMinInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endHour">EndHour</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endMin">EndMin</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startHour">StartHour</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startMin">StartMin</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.internalValue">InternalValue</a></code> | <code>object</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `EndHourInput`<sup>Optional</sup> <a name="EndHourInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endHourInput"></a>

```csharp
public double EndHourInput { get; }
```

- *Type:* double

---

##### `EndMinInput`<sup>Optional</sup> <a name="EndMinInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endMinInput"></a>

```csharp
public double EndMinInput { get; }
```

- *Type:* double

---

##### `StartHourInput`<sup>Optional</sup> <a name="StartHourInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startHourInput"></a>

```csharp
public double StartHourInput { get; }
```

- *Type:* double

---

##### `StartMinInput`<sup>Optional</sup> <a name="StartMinInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startMinInput"></a>

```csharp
public double StartMinInput { get; }
```

- *Type:* double

---

##### `EndHour`<sup>Required</sup> <a name="EndHour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endHour"></a>

```csharp
public double EndHour { get; }
```

- *Type:* double

---

##### `EndMin`<sup>Required</sup> <a name="EndMin" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endMin"></a>

```csharp
public double EndMin { get; }
```

- *Type:* double

---

##### `StartHour`<sup>Required</sup> <a name="StartHour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startHour"></a>

```csharp
public double StartHour { get; }
```

- *Type:* double

---

##### `StartMin`<sup>Required</sup> <a name="StartMin" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startMin"></a>

```csharp
public double StartMin { get; }
```

- *Type:* double

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.internalValue"></a>

```csharp
public object InternalValue { get; }
```

- *Type:* object

---


### TeamRoutingRuleTimeRestrictionRestrictionsList <a name="TeamRoutingRuleTimeRestrictionRestrictionsList" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new TeamRoutingRuleTimeRestrictionRestrictionsList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>HashiCorp.Cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.Initializer.parameter.terraformResource"></a>

- *Type:* HashiCorp.Cdktf.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

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

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.resolve.parameter._context"></a>

- *Type:* HashiCorp.Cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.get"></a>

```csharp
private TeamRoutingRuleTimeRestrictionRestrictionsOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.property.internalValue">InternalValue</a></code> | <code>object</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.property.internalValue"></a>

```csharp
public object InternalValue { get; }
```

- *Type:* object

---


### TeamRoutingRuleTimeRestrictionRestrictionsOutputReference <a name="TeamRoutingRuleTimeRestrictionRestrictionsOutputReference" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new TeamRoutingRuleTimeRestrictionRestrictionsOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>HashiCorp.Cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* HashiCorp.Cdktf.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

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

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.resolve.parameter._context"></a>

- *Type:* HashiCorp.Cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endDayInput">EndDayInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endHourInput">EndHourInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endMinInput">EndMinInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startDayInput">StartDayInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startHourInput">StartHourInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startMinInput">StartMinInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endDay">EndDay</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endHour">EndHour</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endMin">EndMin</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startDay">StartDay</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startHour">StartHour</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startMin">StartMin</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.internalValue">InternalValue</a></code> | <code>object</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `EndDayInput`<sup>Optional</sup> <a name="EndDayInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endDayInput"></a>

```csharp
public string EndDayInput { get; }
```

- *Type:* string

---

##### `EndHourInput`<sup>Optional</sup> <a name="EndHourInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endHourInput"></a>

```csharp
public double EndHourInput { get; }
```

- *Type:* double

---

##### `EndMinInput`<sup>Optional</sup> <a name="EndMinInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endMinInput"></a>

```csharp
public double EndMinInput { get; }
```

- *Type:* double

---

##### `StartDayInput`<sup>Optional</sup> <a name="StartDayInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startDayInput"></a>

```csharp
public string StartDayInput { get; }
```

- *Type:* string

---

##### `StartHourInput`<sup>Optional</sup> <a name="StartHourInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startHourInput"></a>

```csharp
public double StartHourInput { get; }
```

- *Type:* double

---

##### `StartMinInput`<sup>Optional</sup> <a name="StartMinInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startMinInput"></a>

```csharp
public double StartMinInput { get; }
```

- *Type:* double

---

##### `EndDay`<sup>Required</sup> <a name="EndDay" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endDay"></a>

```csharp
public string EndDay { get; }
```

- *Type:* string

---

##### `EndHour`<sup>Required</sup> <a name="EndHour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endHour"></a>

```csharp
public double EndHour { get; }
```

- *Type:* double

---

##### `EndMin`<sup>Required</sup> <a name="EndMin" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endMin"></a>

```csharp
public double EndMin { get; }
```

- *Type:* double

---

##### `StartDay`<sup>Required</sup> <a name="StartDay" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startDay"></a>

```csharp
public string StartDay { get; }
```

- *Type:* string

---

##### `StartHour`<sup>Required</sup> <a name="StartHour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startHour"></a>

```csharp
public double StartHour { get; }
```

- *Type:* double

---

##### `StartMin`<sup>Required</sup> <a name="StartMin" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startMin"></a>

```csharp
public double StartMin { get; }
```

- *Type:* double

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.internalValue"></a>

```csharp
public object InternalValue { get; }
```

- *Type:* object

---



