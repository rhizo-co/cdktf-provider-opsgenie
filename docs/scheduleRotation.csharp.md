# `opsgenie_schedule_rotation`

Refer to the Terraform Registory for docs: [`opsgenie_schedule_rotation`](https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation).

# `scheduleRotation` Submodule <a name="`scheduleRotation` Submodule" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### ScheduleRotation <a name="ScheduleRotation" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation"></a>

Represents a {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation opsgenie_schedule_rotation}.

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new ScheduleRotation(Construct Scope, string Id, ScheduleRotationConfig Config);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.scope">Scope</a></code> | <code>Constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.id">Id</a></code> | <code>string</code> | The scoped construct ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.config">Config</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig">ScheduleRotationConfig</a></code> | *No description.* |

---

##### `Scope`<sup>Required</sup> <a name="Scope" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.scope"></a>

- *Type:* Constructs.Construct

The scope in which to define this construct.

---

##### `Id`<sup>Required</sup> <a name="Id" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.id"></a>

- *Type:* string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `Config`<sup>Required</sup> <a name="Config" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.Initializer.parameter.config"></a>

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig">ScheduleRotationConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.toString">ToString</a></code> | Returns a string representation of this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.addOverride">AddOverride</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.overrideLogicalId">OverrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.resetOverrideLogicalId">ResetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.toMetadata">ToMetadata</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.toTerraform">ToTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.putParticipant">PutParticipant</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.putTimeRestriction">PutTimeRestriction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.resetEndDate">ResetEndDate</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.resetId">ResetId</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.resetLength">ResetLength</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.resetName">ResetName</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.resetTimeRestriction">ResetTimeRestriction</a></code> | *No description.* |

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.toString"></a>

```csharp
private string ToString()
```

Returns a string representation of this construct.

##### `AddOverride` <a name="AddOverride" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.addOverride"></a>

```csharp
private void AddOverride(string Path, object Value)
```

###### `Path`<sup>Required</sup> <a name="Path" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.addOverride.parameter.path"></a>

- *Type:* string

---

###### `Value`<sup>Required</sup> <a name="Value" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.addOverride.parameter.value"></a>

- *Type:* object

---

##### `OverrideLogicalId` <a name="OverrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.overrideLogicalId"></a>

```csharp
private void OverrideLogicalId(string NewLogicalId)
```

Overrides the auto-generated logical ID with a specific ID.

###### `NewLogicalId`<sup>Required</sup> <a name="NewLogicalId" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* string

The new logical ID to use for this stack element.

---

##### `ResetOverrideLogicalId` <a name="ResetOverrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.resetOverrideLogicalId"></a>

