# `data_opsgenie_heartbeat`

Refer to the Terraform Registory for docs: [`data_opsgenie_heartbeat`](https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat).

# `dataOpsgenieHeartbeat` Submodule <a name="`dataOpsgenieHeartbeat` Submodule" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### DataOpsgenieHeartbeat <a name="DataOpsgenieHeartbeat" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat"></a>

Represents a {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat opsgenie_heartbeat}.

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new DataOpsgenieHeartbeat(Construct Scope, string Id, DataOpsgenieHeartbeatConfig Config);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.scope">Scope</a></code> | <code>Constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.id">Id</a></code> | <code>string</code> | The scoped construct ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.config">Config</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig">DataOpsgenieHeartbeatConfig</a></code> | *No description.* |

---

##### `Scope`<sup>Required</sup> <a name="Scope" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.scope"></a>

- *Type:* Constructs.Construct

The scope in which to define this construct.

---

##### `Id`<sup>Required</sup> <a name="Id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.id"></a>

- *Type:* string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `Config`<sup>Required</sup> <a name="Config" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.config"></a>

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig">DataOpsgenieHeartbeatConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.toString">ToString</a></code> | Returns a string representation of this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.addOverride">AddOverride</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.overrideLogicalId">OverrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetOverrideLogicalId">ResetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.toMetadata">ToMetadata</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.toTerraform">ToTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetAlertMessage">ResetAlertMessage</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetAlertPriority">ResetAlertPriority</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetAlertTags">ResetAlertTags</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetDescription">ResetDescription</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetEnabled">ResetEnabled</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetId">ResetId</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetInterval">ResetInterval</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetIntervalUnit">ResetIntervalUnit</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetOwnerTeamId">ResetOwnerTeamId</a></code> | *No description.* |

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.toString"></a>

```csharp
private string ToString()
```

Returns a string representation of this construct.

##### `AddOverride` <a name="AddOverride" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.addOverride"></a>

```csharp
private void AddOverride(string Path, object Value)
```

###### `Path`<sup>Required</sup> <a name="Path" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.addOverride.parameter.path"></a>

- *Type:* string

---

###### `Value`<sup>Required</sup> <a name="Value" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.addOverride.parameter.value"></a>

- *Type:* object

---

##### `OverrideLogicalId` <a name="OverrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.overrideLogicalId"></a>

```csharp
private void OverrideLogicalId(string NewLogicalId)
```

Overrides the auto-generated logical ID with a specific ID.

###### `NewLogicalId`<sup>Required</sup> <a name="NewLogicalId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* string

The new logical ID to use for this stack element.

---

##### `ResetOverrideLogicalId` <a name="ResetOverrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetOverrideLogicalId"></a>

```csharp
private void ResetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `ToMetadata` <a name="ToMetadata" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.toMetadata"></a>

```csharp
private object ToMetadata()
```

##### `ToTerraform` <a name="ToTerraform" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.toTerraform"></a>

```csharp
private object ToTerraform()
```

Adds this resource to the terraform JSON output.

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `ResetAlertMessage` <a name="ResetAlertMessage" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetAlertMessage"></a>

```csharp
private void ResetAlertMessage()
```

##### `ResetAlertPriority` <a name="ResetAlertPriority" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetAlertPriority"></a>

```csharp
private void ResetAlertPriority()
```

##### `ResetAlertTags` <a name="ResetAlertTags" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetAlertTags"></a>

```csharp
private void ResetAlertTags()
```

##### `ResetDescription` <a name="ResetDescription" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetDescription"></a>

```csharp
private void ResetDescription()
```

##### `ResetEnabled` <a name="ResetEnabled" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetEnabled"></a>

```csharp
private void ResetEnabled()
```

##### `ResetId` <a name="ResetId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetId"></a>

```csharp
private void ResetId()
```

##### `ResetInterval` <a name="ResetInterval" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetInterval"></a>

```csharp
private void ResetInterval()
```

##### `ResetIntervalUnit` <a name="ResetIntervalUnit" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetIntervalUnit"></a>

```csharp
private void ResetIntervalUnit()
```

##### `ResetOwnerTeamId` <a name="ResetOwnerTeamId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetOwnerTeamId"></a>

```csharp
private void ResetOwnerTeamId()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isConstruct">IsConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isTerraformElement">IsTerraformElement</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isTerraformDataSource">IsTerraformDataSource</a></code> | *No description.* |

---

##### `IsConstruct` <a name="IsConstruct" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isConstruct"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

