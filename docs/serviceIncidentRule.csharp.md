# `opsgenie_service_incident_rule`

Refer to the Terraform Registory for docs: [`opsgenie_service_incident_rule`](https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule).

# `serviceIncidentRule` Submodule <a name="`serviceIncidentRule` Submodule" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### ServiceIncidentRule <a name="ServiceIncidentRule" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule"></a>

Represents a {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule opsgenie_service_incident_rule}.

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new ServiceIncidentRule(Construct Scope, string Id, ServiceIncidentRuleConfig Config);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.scope">Scope</a></code> | <code>Constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.id">Id</a></code> | <code>string</code> | The scoped construct ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.config">Config</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig">ServiceIncidentRuleConfig</a></code> | *No description.* |

---

##### `Scope`<sup>Required</sup> <a name="Scope" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.scope"></a>

- *Type:* Constructs.Construct

The scope in which to define this construct.

---

##### `Id`<sup>Required</sup> <a name="Id" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.id"></a>

- *Type:* string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `Config`<sup>Required</sup> <a name="Config" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.config"></a>

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

```csharp
private string ToString()
```

Returns a string representation of this construct.

##### `AddOverride` <a name="AddOverride" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.addOverride"></a>

```csharp
private void AddOverride(string Path, object Value)
```

###### `Path`<sup>Required</sup> <a name="Path" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.addOverride.parameter.path"></a>

- *Type:* string

---

###### `Value`<sup>Required</sup> <a name="Value" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.addOverride.parameter.value"></a>

- *Type:* object

---

##### `OverrideLogicalId` <a name="OverrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.overrideLogicalId"></a>

```csharp
private void OverrideLogicalId(string NewLogicalId)
```

Overrides the auto-generated logical ID with a specific ID.

###### `NewLogicalId`<sup>Required</sup> <a name="NewLogicalId" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* string

The new logical ID to use for this stack element.

---

##### `ResetOverrideLogicalId` <a name="ResetOverrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.resetOverrideLogicalId"></a>