```csharp
private void ResetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `ToMetadata` <a name="ToMetadata" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.toMetadata"></a>

```csharp
private object ToMetadata()
```

##### `ToTerraform` <a name="ToTerraform" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.toTerraform"></a>

```csharp
private object ToTerraform()
```

Adds this resource to the terraform JSON output.

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `PutParticipant` <a name="PutParticipant" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.putParticipant"></a>

```csharp
private void PutParticipant(object Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.putParticipant.parameter.value"></a>

- *Type:* object

---

##### `PutTimeRestriction` <a name="PutTimeRestriction" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.putTimeRestriction"></a>

```csharp
private void PutTimeRestriction(object Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.putTimeRestriction.parameter.value"></a>

- *Type:* object

---

##### `ResetEndDate` <a name="ResetEndDate" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.resetEndDate"></a>

```csharp
private void ResetEndDate()
```

##### `ResetId` <a name="ResetId" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.resetId"></a>

```csharp
private void ResetId()
```

##### `ResetLength` <a name="ResetLength" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.resetLength"></a>

```csharp
private void ResetLength()
```

##### `ResetName` <a name="ResetName" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.resetName"></a>

```csharp
private void ResetName()
```

##### `ResetTimeRestriction` <a name="ResetTimeRestriction" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.resetTimeRestriction"></a>

```csharp
private void ResetTimeRestriction()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.isConstruct">IsConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.isTerraformElement">IsTerraformElement</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.isTerraformResource">IsTerraformResource</a></code> | *No description.* |

---

##### `IsConstruct` <a name="IsConstruct" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.isConstruct"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

ScheduleRotation.IsConstruct(object X);
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

###### `X`<sup>Required</sup> <a name="X" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.isConstruct.parameter.x"></a>

- *Type:* object

Any object.

---

##### `IsTerraformElement` <a name="IsTerraformElement" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.isTerraformElement"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

ScheduleRotation.IsTerraformElement(object X);
```

###### `X`<sup>Required</sup> <a name="X" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.isTerraformElement.parameter.x"></a>

- *Type:* object

---

##### `IsTerraformResource` <a name="IsTerraformResource" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.isTerraformResource"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

ScheduleRotation.IsTerraformResource(object X);
```

###### `X`<sup>Required</sup> <a name="X" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.isTerraformResource.parameter.x"></a>

- *Type:* object

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.node">Node</a></code> | <code>Constructs.Node</code> | The tree node. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.cdktfStack">CdktfStack</a></code> | <code>HashiCorp.Cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.friendlyUniqueId">FriendlyUniqueId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.terraformMetaArguments">TerraformMetaArguments</a></code> | <code>System.Collections.Generic.IDictionary<string, object></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.terraformResourceType">TerraformResourceType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.terraformGeneratorMetadata">TerraformGeneratorMetadata</a></code> | <code>HashiCorp.Cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.connection">Connection</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.count">Count</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.dependsOn">DependsOn</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.forEach">ForEach</a></code> | <code>HashiCorp.Cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.lifecycle">Lifecycle</a></code> | <code>HashiCorp.Cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.provider">Provider</a></code> | <code>HashiCorp.Cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.provisioners">Provisioners</a></code> | <code>object[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.participant">Participant</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList">ScheduleRotationParticipantList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.timeRestriction">TimeRestriction</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList">ScheduleRotationTimeRestrictionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.endDateInput">EndDateInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.idInput">IdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.lengthInput">LengthInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.nameInput">NameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.participantInput">ParticipantInput</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.scheduleIdInput">ScheduleIdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.startDateInput">StartDateInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.timeRestrictionInput">TimeRestrictionInput</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.typeInput">TypeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.endDate">EndDate</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.id">Id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.length">Length</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.name">Name</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.scheduleId">ScheduleId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.startDate">StartDate</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.type">Type</a></code> | <code>string</code> | *No description.* |

---

##### `Node`<sup>Required</sup> <a name="Node" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.node"></a>

```csharp
public Node Node { get; }
```

- *Type:* Constructs.Node

The tree node.

---

##### `CdktfStack`<sup>Required</sup> <a name="CdktfStack" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.cdktfStack"></a>

```csharp
public TerraformStack CdktfStack { get; }
```

- *Type:* HashiCorp.Cdktf.TerraformStack

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `FriendlyUniqueId`<sup>Required</sup> <a name="FriendlyUniqueId" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.friendlyUniqueId"></a>

```csharp
public string FriendlyUniqueId { get; }
```

- *Type:* string

---

##### `TerraformMetaArguments`<sup>Required</sup> <a name="TerraformMetaArguments" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.terraformMetaArguments"></a>

```csharp
public System.Collections.Generic.IDictionary<string, object> TerraformMetaArguments { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, object>

---

##### `TerraformResourceType`<sup>Required</sup> <a name="TerraformResourceType" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.terraformResourceType"></a>

```csharp
public string TerraformResourceType { get; }
```

- *Type:* string

---

##### `TerraformGeneratorMetadata`<sup>Optional</sup> <a name="TerraformGeneratorMetadata" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.terraformGeneratorMetadata"></a>

```csharp
public TerraformProviderGeneratorMetadata TerraformGeneratorMetadata { get; }
```

- *Type:* HashiCorp.Cdktf.TerraformProviderGeneratorMetadata

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.connection"></a>

```csharp
public object Connection { get; }
```

- *Type:* object

---

##### `Count`<sup>Optional</sup> <a name="Count" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.count"></a>

```csharp
public object Count { get; }
```

- *Type:* object

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.dependsOn"></a>

```csharp
public string[] DependsOn { get; }
```

- *Type:* string[]

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.forEach"></a>

```csharp
public ITerraformIterator ForEach { get; }
```

- *Type:* HashiCorp.Cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.lifecycle"></a>

```csharp
public TerraformResourceLifecycle Lifecycle { get; }
```

- *Type:* HashiCorp.Cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.provider"></a>

```csharp
public TerraformProvider Provider { get; }
```

- *Type:* HashiCorp.Cdktf.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.provisioners"></a>

```csharp
public object[] Provisioners { get; }
```

- *Type:* object[]

---

##### `Participant`<sup>Required</sup> <a name="Participant" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.participant"></a>

```csharp
public ScheduleRotationParticipantList Participant { get; }
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList">ScheduleRotationParticipantList</a>

---

##### `TimeRestriction`<sup>Required</sup> <a name="TimeRestriction" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.timeRestriction"></a>

```csharp
public ScheduleRotationTimeRestrictionList TimeRestriction { get; }
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList">ScheduleRotationTimeRestrictionList</a>

---

##### `EndDateInput`<sup>Optional</sup> <a name="EndDateInput" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.endDateInput"></a>

```csharp
public string EndDateInput { get; }
```

- *Type:* string

---

##### `IdInput`<sup>Optional</sup> <a name="IdInput" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.idInput"></a>

```csharp
public string IdInput { get; }
```

- *Type:* string

---

##### `LengthInput`<sup>Optional</sup> <a name="LengthInput" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.lengthInput"></a>

```csharp
public double LengthInput { get; }
```

- *Type:* double

---

##### `NameInput`<sup>Optional</sup> <a name="NameInput" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.nameInput"></a>

```csharp
public string NameInput { get; }
```

- *Type:* string

---

##### `ParticipantInput`<sup>Optional</sup> <a name="ParticipantInput" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.participantInput"></a>

```csharp
public object ParticipantInput { get; }
```

- *Type:* object

---

##### `ScheduleIdInput`<sup>Optional</sup> <a name="ScheduleIdInput" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.scheduleIdInput"></a>

```csharp
public string ScheduleIdInput { get; }
```

- *Type:* string

---

##### `StartDateInput`<sup>Optional</sup> <a name="StartDateInput" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.startDateInput"></a>

```csharp
public string StartDateInput { get; }
```

- *Type:* string

---

##### `TimeRestrictionInput`<sup>Optional</sup> <a name="TimeRestrictionInput" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.timeRestrictionInput"></a>

```csharp
public object TimeRestrictionInput { get; }
```

- *Type:* object

---

##### `TypeInput`<sup>Optional</sup> <a name="TypeInput" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.typeInput"></a>

```csharp
public string TypeInput { get; }
```

- *Type:* string

---

##### `EndDate`<sup>Required</sup> <a name="EndDate" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.endDate"></a>

```csharp
public string EndDate { get; }
```

- *Type:* string

---

##### `Id`<sup>Required</sup> <a name="Id" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.id"></a>

```csharp
public string Id { get; }
```

- *Type:* string

---

##### `Length`<sup>Required</sup> <a name="Length" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.length"></a>

```csharp
public double Length { get; }
```

- *Type:* double

---

##### `Name`<sup>Required</sup> <a name="Name" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.name"></a>

```csharp
public string Name { get; }
```

- *Type:* string

---

##### `ScheduleId`<sup>Required</sup> <a name="ScheduleId" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.scheduleId"></a>

```csharp
public string ScheduleId { get; }
```

- *Type:* string

---

##### `StartDate`<sup>Required</sup> <a name="StartDate" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.startDate"></a>

```csharp
public string StartDate { get; }
```

- *Type:* string

---

##### `Type`<sup>Required</sup> <a name="Type" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.type"></a>

```csharp
public string Type { get; }
```

- *Type:* string

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.tfResourceType">TfResourceType</a></code> | <code>string</code> | *No description.* |

---

##### `TfResourceType`<sup>Required</sup> <a name="TfResourceType" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotation.property.tfResourceType"></a>

```csharp
public string TfResourceType { get; }
```

- *Type:* string

---

## Structs <a name="Structs" id="Structs"></a>

### ScheduleRotationConfig <a name="ScheduleRotationConfig" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new ScheduleRotationConfig {
    object Connection = null,
    object Count = null,
    ITerraformDependable[] DependsOn = null,
    ITerraformIterator ForEach = null,
    TerraformResourceLifecycle Lifecycle = null,
    TerraformProvider Provider = null,
    object[] Provisioners = null,
    object Participant,
    string ScheduleId,
    string StartDate,
    string Type,
    string EndDate = null,
    string Id = null,
    double Length = null,
    string Name = null,
    object TimeRestriction = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.connection">Connection</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.count">Count</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.dependsOn">DependsOn</a></code> | <code>HashiCorp.Cdktf.ITerraformDependable[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.forEach">ForEach</a></code> | <code>HashiCorp.Cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.lifecycle">Lifecycle</a></code> | <code>HashiCorp.Cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.provider">Provider</a></code> | <code>HashiCorp.Cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.provisioners">Provisioners</a></code> | <code>object[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.participant">Participant</a></code> | <code>object</code> | participant block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.scheduleId">ScheduleId</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#schedule_id ScheduleRotation#schedule_id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.startDate">StartDate</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#start_date ScheduleRotation#start_date}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.type">Type</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#type ScheduleRotation#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.endDate">EndDate</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#end_date ScheduleRotation#end_date}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.id">Id</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#id ScheduleRotation#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.length">Length</a></code> | <code>double</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#length ScheduleRotation#length}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.name">Name</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#name ScheduleRotation#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.timeRestriction">TimeRestriction</a></code> | <code>object</code> | time_restriction block. |

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.connection"></a>

```csharp
public object Connection { get; set; }
```

- *Type:* object

---

##### `Count`<sup>Optional</sup> <a name="Count" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.count"></a>

```csharp
public object Count { get; set; }
```

- *Type:* object

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.dependsOn"></a>

```csharp
public ITerraformDependable[] DependsOn { get; set; }
```

- *Type:* HashiCorp.Cdktf.ITerraformDependable[]

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.forEach"></a>

```csharp
public ITerraformIterator ForEach { get; set; }
```

- *Type:* HashiCorp.Cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.lifecycle"></a>

```csharp
public TerraformResourceLifecycle Lifecycle { get; set; }
```

- *Type:* HashiCorp.Cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.provider"></a>

```csharp
public TerraformProvider Provider { get; set; }
```

- *Type:* HashiCorp.Cdktf.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.provisioners"></a>

```csharp
public object[] Provisioners { get; set; }
```

- *Type:* object[]

---

##### `Participant`<sup>Required</sup> <a name="Participant" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.participant"></a>

```csharp
public object Participant { get; set; }
```

- *Type:* object

participant block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#participant ScheduleRotation#participant}

---

##### `ScheduleId`<sup>Required</sup> <a name="ScheduleId" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.scheduleId"></a>

```csharp
public string ScheduleId { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#schedule_id ScheduleRotation#schedule_id}.

---

##### `StartDate`<sup>Required</sup> <a name="StartDate" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.startDate"></a>

```csharp
public string StartDate { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#start_date ScheduleRotation#start_date}.

---

##### `Type`<sup>Required</sup> <a name="Type" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.type"></a>

```csharp
public string Type { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#type ScheduleRotation#type}.

---

##### `EndDate`<sup>Optional</sup> <a name="EndDate" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.endDate"></a>

```csharp
public string EndDate { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#end_date ScheduleRotation#end_date}.

---

##### `Id`<sup>Optional</sup> <a name="Id" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.id"></a>

```csharp
public string Id { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#id ScheduleRotation#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `Length`<sup>Optional</sup> <a name="Length" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.length"></a>

```csharp
public double Length { get; set; }
```

- *Type:* double

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#length ScheduleRotation#length}.

---

##### `Name`<sup>Optional</sup> <a name="Name" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.name"></a>

```csharp
public string Name { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#name ScheduleRotation#name}.

---

##### `TimeRestriction`<sup>Optional</sup> <a name="TimeRestriction" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationConfig.property.timeRestriction"></a>

```csharp
public object TimeRestriction { get; set; }
```

- *Type:* object

time_restriction block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#time_restriction ScheduleRotation#time_restriction}

---

### ScheduleRotationParticipant <a name="ScheduleRotationParticipant" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipant"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipant.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new ScheduleRotationParticipant {
    string Type,
    string Id = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipant.property.type">Type</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#type ScheduleRotation#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipant.property.id">Id</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#id ScheduleRotation#id}. |

---

##### `Type`<sup>Required</sup> <a name="Type" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipant.property.type"></a>

```csharp
public string Type { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#type ScheduleRotation#type}.

---

##### `Id`<sup>Optional</sup> <a name="Id" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipant.property.id"></a>

```csharp
public string Id { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#id ScheduleRotation#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

### ScheduleRotationTimeRestriction <a name="ScheduleRotationTimeRestriction" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestriction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestriction.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new ScheduleRotationTimeRestriction {
    string Type,
    object Restriction = null,
    object Restrictions = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestriction.property.type">Type</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#type ScheduleRotation#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestriction.property.restriction">Restriction</a></code> | <code>object</code> | restriction block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestriction.property.restrictions">Restrictions</a></code> | <code>object</code> | restrictions block. |

---

##### `Type`<sup>Required</sup> <a name="Type" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestriction.property.type"></a>

```csharp
public string Type { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#type ScheduleRotation#type}.

---

##### `Restriction`<sup>Optional</sup> <a name="Restriction" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestriction.property.restriction"></a>

```csharp
public object Restriction { get; set; }
```

- *Type:* object

restriction block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#restriction ScheduleRotation#restriction}

---

##### `Restrictions`<sup>Optional</sup> <a name="Restrictions" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestriction.property.restrictions"></a>

```csharp
public object Restrictions { get; set; }
```

- *Type:* object

restrictions block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#restrictions ScheduleRotation#restrictions}

---

### ScheduleRotationTimeRestrictionRestriction <a name="ScheduleRotationTimeRestrictionRestriction" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestriction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestriction.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new ScheduleRotationTimeRestrictionRestriction {
    double EndHour,
    double EndMin,
    double StartHour,
    double StartMin
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestriction.property.endHour">EndHour</a></code> | <code>double</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#end_hour ScheduleRotation#end_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestriction.property.endMin">EndMin</a></code> | <code>double</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#end_min ScheduleRotation#end_min}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestriction.property.startHour">StartHour</a></code> | <code>double</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#start_hour ScheduleRotation#start_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestriction.property.startMin">StartMin</a></code> | <code>double</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#start_min ScheduleRotation#start_min}. |

---

##### `EndHour`<sup>Required</sup> <a name="EndHour" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestriction.property.endHour"></a>

```csharp
public double EndHour { get; set; }
```

- *Type:* double

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#end_hour ScheduleRotation#end_hour}.

---

##### `EndMin`<sup>Required</sup> <a name="EndMin" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestriction.property.endMin"></a>

```csharp
public double EndMin { get; set; }
```

- *Type:* double

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#end_min ScheduleRotation#end_min}.

---

##### `StartHour`<sup>Required</sup> <a name="StartHour" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestriction.property.startHour"></a>

```csharp
public double StartHour { get; set; }
```

- *Type:* double

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#start_hour ScheduleRotation#start_hour}.

---

##### `StartMin`<sup>Required</sup> <a name="StartMin" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestriction.property.startMin"></a>

```csharp
public double StartMin { get; set; }
```

- *Type:* double

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#start_min ScheduleRotation#start_min}.

---

### ScheduleRotationTimeRestrictionRestrictions <a name="ScheduleRotationTimeRestrictionRestrictions" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictions"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictions.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new ScheduleRotationTimeRestrictionRestrictions {
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
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictions.property.endDay">EndDay</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#end_day ScheduleRotation#end_day}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictions.property.endHour">EndHour</a></code> | <code>double</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#end_hour ScheduleRotation#end_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictions.property.endMin">EndMin</a></code> | <code>double</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#end_min ScheduleRotation#end_min}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictions.property.startDay">StartDay</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#start_day ScheduleRotation#start_day}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictions.property.startHour">StartHour</a></code> | <code>double</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#start_hour ScheduleRotation#start_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictions.property.startMin">StartMin</a></code> | <code>double</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#start_min ScheduleRotation#start_min}. |

---

##### `EndDay`<sup>Required</sup> <a name="EndDay" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictions.property.endDay"></a>

```csharp
public string EndDay { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#end_day ScheduleRotation#end_day}.

---

##### `EndHour`<sup>Required</sup> <a name="EndHour" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictions.property.endHour"></a>

```csharp
public double EndHour { get; set; }
```

- *Type:* double

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#end_hour ScheduleRotation#end_hour}.

---

##### `EndMin`<sup>Required</sup> <a name="EndMin" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictions.property.endMin"></a>

```csharp
public double EndMin { get; set; }
```

- *Type:* double

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#end_min ScheduleRotation#end_min}.

---

##### `StartDay`<sup>Required</sup> <a name="StartDay" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictions.property.startDay"></a>

```csharp
public string StartDay { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#start_day ScheduleRotation#start_day}.

---

##### `StartHour`<sup>Required</sup> <a name="StartHour" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictions.property.startHour"></a>

```csharp
public double StartHour { get; set; }
```

- *Type:* double

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#start_hour ScheduleRotation#start_hour}.

---

##### `StartMin`<sup>Required</sup> <a name="StartMin" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictions.property.startMin"></a>

```csharp
public double StartMin { get; set; }
```

- *Type:* double

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/schedule_rotation#start_min ScheduleRotation#start_min}.

---

## Classes <a name="Classes" id="Classes"></a>

### ScheduleRotationParticipantList <a name="ScheduleRotationParticipantList" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new ScheduleRotationParticipantList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>HashiCorp.Cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.Initializer.parameter.terraformResource"></a>

- *Type:* HashiCorp.Cdktf.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.get">Get</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.resolve.parameter._context"></a>

- *Type:* HashiCorp.Cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.get"></a>

```csharp
private ScheduleRotationParticipantOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.property.internalValue">InternalValue</a></code> | <code>object</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantList.property.internalValue"></a>

```csharp
public object InternalValue { get; }
```

- *Type:* object

---


### ScheduleRotationParticipantOutputReference <a name="ScheduleRotationParticipantOutputReference" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new ScheduleRotationParticipantOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>HashiCorp.Cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* HashiCorp.Cdktf.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.resetId">ResetId</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.resolve.parameter._context"></a>

- *Type:* HashiCorp.Cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetId` <a name="ResetId" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.resetId"></a>

```csharp
private void ResetId()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.property.idInput">IdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.property.typeInput">TypeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.property.id">Id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.property.type">Type</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.property.internalValue">InternalValue</a></code> | <code>object</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `IdInput`<sup>Optional</sup> <a name="IdInput" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.property.idInput"></a>

```csharp
public string IdInput { get; }
```

- *Type:* string

---

##### `TypeInput`<sup>Optional</sup> <a name="TypeInput" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.property.typeInput"></a>

```csharp
public string TypeInput { get; }
```

- *Type:* string

---

##### `Id`<sup>Required</sup> <a name="Id" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.property.id"></a>

```csharp
public string Id { get; }
```

- *Type:* string

---

##### `Type`<sup>Required</sup> <a name="Type" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.property.type"></a>

```csharp
public string Type { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationParticipantOutputReference.property.internalValue"></a>

```csharp
public object InternalValue { get; }
```

- *Type:* object

---


### ScheduleRotationTimeRestrictionList <a name="ScheduleRotationTimeRestrictionList" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new ScheduleRotationTimeRestrictionList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>HashiCorp.Cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.Initializer.parameter.terraformResource"></a>

- *Type:* HashiCorp.Cdktf.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.get">Get</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.resolve.parameter._context"></a>

- *Type:* HashiCorp.Cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.get"></a>

```csharp
private ScheduleRotationTimeRestrictionOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.property.internalValue">InternalValue</a></code> | <code>object</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionList.property.internalValue"></a>

```csharp
public object InternalValue { get; }
```

- *Type:* object

---


### ScheduleRotationTimeRestrictionOutputReference <a name="ScheduleRotationTimeRestrictionOutputReference" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new ScheduleRotationTimeRestrictionOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>HashiCorp.Cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* HashiCorp.Cdktf.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.putRestriction">PutRestriction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.putRestrictions">PutRestrictions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.resetRestriction">ResetRestriction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.resetRestrictions">ResetRestrictions</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.resolve.parameter._context"></a>

- *Type:* HashiCorp.Cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `PutRestriction` <a name="PutRestriction" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.putRestriction"></a>

```csharp
private void PutRestriction(object Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.putRestriction.parameter.value"></a>

- *Type:* object

---

##### `PutRestrictions` <a name="PutRestrictions" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.putRestrictions"></a>

```csharp
private void PutRestrictions(object Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.putRestrictions.parameter.value"></a>

- *Type:* object

---

##### `ResetRestriction` <a name="ResetRestriction" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.resetRestriction"></a>

```csharp
private void ResetRestriction()
```

##### `ResetRestrictions` <a name="ResetRestrictions" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.resetRestrictions"></a>

```csharp
private void ResetRestrictions()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.property.restriction">Restriction</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList">ScheduleRotationTimeRestrictionRestrictionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.property.restrictions">Restrictions</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList">ScheduleRotationTimeRestrictionRestrictionsList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.property.restrictionInput">RestrictionInput</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.property.restrictionsInput">RestrictionsInput</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.property.typeInput">TypeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.property.type">Type</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.property.internalValue">InternalValue</a></code> | <code>object</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `Restriction`<sup>Required</sup> <a name="Restriction" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.property.restriction"></a>

```csharp
public ScheduleRotationTimeRestrictionRestrictionList Restriction { get; }
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList">ScheduleRotationTimeRestrictionRestrictionList</a>

---

##### `Restrictions`<sup>Required</sup> <a name="Restrictions" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.property.restrictions"></a>

```csharp
public ScheduleRotationTimeRestrictionRestrictionsList Restrictions { get; }
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList">ScheduleRotationTimeRestrictionRestrictionsList</a>

---

##### `RestrictionInput`<sup>Optional</sup> <a name="RestrictionInput" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.property.restrictionInput"></a>

```csharp
public object RestrictionInput { get; }
```

- *Type:* object

---

##### `RestrictionsInput`<sup>Optional</sup> <a name="RestrictionsInput" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.property.restrictionsInput"></a>

```csharp
public object RestrictionsInput { get; }
```

- *Type:* object

---

##### `TypeInput`<sup>Optional</sup> <a name="TypeInput" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.property.typeInput"></a>

```csharp
public string TypeInput { get; }
```

- *Type:* string

---

##### `Type`<sup>Required</sup> <a name="Type" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.property.type"></a>

```csharp
public string Type { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionOutputReference.property.internalValue"></a>

```csharp
public object InternalValue { get; }
```

- *Type:* object

---


### ScheduleRotationTimeRestrictionRestrictionList <a name="ScheduleRotationTimeRestrictionRestrictionList" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new ScheduleRotationTimeRestrictionRestrictionList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>HashiCorp.Cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.Initializer.parameter.terraformResource"></a>

- *Type:* HashiCorp.Cdktf.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.get">Get</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.resolve.parameter._context"></a>

- *Type:* HashiCorp.Cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.get"></a>

```csharp
private ScheduleRotationTimeRestrictionRestrictionOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.property.internalValue">InternalValue</a></code> | <code>object</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionList.property.internalValue"></a>

```csharp
public object InternalValue { get; }
```

- *Type:* object

---


### ScheduleRotationTimeRestrictionRestrictionOutputReference <a name="ScheduleRotationTimeRestrictionRestrictionOutputReference" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new ScheduleRotationTimeRestrictionRestrictionOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>HashiCorp.Cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* HashiCorp.Cdktf.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.resolve.parameter._context"></a>

- *Type:* HashiCorp.Cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.endHourInput">EndHourInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.endMinInput">EndMinInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.startHourInput">StartHourInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.startMinInput">StartMinInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.endHour">EndHour</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.endMin">EndMin</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.startHour">StartHour</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.startMin">StartMin</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.internalValue">InternalValue</a></code> | <code>object</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `EndHourInput`<sup>Optional</sup> <a name="EndHourInput" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.endHourInput"></a>

```csharp
public double EndHourInput { get; }
```

- *Type:* double

---

##### `EndMinInput`<sup>Optional</sup> <a name="EndMinInput" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.endMinInput"></a>

```csharp
public double EndMinInput { get; }
```

- *Type:* double

---

##### `StartHourInput`<sup>Optional</sup> <a name="StartHourInput" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.startHourInput"></a>

```csharp
public double StartHourInput { get; }
```

- *Type:* double

---

##### `StartMinInput`<sup>Optional</sup> <a name="StartMinInput" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.startMinInput"></a>

```csharp
public double StartMinInput { get; }
```

- *Type:* double

---

##### `EndHour`<sup>Required</sup> <a name="EndHour" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.endHour"></a>

```csharp
public double EndHour { get; }
```

- *Type:* double

---

##### `EndMin`<sup>Required</sup> <a name="EndMin" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.endMin"></a>

```csharp
public double EndMin { get; }
```

- *Type:* double

---

##### `StartHour`<sup>Required</sup> <a name="StartHour" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.startHour"></a>

```csharp
public double StartHour { get; }
```

- *Type:* double

---

##### `StartMin`<sup>Required</sup> <a name="StartMin" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.startMin"></a>

```csharp
public double StartMin { get; }
```

- *Type:* double

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionOutputReference.property.internalValue"></a>

```csharp
public object InternalValue { get; }
```

- *Type:* object

---


### ScheduleRotationTimeRestrictionRestrictionsList <a name="ScheduleRotationTimeRestrictionRestrictionsList" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new ScheduleRotationTimeRestrictionRestrictionsList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>HashiCorp.Cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.Initializer.parameter.terraformResource"></a>

- *Type:* HashiCorp.Cdktf.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.get">Get</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.resolve.parameter._context"></a>

- *Type:* HashiCorp.Cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.get"></a>

```csharp
private ScheduleRotationTimeRestrictionRestrictionsOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.property.internalValue">InternalValue</a></code> | <code>object</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsList.property.internalValue"></a>

```csharp
public object InternalValue { get; }
```

- *Type:* object

---


### ScheduleRotationTimeRestrictionRestrictionsOutputReference <a name="ScheduleRotationTimeRestrictionRestrictionsOutputReference" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new ScheduleRotationTimeRestrictionRestrictionsOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>HashiCorp.Cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* HashiCorp.Cdktf.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.resolve.parameter._context"></a>

- *Type:* HashiCorp.Cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.endDayInput">EndDayInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.endHourInput">EndHourInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.endMinInput">EndMinInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.startDayInput">StartDayInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.startHourInput">StartHourInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.startMinInput">StartMinInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.endDay">EndDay</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.endHour">EndHour</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.endMin">EndMin</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.startDay">StartDay</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.startHour">StartHour</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.startMin">StartMin</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.internalValue">InternalValue</a></code> | <code>object</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `EndDayInput`<sup>Optional</sup> <a name="EndDayInput" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.endDayInput"></a>

```csharp
public string EndDayInput { get; }
```

- *Type:* string

---

##### `EndHourInput`<sup>Optional</sup> <a name="EndHourInput" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.endHourInput"></a>

```csharp
public double EndHourInput { get; }
```

- *Type:* double

---

##### `EndMinInput`<sup>Optional</sup> <a name="EndMinInput" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.endMinInput"></a>

```csharp
public double EndMinInput { get; }
```

- *Type:* double

---

##### `StartDayInput`<sup>Optional</sup> <a name="StartDayInput" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.startDayInput"></a>

```csharp
public string StartDayInput { get; }
```

- *Type:* string

---

##### `StartHourInput`<sup>Optional</sup> <a name="StartHourInput" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.startHourInput"></a>

```csharp
public double StartHourInput { get; }
```

- *Type:* double

---

##### `StartMinInput`<sup>Optional</sup> <a name="StartMinInput" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.startMinInput"></a>

```csharp
public double StartMinInput { get; }
```

- *Type:* double

---

##### `EndDay`<sup>Required</sup> <a name="EndDay" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.endDay"></a>

```csharp
public string EndDay { get; }
```

- *Type:* string

---

##### `EndHour`<sup>Required</sup> <a name="EndHour" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.endHour"></a>

```csharp
public double EndHour { get; }
```

- *Type:* double

---

##### `EndMin`<sup>Required</sup> <a name="EndMin" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.endMin"></a>

```csharp
public double EndMin { get; }
```

- *Type:* double

---

##### `StartDay`<sup>Required</sup> <a name="StartDay" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.startDay"></a>

```csharp
public string StartDay { get; }
```

- *Type:* string

---

##### `StartHour`<sup>Required</sup> <a name="StartHour" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.startHour"></a>

```csharp
public double StartHour { get; }
```

- *Type:* double

---

##### `StartMin`<sup>Required</sup> <a name="StartMin" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.startMin"></a>

```csharp
public double StartMin { get; }
```

- *Type:* double

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.scheduleRotation.ScheduleRotationTimeRestrictionRestrictionsOutputReference.property.internalValue"></a>

```csharp
public object InternalValue { get; }
```

- *Type:* object

---