DataOpsgenieHeartbeat.IsConstruct(object X);
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

###### `X`<sup>Required</sup> <a name="X" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isConstruct.parameter.x"></a>

- *Type:* object

Any object.

---

##### `IsTerraformElement` <a name="IsTerraformElement" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isTerraformElement"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

DataOpsgenieHeartbeat.IsTerraformElement(object X);
```

###### `X`<sup>Required</sup> <a name="X" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isTerraformElement.parameter.x"></a>

- *Type:* object

---

##### `IsTerraformDataSource` <a name="IsTerraformDataSource" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isTerraformDataSource"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

DataOpsgenieHeartbeat.IsTerraformDataSource(object X);
```

###### `X`<sup>Required</sup> <a name="X" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isTerraformDataSource.parameter.x"></a>

- *Type:* object

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.node">Node</a></code> | <code>Constructs.Node</code> | The tree node. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.cdktfStack">CdktfStack</a></code> | <code>HashiCorp.Cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.friendlyUniqueId">FriendlyUniqueId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.terraformMetaArguments">TerraformMetaArguments</a></code> | <code>System.Collections.Generic.IDictionary<string, object></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.terraformResourceType">TerraformResourceType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.terraformGeneratorMetadata">TerraformGeneratorMetadata</a></code> | <code>HashiCorp.Cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.count">Count</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.dependsOn">DependsOn</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.forEach">ForEach</a></code> | <code>HashiCorp.Cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.lifecycle">Lifecycle</a></code> | <code>HashiCorp.Cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.provider">Provider</a></code> | <code>HashiCorp.Cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertMessageInput">AlertMessageInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertPriorityInput">AlertPriorityInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertTagsInput">AlertTagsInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.descriptionInput">DescriptionInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.enabledInput">EnabledInput</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.idInput">IdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.intervalInput">IntervalInput</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.intervalUnitInput">IntervalUnitInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.nameInput">NameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.ownerTeamIdInput">OwnerTeamIdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertMessage">AlertMessage</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertPriority">AlertPriority</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertTags">AlertTags</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.description">Description</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.enabled">Enabled</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.id">Id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.interval">Interval</a></code> | <code>double</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.intervalUnit">IntervalUnit</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.name">Name</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.ownerTeamId">OwnerTeamId</a></code> | <code>string</code> | *No description.* |

---

##### `Node`<sup>Required</sup> <a name="Node" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.node"></a>

```csharp
public Node Node { get; }
```

- *Type:* Constructs.Node

The tree node.

---

##### `CdktfStack`<sup>Required</sup> <a name="CdktfStack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.cdktfStack"></a>

```csharp
public TerraformStack CdktfStack { get; }
```

- *Type:* HashiCorp.Cdktf.TerraformStack

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `FriendlyUniqueId`<sup>Required</sup> <a name="FriendlyUniqueId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.friendlyUniqueId"></a>

```csharp
public string FriendlyUniqueId { get; }
```

- *Type:* string

---

##### `TerraformMetaArguments`<sup>Required</sup> <a name="TerraformMetaArguments" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.terraformMetaArguments"></a>