```csharp
private void ResetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `ToMetadata` <a name="ToMetadata" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.toMetadata"></a>

```csharp
private object ToMetadata()
```

##### `ToTerraform` <a name="ToTerraform" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.toTerraform"></a>

```csharp
private object ToTerraform()
```

Adds this resource to the terraform JSON output.

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `PutIncidentRule` <a name="PutIncidentRule" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.putIncidentRule"></a>

```csharp
private void PutIncidentRule(object Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.putIncidentRule.parameter.value"></a>

- *Type:* object

---

##### `ResetId` <a name="ResetId" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.resetId"></a>

```csharp
private void ResetId()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isConstruct">IsConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isTerraformElement">IsTerraformElement</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isTerraformResource">IsTerraformResource</a></code> | *No description.* |

---

##### `IsConstruct` <a name="IsConstruct" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isConstruct"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

ServiceIncidentRule.IsConstruct(object X);
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

###### `X`<sup>Required</sup> <a name="X" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isConstruct.parameter.x"></a>

- *Type:* object

Any object.

---

##### `IsTerraformElement` <a name="IsTerraformElement" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isTerraformElement"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

ServiceIncidentRule.IsTerraformElement(object X);
```

###### `X`<sup>Required</sup> <a name="X" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isTerraformElement.parameter.x"></a>

- *Type:* object

---

##### `IsTerraformResource` <a name="IsTerraformResource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isTerraformResource"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

ServiceIncidentRule.IsTerraformResource(object X);
```

###### `X`<sup>Required</sup> <a name="X" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isTerraformResource.parameter.x"></a>

- *Type:* object

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.node">Node</a></code> | <code>Constructs.Node</code> | The tree node. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.cdktfStack">CdktfStack</a></code> | <code>HashiCorp.Cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.friendlyUniqueId">FriendlyUniqueId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.terraformMetaArguments">TerraformMetaArguments</a></code> | <code>System.Collections.Generic.IDictionary<string, object></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.terraformResourceType">TerraformResourceType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.terraformGeneratorMetadata">TerraformGeneratorMetadata</a></code> | <code>HashiCorp.Cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.connection">Connection</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.count">Count</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.dependsOn">DependsOn</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.forEach">ForEach</a></code> | <code>HashiCorp.Cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.lifecycle">Lifecycle</a></code> | <code>HashiCorp.Cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.provider">Provider</a></code> | <code>HashiCorp.Cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.provisioners">Provisioners</a></code> | <code>object[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.incidentRule">IncidentRule</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList">ServiceIncidentRuleIncidentRuleList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.idInput">IdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.incidentRuleInput">IncidentRuleInput</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.serviceIdInput">ServiceIdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.id">Id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.serviceId">ServiceId</a></code> | <code>string</code> | *No description.* |

---

##### `Node`<sup>Required</sup> <a name="Node" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.node"></a>

```csharp
public Node Node { get; }
```

- *Type:* Constructs.Node

The tree node.

---

##### `CdktfStack`<sup>Required</sup> <a name="CdktfStack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.cdktfStack"></a>

```csharp
public TerraformStack CdktfStack { get; }
```

- *Type:* HashiCorp.Cdktf.TerraformStack

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `FriendlyUniqueId`<sup>Required</sup> <a name="FriendlyUniqueId" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.friendlyUniqueId"></a>

```csharp
public string FriendlyUniqueId { get; }
```

- *Type:* string

---

##### `TerraformMetaArguments`<sup>Required</sup> <a name="TerraformMetaArguments" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.terraformMetaArguments"></a>

```csharp
public System.Collections.Generic.IDictionary<string, object> TerraformMetaArguments { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, object>

---

##### `TerraformResourceType`<sup>Required</sup> <a name="TerraformResourceType" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.terraformResourceType"></a>

```csharp
public string TerraformResourceType { get; }
```

- *Type:* string

---

##### `TerraformGeneratorMetadata`<sup>Optional</sup> <a name="TerraformGeneratorMetadata" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.terraformGeneratorMetadata"></a>

```csharp
public TerraformProviderGeneratorMetadata TerraformGeneratorMetadata { get; }
```

- *Type:* HashiCorp.Cdktf.TerraformProviderGeneratorMetadata

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.connection"></a>

```csharp
public object Connection { get; }
```

- *Type:* object

---

##### `Count`<sup>Optional</sup> <a name="Count" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.count"></a>

```csharp
public object Count { get; }
```

- *Type:* object

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.dependsOn"></a>

```csharp
public string[] DependsOn { get; }
```

- *Type:* string[]

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.forEach"></a>

```csharp
public ITerraformIterator ForEach { get; }
```

- *Type:* HashiCorp.Cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.lifecycle"></a>

```csharp
public TerraformResourceLifecycle Lifecycle { get; }
```

- *Type:* HashiCorp.Cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.provider"></a>

```csharp
public TerraformProvider Provider { get; }
```

- *Type:* HashiCorp.Cdktf.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.provisioners"></a>

```csharp
public object[] Provisioners { get; }
```

- *Type:* object[]

---

##### `IncidentRule`<sup>Required</sup> <a name="IncidentRule" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.incidentRule"></a>

```csharp
public ServiceIncidentRuleIncidentRuleList IncidentRule { get; }
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList">ServiceIncidentRuleIncidentRuleList</a>

---

##### `IdInput`<sup>Optional</sup> <a name="IdInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.idInput"></a>

```csharp
public string IdInput { get; }
```

- *Type:* string

---

##### `IncidentRuleInput`<sup>Optional</sup> <a name="IncidentRuleInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.incidentRuleInput"></a>

```csharp
public object IncidentRuleInput { get; }
```

- *Type:* object

---

##### `ServiceIdInput`<sup>Optional</sup> <a name="ServiceIdInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.serviceIdInput"></a>

```csharp
public string ServiceIdInput { get; }
```

- *Type:* string

---

##### `Id`<sup>Required</sup> <a name="Id" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.id"></a>

```csharp
public string Id { get; }
```

- *Type:* string

---

##### `ServiceId`<sup>Required</sup> <a name="ServiceId" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.serviceId"></a>

```csharp
public string ServiceId { get; }
```

- *Type:* string

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.tfResourceType">TfResourceType</a></code> | <code>string</code> | *No description.* |

---

##### `TfResourceType`<sup>Required</sup> <a name="TfResourceType" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.tfResourceType"></a>

```csharp
public string TfResourceType { get; }
```

- *Type:* string

---

## Structs <a name="Structs" id="Structs"></a>

### ServiceIncidentRuleConfig <a name="ServiceIncidentRuleConfig" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new ServiceIncidentRuleConfig {
    object Connection = null,
    object Count = null,
    ITerraformDependable[] DependsOn = null,
    ITerraformIterator ForEach = null,
    TerraformResourceLifecycle Lifecycle = null,
    TerraformProvider Provider = null,
    object[] Provisioners = null,
    object IncidentRule,
    string ServiceId,
    string Id = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.connection">Connection</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.count">Count</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.dependsOn">DependsOn</a></code> | <code>HashiCorp.Cdktf.ITerraformDependable[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.forEach">ForEach</a></code> | <code>HashiCorp.Cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.lifecycle">Lifecycle</a></code> | <code>HashiCorp.Cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.provider">Provider</a></code> | <code>HashiCorp.Cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.provisioners">Provisioners</a></code> | <code>object[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.incidentRule">IncidentRule</a></code> | <code>object</code> | incident_rule block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.serviceId">ServiceId</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#service_id ServiceIncidentRule#service_id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.id">Id</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#id ServiceIncidentRule#id}. |

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.connection"></a>

```csharp
public object Connection { get; set; }
```

- *Type:* object

---

##### `Count`<sup>Optional</sup> <a name="Count" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.count"></a>

```csharp
public object Count { get; set; }
```

- *Type:* object

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.dependsOn"></a>

```csharp
public ITerraformDependable[] DependsOn { get; set; }
```

- *Type:* HashiCorp.Cdktf.ITerraformDependable[]

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.forEach"></a>

```csharp
public ITerraformIterator ForEach { get; set; }
```

- *Type:* HashiCorp.Cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.lifecycle"></a>

```csharp
public TerraformResourceLifecycle Lifecycle { get; set; }
```

- *Type:* HashiCorp.Cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.provider"></a>

```csharp
public TerraformProvider Provider { get; set; }
```

- *Type:* HashiCorp.Cdktf.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.provisioners"></a>

```csharp
public object[] Provisioners { get; set; }
```

- *Type:* object[]

---

##### `IncidentRule`<sup>Required</sup> <a name="IncidentRule" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.incidentRule"></a>

```csharp
public object IncidentRule { get; set; }
```

- *Type:* object

incident_rule block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#incident_rule ServiceIncidentRule#incident_rule}

---

##### `ServiceId`<sup>Required</sup> <a name="ServiceId" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.serviceId"></a>

```csharp
public string ServiceId { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#service_id ServiceIncidentRule#service_id}.

---

##### `Id`<sup>Optional</sup> <a name="Id" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.id"></a>

```csharp
public string Id { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#id ServiceIncidentRule#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

### ServiceIncidentRuleIncidentRule <a name="ServiceIncidentRuleIncidentRule" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new ServiceIncidentRuleIncidentRule {
    object IncidentProperties,
    string ConditionMatchType = null,
    object Conditions = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule.property.incidentProperties">IncidentProperties</a></code> | <code>object</code> | incident_properties block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule.property.conditionMatchType">ConditionMatchType</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#condition_match_type ServiceIncidentRule#condition_match_type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule.property.conditions">Conditions</a></code> | <code>object</code> | conditions block. |

---

##### `IncidentProperties`<sup>Required</sup> <a name="IncidentProperties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule.property.incidentProperties"></a>

```csharp
public object IncidentProperties { get; set; }
```

- *Type:* object

incident_properties block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#incident_properties ServiceIncidentRule#incident_properties}

---

##### `ConditionMatchType`<sup>Optional</sup> <a name="ConditionMatchType" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule.property.conditionMatchType"></a>

```csharp
public string ConditionMatchType { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#condition_match_type ServiceIncidentRule#condition_match_type}.

---

##### `Conditions`<sup>Optional</sup> <a name="Conditions" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule.property.conditions"></a>

```csharp
public object Conditions { get; set; }
```

- *Type:* object

conditions block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#conditions ServiceIncidentRule#conditions}

---

### ServiceIncidentRuleIncidentRuleConditions <a name="ServiceIncidentRuleIncidentRuleConditions" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new ServiceIncidentRuleIncidentRuleConditions {
    string Field,
    string Operation,
    string ExpectedValue = null,
    string Key = null,
    object Not = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.field">Field</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#field ServiceIncidentRule#field}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.operation">Operation</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#operation ServiceIncidentRule#operation}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.expectedValue">ExpectedValue</a></code> | <code>string</code> | User defined value that will be compared with alert field according to the operation. Default value is empty string. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.key">Key</a></code> | <code>string</code> | If 'field' is set as 'extra-properties', key could be used for key-value pair. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.not">Not</a></code> | <code>object</code> | Indicates behaviour of the given operation. Default value is false. |

---

##### `Field`<sup>Required</sup> <a name="Field" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.field"></a>

```csharp
public string Field { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#field ServiceIncidentRule#field}.

---

##### `Operation`<sup>Required</sup> <a name="Operation" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.operation"></a>

```csharp
public string Operation { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#operation ServiceIncidentRule#operation}.

---

##### `ExpectedValue`<sup>Optional</sup> <a name="ExpectedValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.expectedValue"></a>

```csharp
public string ExpectedValue { get; set; }
```

- *Type:* string

User defined value that will be compared with alert field according to the operation. Default value is empty string.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#expected_value ServiceIncidentRule#expected_value}

---

##### `Key`<sup>Optional</sup> <a name="Key" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.key"></a>

```csharp
public string Key { get; set; }
```

- *Type:* string

If 'field' is set as 'extra-properties', key could be used for key-value pair.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#key ServiceIncidentRule#key}

---

##### `Not`<sup>Optional</sup> <a name="Not" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.not"></a>

```csharp
public object Not { get; set; }
```

- *Type:* object

Indicates behaviour of the given operation. Default value is false.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#not ServiceIncidentRule#not}

---

### ServiceIncidentRuleIncidentRuleIncidentProperties <a name="ServiceIncidentRuleIncidentRuleIncidentProperties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new ServiceIncidentRuleIncidentRuleIncidentProperties {
    string Message,
    string Priority,
    object StakeholderProperties,
    string Description = null,
    System.Collections.Generic.IDictionary<string, string> Details = null,
    string[] Tags = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.message">Message</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#message ServiceIncidentRule#message}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.priority">Priority</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#priority ServiceIncidentRule#priority}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.stakeholderProperties">StakeholderProperties</a></code> | <code>object</code> | stakeholder_properties block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.description">Description</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#description ServiceIncidentRule#description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.details">Details</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#details ServiceIncidentRule#details}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.tags">Tags</a></code> | <code>string[]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#tags ServiceIncidentRule#tags}. |

---

##### `Message`<sup>Required</sup> <a name="Message" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.message"></a>

```csharp
public string Message { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#message ServiceIncidentRule#message}.

---

##### `Priority`<sup>Required</sup> <a name="Priority" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.priority"></a>

```csharp
public string Priority { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#priority ServiceIncidentRule#priority}.

---

##### `StakeholderProperties`<sup>Required</sup> <a name="StakeholderProperties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.stakeholderProperties"></a>

```csharp
public object StakeholderProperties { get; set; }
```

- *Type:* object

stakeholder_properties block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#stakeholder_properties ServiceIncidentRule#stakeholder_properties}

---

##### `Description`<sup>Optional</sup> <a name="Description" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.description"></a>

```csharp
public string Description { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#description ServiceIncidentRule#description}.

---

##### `Details`<sup>Optional</sup> <a name="Details" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.details"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> Details { get; set; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#details ServiceIncidentRule#details}.

---

##### `Tags`<sup>Optional</sup> <a name="Tags" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.tags"></a>

```csharp
public string[] Tags { get; set; }
```

- *Type:* string[]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#tags ServiceIncidentRule#tags}.

---

### ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties <a name="ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties {
    string Message,
    string Description = null,
    object Enable = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties.property.message">Message</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#message ServiceIncidentRule#message}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties.property.description">Description</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#description ServiceIncidentRule#description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties.property.enable">Enable</a></code> | <code>object</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#enable ServiceIncidentRule#enable}. |

---

##### `Message`<sup>Required</sup> <a name="Message" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties.property.message"></a>

```csharp
public string Message { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#message ServiceIncidentRule#message}.

---

##### `Description`<sup>Optional</sup> <a name="Description" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties.property.description"></a>

```csharp
public string Description { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#description ServiceIncidentRule#description}.

---

##### `Enable`<sup>Optional</sup> <a name="Enable" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties.property.enable"></a>

```csharp
public object Enable { get; set; }
```

- *Type:* object

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#enable ServiceIncidentRule#enable}.

---

## Classes <a name="Classes" id="Classes"></a>

### ServiceIncidentRuleIncidentRuleConditionsList <a name="ServiceIncidentRuleIncidentRuleConditionsList" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new ServiceIncidentRuleIncidentRuleConditionsList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>HashiCorp.Cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.Initializer.parameter.terraformResource"></a>

- *Type:* HashiCorp.Cdktf.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

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

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.resolve.parameter._context"></a>

- *Type:* HashiCorp.Cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.get"></a>

```csharp
private ServiceIncidentRuleIncidentRuleConditionsOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.property.internalValue">InternalValue</a></code> | <code>object</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.property.internalValue"></a>

```csharp
public object InternalValue { get; }
```

- *Type:* object

---


### ServiceIncidentRuleIncidentRuleConditionsOutputReference <a name="ServiceIncidentRuleIncidentRuleConditionsOutputReference" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new ServiceIncidentRuleIncidentRuleConditionsOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>HashiCorp.Cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* HashiCorp.Cdktf.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

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

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.resolve.parameter._context"></a>

- *Type:* HashiCorp.Cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetExpectedValue` <a name="ResetExpectedValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.resetExpectedValue"></a>

```csharp
private void ResetExpectedValue()
```

##### `ResetKey` <a name="ResetKey" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.resetKey"></a>

```csharp
private void ResetKey()
```

##### `ResetNot` <a name="ResetNot" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.resetNot"></a>

```csharp
private void ResetNot()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.expectedValueInput">ExpectedValueInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.fieldInput">FieldInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.keyInput">KeyInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.notInput">NotInput</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.operationInput">OperationInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.expectedValue">ExpectedValue</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.field">Field</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.key">Key</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.not">Not</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.operation">Operation</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.internalValue">InternalValue</a></code> | <code>object</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `ExpectedValueInput`<sup>Optional</sup> <a name="ExpectedValueInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.expectedValueInput"></a>

```csharp
public string ExpectedValueInput { get; }
```

- *Type:* string

---

##### `FieldInput`<sup>Optional</sup> <a name="FieldInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.fieldInput"></a>

```csharp
public string FieldInput { get; }
```

- *Type:* string

---

##### `KeyInput`<sup>Optional</sup> <a name="KeyInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.keyInput"></a>

```csharp
public string KeyInput { get; }
```

- *Type:* string

---

##### `NotInput`<sup>Optional</sup> <a name="NotInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.notInput"></a>

```csharp
public object NotInput { get; }
```

- *Type:* object

---

##### `OperationInput`<sup>Optional</sup> <a name="OperationInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.operationInput"></a>

```csharp
public string OperationInput { get; }
```

- *Type:* string

---

##### `ExpectedValue`<sup>Required</sup> <a name="ExpectedValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.expectedValue"></a>

```csharp
public string ExpectedValue { get; }
```

- *Type:* string

---

##### `Field`<sup>Required</sup> <a name="Field" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.field"></a>

```csharp
public string Field { get; }
```

- *Type:* string

---

##### `Key`<sup>Required</sup> <a name="Key" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.key"></a>

```csharp
public string Key { get; }
```

- *Type:* string

---

##### `Not`<sup>Required</sup> <a name="Not" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.not"></a>

```csharp
public object Not { get; }
```

- *Type:* object

---

##### `Operation`<sup>Required</sup> <a name="Operation" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.operation"></a>

```csharp
public string Operation { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.internalValue"></a>

```csharp
public object InternalValue { get; }
```

- *Type:* object

---


### ServiceIncidentRuleIncidentRuleIncidentPropertiesList <a name="ServiceIncidentRuleIncidentRuleIncidentPropertiesList" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new ServiceIncidentRuleIncidentRuleIncidentPropertiesList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>HashiCorp.Cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.Initializer.parameter.terraformResource"></a>

- *Type:* HashiCorp.Cdktf.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

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

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.resolve.parameter._context"></a>

- *Type:* HashiCorp.Cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.get"></a>

```csharp
private ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.property.internalValue">InternalValue</a></code> | <code>object</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.property.internalValue"></a>

```csharp
public object InternalValue { get; }
```

- *Type:* object

---


### ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference <a name="ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>HashiCorp.Cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* HashiCorp.Cdktf.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

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

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.resolve.parameter._context"></a>

- *Type:* HashiCorp.Cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `PutStakeholderProperties` <a name="PutStakeholderProperties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.putStakeholderProperties"></a>

```csharp
private void PutStakeholderProperties(object Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.putStakeholderProperties.parameter.value"></a>

- *Type:* object

---

##### `ResetDescription` <a name="ResetDescription" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.resetDescription"></a>

```csharp
private void ResetDescription()
```

##### `ResetDetails` <a name="ResetDetails" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.resetDetails"></a>

```csharp
private void ResetDetails()
```

##### `ResetTags` <a name="ResetTags" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.resetTags"></a>

```csharp
private void ResetTags()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.stakeholderProperties">StakeholderProperties</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList">ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.descriptionInput">DescriptionInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.detailsInput">DetailsInput</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.messageInput">MessageInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.priorityInput">PriorityInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.stakeholderPropertiesInput">StakeholderPropertiesInput</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.tagsInput">TagsInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.description">Description</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.details">Details</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.message">Message</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.priority">Priority</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.tags">Tags</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.internalValue">InternalValue</a></code> | <code>object</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `StakeholderProperties`<sup>Required</sup> <a name="StakeholderProperties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.stakeholderProperties"></a>

```csharp
public ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList StakeholderProperties { get; }
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList">ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList</a>

---

##### `DescriptionInput`<sup>Optional</sup> <a name="DescriptionInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.descriptionInput"></a>

```csharp
public string DescriptionInput { get; }
```

- *Type:* string

---

##### `DetailsInput`<sup>Optional</sup> <a name="DetailsInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.detailsInput"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> DetailsInput { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

---

##### `MessageInput`<sup>Optional</sup> <a name="MessageInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.messageInput"></a>

```csharp
public string MessageInput { get; }
```

- *Type:* string

---

##### `PriorityInput`<sup>Optional</sup> <a name="PriorityInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.priorityInput"></a>

```csharp
public string PriorityInput { get; }
```

- *Type:* string

---

##### `StakeholderPropertiesInput`<sup>Optional</sup> <a name="StakeholderPropertiesInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.stakeholderPropertiesInput"></a>

```csharp
public object StakeholderPropertiesInput { get; }
```

- *Type:* object

---

##### `TagsInput`<sup>Optional</sup> <a name="TagsInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.tagsInput"></a>

```csharp
public string[] TagsInput { get; }
```

- *Type:* string[]

---

##### `Description`<sup>Required</sup> <a name="Description" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.description"></a>

```csharp
public string Description { get; }
```

- *Type:* string

---

##### `Details`<sup>Required</sup> <a name="Details" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.details"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> Details { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

---

##### `Message`<sup>Required</sup> <a name="Message" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.message"></a>

```csharp
public string Message { get; }
```

- *Type:* string

---

##### `Priority`<sup>Required</sup> <a name="Priority" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.priority"></a>

```csharp
public string Priority { get; }
```

- *Type:* string

---

##### `Tags`<sup>Required</sup> <a name="Tags" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.tags"></a>

```csharp
public string[] Tags { get; }
```

- *Type:* string[]

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.internalValue"></a>

```csharp
public object InternalValue { get; }
```

- *Type:* object

---


### ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList <a name="ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>HashiCorp.Cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.Initializer.parameter.terraformResource"></a>

- *Type:* HashiCorp.Cdktf.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

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

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.resolve.parameter._context"></a>

- *Type:* HashiCorp.Cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.get"></a>

```csharp
private ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.property.internalValue">InternalValue</a></code> | <code>object</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.property.internalValue"></a>

```csharp
public object InternalValue { get; }
```

- *Type:* object

---


### ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference <a name="ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>HashiCorp.Cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* HashiCorp.Cdktf.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

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

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.resolve.parameter._context"></a>

- *Type:* HashiCorp.Cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetDescription` <a name="ResetDescription" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.resetDescription"></a>

```csharp
private void ResetDescription()
```

##### `ResetEnable` <a name="ResetEnable" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.resetEnable"></a>

```csharp
private void ResetEnable()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.descriptionInput">DescriptionInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.enableInput">EnableInput</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.messageInput">MessageInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.description">Description</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.enable">Enable</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.message">Message</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.internalValue">InternalValue</a></code> | <code>object</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `DescriptionInput`<sup>Optional</sup> <a name="DescriptionInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.descriptionInput"></a>

```csharp
public string DescriptionInput { get; }
```

- *Type:* string

---

##### `EnableInput`<sup>Optional</sup> <a name="EnableInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.enableInput"></a>

```csharp
public object EnableInput { get; }
```

- *Type:* object

---

##### `MessageInput`<sup>Optional</sup> <a name="MessageInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.messageInput"></a>

```csharp
public string MessageInput { get; }
```

- *Type:* string

---

##### `Description`<sup>Required</sup> <a name="Description" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.description"></a>

```csharp
public string Description { get; }
```

- *Type:* string

---

##### `Enable`<sup>Required</sup> <a name="Enable" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.enable"></a>

```csharp
public object Enable { get; }
```

- *Type:* object

---

##### `Message`<sup>Required</sup> <a name="Message" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.message"></a>

```csharp
public string Message { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.internalValue"></a>

```csharp
public object InternalValue { get; }
```

- *Type:* object

---


### ServiceIncidentRuleIncidentRuleList <a name="ServiceIncidentRuleIncidentRuleList" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new ServiceIncidentRuleIncidentRuleList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>HashiCorp.Cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.Initializer.parameter.terraformResource"></a>

- *Type:* HashiCorp.Cdktf.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

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

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.resolve.parameter._context"></a>

- *Type:* HashiCorp.Cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.get"></a>

```csharp
private ServiceIncidentRuleIncidentRuleOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.property.internalValue">InternalValue</a></code> | <code>object</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.property.internalValue"></a>

```csharp
public object InternalValue { get; }
```

- *Type:* object

---


### ServiceIncidentRuleIncidentRuleOutputReference <a name="ServiceIncidentRuleIncidentRuleOutputReference" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new ServiceIncidentRuleIncidentRuleOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>HashiCorp.Cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* HashiCorp.Cdktf.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

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

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.resolve.parameter._context"></a>

- *Type:* HashiCorp.Cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `PutConditions` <a name="PutConditions" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.putConditions"></a>

```csharp
private void PutConditions(object Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.putConditions.parameter.value"></a>

- *Type:* object

---

##### `PutIncidentProperties` <a name="PutIncidentProperties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.putIncidentProperties"></a>

```csharp
private void PutIncidentProperties(object Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.putIncidentProperties.parameter.value"></a>

- *Type:* object

---

##### `ResetConditionMatchType` <a name="ResetConditionMatchType" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.resetConditionMatchType"></a>

```csharp
private void ResetConditionMatchType()
```

##### `ResetConditions` <a name="ResetConditions" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.resetConditions"></a>

```csharp
private void ResetConditions()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditions">Conditions</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList">ServiceIncidentRuleIncidentRuleConditionsList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.incidentProperties">IncidentProperties</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList">ServiceIncidentRuleIncidentRuleIncidentPropertiesList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditionMatchTypeInput">ConditionMatchTypeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditionsInput">ConditionsInput</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.incidentPropertiesInput">IncidentPropertiesInput</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditionMatchType">ConditionMatchType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.internalValue">InternalValue</a></code> | <code>object</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `Conditions`<sup>Required</sup> <a name="Conditions" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditions"></a>

```csharp
public ServiceIncidentRuleIncidentRuleConditionsList Conditions { get; }
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList">ServiceIncidentRuleIncidentRuleConditionsList</a>

---

##### `IncidentProperties`<sup>Required</sup> <a name="IncidentProperties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.incidentProperties"></a>

```csharp
public ServiceIncidentRuleIncidentRuleIncidentPropertiesList IncidentProperties { get; }
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList">ServiceIncidentRuleIncidentRuleIncidentPropertiesList</a>

---

##### `ConditionMatchTypeInput`<sup>Optional</sup> <a name="ConditionMatchTypeInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditionMatchTypeInput"></a>

```csharp
public string ConditionMatchTypeInput { get; }
```

- *Type:* string

---

##### `ConditionsInput`<sup>Optional</sup> <a name="ConditionsInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditionsInput"></a>

```csharp
public object ConditionsInput { get; }
```

- *Type:* object

---

##### `IncidentPropertiesInput`<sup>Optional</sup> <a name="IncidentPropertiesInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.incidentPropertiesInput"></a>

```csharp
public object IncidentPropertiesInput { get; }
```

- *Type:* object

---

##### `ConditionMatchType`<sup>Required</sup> <a name="ConditionMatchType" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditionMatchType"></a>

```csharp
public string ConditionMatchType { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.internalValue"></a>

```csharp
public object InternalValue { get; }
```

- *Type:* object

---