```csharp
public System.Collections.Generic.IDictionary<string, object> TerraformMetaArguments { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, object>

---

##### `TerraformResourceType`<sup>Required</sup> <a name="TerraformResourceType" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.terraformResourceType"></a>

```csharp
public string TerraformResourceType { get; }
```

- *Type:* string

---

##### `TerraformGeneratorMetadata`<sup>Optional</sup> <a name="TerraformGeneratorMetadata" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.terraformGeneratorMetadata"></a>

```csharp
public TerraformProviderGeneratorMetadata TerraformGeneratorMetadata { get; }
```

- *Type:* HashiCorp.Cdktf.TerraformProviderGeneratorMetadata

---

##### `Count`<sup>Optional</sup> <a name="Count" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.count"></a>

```csharp
public object Count { get; }
```

- *Type:* object

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.dependsOn"></a>

```csharp
public string[] DependsOn { get; }
```

- *Type:* string[]

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.forEach"></a>

```csharp
public ITerraformIterator ForEach { get; }
```

- *Type:* HashiCorp.Cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.lifecycle"></a>

```csharp
public TerraformResourceLifecycle Lifecycle { get; }
```

- *Type:* HashiCorp.Cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.provider"></a>

```csharp
public TerraformProvider Provider { get; }
```

- *Type:* HashiCorp.Cdktf.TerraformProvider

---

##### `AlertMessageInput`<sup>Optional</sup> <a name="AlertMessageInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertMessageInput"></a>

```csharp
public string AlertMessageInput { get; }
```

- *Type:* string

---

##### `AlertPriorityInput`<sup>Optional</sup> <a name="AlertPriorityInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertPriorityInput"></a>

```csharp
public string AlertPriorityInput { get; }
```

- *Type:* string

---

##### `AlertTagsInput`<sup>Optional</sup> <a name="AlertTagsInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertTagsInput"></a>

```csharp
public string[] AlertTagsInput { get; }
```

- *Type:* string[]

---

##### `DescriptionInput`<sup>Optional</sup> <a name="DescriptionInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.descriptionInput"></a>

```csharp
public string DescriptionInput { get; }
```

- *Type:* string

---

##### `EnabledInput`<sup>Optional</sup> <a name="EnabledInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.enabledInput"></a>

```csharp
public object EnabledInput { get; }
```

- *Type:* object

---

##### `IdInput`<sup>Optional</sup> <a name="IdInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.idInput"></a>

```csharp
public string IdInput { get; }
```

- *Type:* string

---

##### `IntervalInput`<sup>Optional</sup> <a name="IntervalInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.intervalInput"></a>

```csharp
public double IntervalInput { get; }
```

- *Type:* double

---

##### `IntervalUnitInput`<sup>Optional</sup> <a name="IntervalUnitInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.intervalUnitInput"></a>

```csharp
public string IntervalUnitInput { get; }
```

- *Type:* string

---

##### `NameInput`<sup>Optional</sup> <a name="NameInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.nameInput"></a>

```csharp
public string NameInput { get; }
```

- *Type:* string

---

##### `OwnerTeamIdInput`<sup>Optional</sup> <a name="OwnerTeamIdInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.ownerTeamIdInput"></a>

```csharp
public string OwnerTeamIdInput { get; }
```

- *Type:* string

---

##### `AlertMessage`<sup>Required</sup> <a name="AlertMessage" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertMessage"></a>

```csharp
public string AlertMessage { get; }
```

- *Type:* string

---

##### `AlertPriority`<sup>Required</sup> <a name="AlertPriority" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertPriority"></a>

```csharp
public string AlertPriority { get; }
```

- *Type:* string

---

##### `AlertTags`<sup>Required</sup> <a name="AlertTags" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertTags"></a>

```csharp
public string[] AlertTags { get; }
```

- *Type:* string[]

---

##### `Description`<sup>Required</sup> <a name="Description" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.description"></a>

```csharp
public string Description { get; }
```

- *Type:* string

---

##### `Enabled`<sup>Required</sup> <a name="Enabled" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.enabled"></a>

```csharp
public object Enabled { get; }
```

- *Type:* object

---

##### `Id`<sup>Required</sup> <a name="Id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.id"></a>

```csharp
public string Id { get; }
```

- *Type:* string

---

##### `Interval`<sup>Required</sup> <a name="Interval" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.interval"></a>

```csharp
public double Interval { get; }
```

- *Type:* double

---

##### `IntervalUnit`<sup>Required</sup> <a name="IntervalUnit" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.intervalUnit"></a>

```csharp
public string IntervalUnit { get; }
```

- *Type:* string

---

##### `Name`<sup>Required</sup> <a name="Name" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.name"></a>

```csharp
public string Name { get; }
```

- *Type:* string

---

##### `OwnerTeamId`<sup>Required</sup> <a name="OwnerTeamId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.ownerTeamId"></a>

```csharp
public string OwnerTeamId { get; }
```

- *Type:* string

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.tfResourceType">TfResourceType</a></code> | <code>string</code> | *No description.* |

---

##### `TfResourceType`<sup>Required</sup> <a name="TfResourceType" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.tfResourceType"></a>

```csharp
public string TfResourceType { get; }
```

- *Type:* string

---

## Structs <a name="Structs" id="Structs"></a>

### DataOpsgenieHeartbeatConfig <a name="DataOpsgenieHeartbeatConfig" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new DataOpsgenieHeartbeatConfig {
    object Connection = null,
    object Count = null,
    ITerraformDependable[] DependsOn = null,
    ITerraformIterator ForEach = null,
    TerraformResourceLifecycle Lifecycle = null,
    TerraformProvider Provider = null,
    object[] Provisioners = null,
    string Name,
    string AlertMessage = null,
    string AlertPriority = null,
    string[] AlertTags = null,
    string Description = null,
    object Enabled = null,
    string Id = null,
    double Interval = null,
    string IntervalUnit = null,
    string OwnerTeamId = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.connection">Connection</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.count">Count</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.dependsOn">DependsOn</a></code> | <code>HashiCorp.Cdktf.ITerraformDependable[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.forEach">ForEach</a></code> | <code>HashiCorp.Cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.lifecycle">Lifecycle</a></code> | <code>HashiCorp.Cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.provider">Provider</a></code> | <code>HashiCorp.Cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.provisioners">Provisioners</a></code> | <code>object[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.name">Name</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#name DataOpsgenieHeartbeat#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.alertMessage">AlertMessage</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_message DataOpsgenieHeartbeat#alert_message}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.alertPriority">AlertPriority</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_priority DataOpsgenieHeartbeat#alert_priority}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.alertTags">AlertTags</a></code> | <code>string[]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_tags DataOpsgenieHeartbeat#alert_tags}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.description">Description</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#description DataOpsgenieHeartbeat#description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.enabled">Enabled</a></code> | <code>object</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#enabled DataOpsgenieHeartbeat#enabled}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.id">Id</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#id DataOpsgenieHeartbeat#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.interval">Interval</a></code> | <code>double</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#interval DataOpsgenieHeartbeat#interval}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.intervalUnit">IntervalUnit</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#interval_unit DataOpsgenieHeartbeat#interval_unit}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.ownerTeamId">OwnerTeamId</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#owner_team_id DataOpsgenieHeartbeat#owner_team_id}. |

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.connection"></a>

```csharp
public object Connection { get; set; }
```

- *Type:* object

---

##### `Count`<sup>Optional</sup> <a name="Count" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.count"></a>

```csharp
public object Count { get; set; }
```

- *Type:* object

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.dependsOn"></a>

```csharp
public ITerraformDependable[] DependsOn { get; set; }
```

- *Type:* HashiCorp.Cdktf.ITerraformDependable[]

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.forEach"></a>

```csharp
public ITerraformIterator ForEach { get; set; }
```

- *Type:* HashiCorp.Cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.lifecycle"></a>

```csharp
public TerraformResourceLifecycle Lifecycle { get; set; }
```

- *Type:* HashiCorp.Cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.provider"></a>

```csharp
public TerraformProvider Provider { get; set; }
```

- *Type:* HashiCorp.Cdktf.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.provisioners"></a>

```csharp
public object[] Provisioners { get; set; }
```

- *Type:* object[]

---

##### `Name`<sup>Required</sup> <a name="Name" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.name"></a>

```csharp
public string Name { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#name DataOpsgenieHeartbeat#name}.

---

##### `AlertMessage`<sup>Optional</sup> <a name="AlertMessage" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.alertMessage"></a>

```csharp
public string AlertMessage { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_message DataOpsgenieHeartbeat#alert_message}.

---

##### `AlertPriority`<sup>Optional</sup> <a name="AlertPriority" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.alertPriority"></a>

```csharp
public string AlertPriority { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_priority DataOpsgenieHeartbeat#alert_priority}.

---

##### `AlertTags`<sup>Optional</sup> <a name="AlertTags" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.alertTags"></a>

```csharp
public string[] AlertTags { get; set; }
```

- *Type:* string[]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_tags DataOpsgenieHeartbeat#alert_tags}.

---

##### `Description`<sup>Optional</sup> <a name="Description" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.description"></a>

```csharp
public string Description { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#description DataOpsgenieHeartbeat#description}.

---

##### `Enabled`<sup>Optional</sup> <a name="Enabled" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.enabled"></a>

```csharp
public object Enabled { get; set; }
```

- *Type:* object

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#enabled DataOpsgenieHeartbeat#enabled}.

---

##### `Id`<sup>Optional</sup> <a name="Id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.id"></a>

```csharp
public string Id { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#id DataOpsgenieHeartbeat#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `Interval`<sup>Optional</sup> <a name="Interval" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.interval"></a>

```csharp
public double Interval { get; set; }
```

- *Type:* double

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#interval DataOpsgenieHeartbeat#interval}.

---

##### `IntervalUnit`<sup>Optional</sup> <a name="IntervalUnit" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.intervalUnit"></a>

```csharp
public string IntervalUnit { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#interval_unit DataOpsgenieHeartbeat#interval_unit}.

---

##### `OwnerTeamId`<sup>Optional</sup> <a name="OwnerTeamId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.ownerTeamId"></a>

```csharp
public string OwnerTeamId { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#owner_team_id DataOpsgenieHeartbeat#owner_team_id}.

---



