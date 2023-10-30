# `opsgenie_api_integration`

Refer to the Terraform Registory for docs: [`opsgenie_api_integration`](https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/api_integration).

# `apiIntegration` Submodule <a name="`apiIntegration` Submodule" id="rhizo-co-terraform-provider-opsgenie.apiIntegration"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### ApiIntegration <a name="ApiIntegration" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration"></a>

Represents a {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/api_integration opsgenie_api_integration}.

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new ApiIntegration(Construct Scope, string Id, ApiIntegrationConfig Config);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.Initializer.parameter.scope">Scope</a></code> | <code>Constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.Initializer.parameter.id">Id</a></code> | <code>string</code> | The scoped construct ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.Initializer.parameter.config">Config</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig">ApiIntegrationConfig</a></code> | *No description.* |

---

##### `Scope`<sup>Required</sup> <a name="Scope" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.Initializer.parameter.scope"></a>

- *Type:* Constructs.Construct

The scope in which to define this construct.

---

##### `Id`<sup>Required</sup> <a name="Id" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.Initializer.parameter.id"></a>

- *Type:* string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `Config`<sup>Required</sup> <a name="Config" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.Initializer.parameter.config"></a>

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig">ApiIntegrationConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.toString">ToString</a></code> | Returns a string representation of this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.addOverride">AddOverride</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.overrideLogicalId">OverrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.resetOverrideLogicalId">ResetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.toMetadata">ToMetadata</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.toTerraform">ToTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.putResponders">PutResponders</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.resetAllowWriteAccess">ResetAllowWriteAccess</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.resetEnabled">ResetEnabled</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.resetHeaders">ResetHeaders</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.resetId">ResetId</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.resetIgnoreRespondersFromPayload">ResetIgnoreRespondersFromPayload</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.resetOwnerTeamId">ResetOwnerTeamId</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.resetResponders">ResetResponders</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.resetSuppressNotifications">ResetSuppressNotifications</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.resetType">ResetType</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.resetWebhookUrl">ResetWebhookUrl</a></code> | *No description.* |

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.toString"></a>

```csharp
private string ToString()
```

Returns a string representation of this construct.

##### `AddOverride` <a name="AddOverride" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.addOverride"></a>

```csharp
private void AddOverride(string Path, object Value)
```

###### `Path`<sup>Required</sup> <a name="Path" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.addOverride.parameter.path"></a>

- *Type:* string

---

###### `Value`<sup>Required</sup> <a name="Value" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.addOverride.parameter.value"></a>

- *Type:* object

---

##### `OverrideLogicalId` <a name="OverrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.overrideLogicalId"></a>

```csharp
private void OverrideLogicalId(string NewLogicalId)
```

Overrides the auto-generated logical ID with a specific ID.

###### `NewLogicalId`<sup>Required</sup> <a name="NewLogicalId" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* string

The new logical ID to use for this stack element.

---

##### `ResetOverrideLogicalId` <a name="ResetOverrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.resetOverrideLogicalId"></a>

```csharp
private void ResetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `ToMetadata` <a name="ToMetadata" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.toMetadata"></a>

```csharp
private object ToMetadata()
```

##### `ToTerraform` <a name="ToTerraform" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.toTerraform"></a>

```csharp
private object ToTerraform()
```

Adds this resource to the terraform JSON output.

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `PutResponders` <a name="PutResponders" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.putResponders"></a>

```csharp
private void PutResponders(object Value)
```

###### `Value`<sup>Required</sup> <a name="Value" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.putResponders.parameter.value"></a>

- *Type:* object

---

##### `ResetAllowWriteAccess` <a name="ResetAllowWriteAccess" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.resetAllowWriteAccess"></a>

```csharp
private void ResetAllowWriteAccess()
```

##### `ResetEnabled` <a name="ResetEnabled" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.resetEnabled"></a>

```csharp
private void ResetEnabled()
```

##### `ResetHeaders` <a name="ResetHeaders" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.resetHeaders"></a>

```csharp
private void ResetHeaders()
```

##### `ResetId` <a name="ResetId" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.resetId"></a>

```csharp
private void ResetId()
```

##### `ResetIgnoreRespondersFromPayload` <a name="ResetIgnoreRespondersFromPayload" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.resetIgnoreRespondersFromPayload"></a>

```csharp
private void ResetIgnoreRespondersFromPayload()
```

##### `ResetOwnerTeamId` <a name="ResetOwnerTeamId" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.resetOwnerTeamId"></a>

```csharp
private void ResetOwnerTeamId()
```

##### `ResetResponders` <a name="ResetResponders" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.resetResponders"></a>

```csharp
private void ResetResponders()
```

##### `ResetSuppressNotifications` <a name="ResetSuppressNotifications" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.resetSuppressNotifications"></a>

```csharp
private void ResetSuppressNotifications()
```

##### `ResetType` <a name="ResetType" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.resetType"></a>

```csharp
private void ResetType()
```

##### `ResetWebhookUrl` <a name="ResetWebhookUrl" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.resetWebhookUrl"></a>

```csharp
private void ResetWebhookUrl()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.isConstruct">IsConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.isTerraformElement">IsTerraformElement</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.isTerraformResource">IsTerraformResource</a></code> | *No description.* |

---

##### `IsConstruct` <a name="IsConstruct" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.isConstruct"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

ApiIntegration.IsConstruct(object X);
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

###### `X`<sup>Required</sup> <a name="X" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.isConstruct.parameter.x"></a>

- *Type:* object

Any object.

---

##### `IsTerraformElement` <a name="IsTerraformElement" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.isTerraformElement"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

ApiIntegration.IsTerraformElement(object X);
```

###### `X`<sup>Required</sup> <a name="X" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.isTerraformElement.parameter.x"></a>

- *Type:* object

---

##### `IsTerraformResource` <a name="IsTerraformResource" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.isTerraformResource"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

ApiIntegration.IsTerraformResource(object X);
```

###### `X`<sup>Required</sup> <a name="X" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.isTerraformResource.parameter.x"></a>

- *Type:* object

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.node">Node</a></code> | <code>Constructs.Node</code> | The tree node. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.cdktfStack">CdktfStack</a></code> | <code>HashiCorp.Cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.friendlyUniqueId">FriendlyUniqueId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.terraformMetaArguments">TerraformMetaArguments</a></code> | <code>System.Collections.Generic.IDictionary<string, object></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.terraformResourceType">TerraformResourceType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.terraformGeneratorMetadata">TerraformGeneratorMetadata</a></code> | <code>HashiCorp.Cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.connection">Connection</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.count">Count</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.dependsOn">DependsOn</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.forEach">ForEach</a></code> | <code>HashiCorp.Cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.lifecycle">Lifecycle</a></code> | <code>HashiCorp.Cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.provider">Provider</a></code> | <code>HashiCorp.Cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.provisioners">Provisioners</a></code> | <code>object[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.apiKey">ApiKey</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.responders">Responders</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersList">ApiIntegrationRespondersList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.allowWriteAccessInput">AllowWriteAccessInput</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.enabledInput">EnabledInput</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.headersInput">HeadersInput</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.idInput">IdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.ignoreRespondersFromPayloadInput">IgnoreRespondersFromPayloadInput</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.nameInput">NameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.ownerTeamIdInput">OwnerTeamIdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.respondersInput">RespondersInput</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.suppressNotificationsInput">SuppressNotificationsInput</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.typeInput">TypeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.webhookUrlInput">WebhookUrlInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.allowWriteAccess">AllowWriteAccess</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.enabled">Enabled</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.headers">Headers</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.id">Id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.ignoreRespondersFromPayload">IgnoreRespondersFromPayload</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.name">Name</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.ownerTeamId">OwnerTeamId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.suppressNotifications">SuppressNotifications</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.type">Type</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.webhookUrl">WebhookUrl</a></code> | <code>string</code> | *No description.* |

---

##### `Node`<sup>Required</sup> <a name="Node" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.node"></a>

```csharp
public Node Node { get; }
```

- *Type:* Constructs.Node

The tree node.

---

##### `CdktfStack`<sup>Required</sup> <a name="CdktfStack" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.cdktfStack"></a>

```csharp
public TerraformStack CdktfStack { get; }
```

- *Type:* HashiCorp.Cdktf.TerraformStack

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `FriendlyUniqueId`<sup>Required</sup> <a name="FriendlyUniqueId" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.friendlyUniqueId"></a>

```csharp
public string FriendlyUniqueId { get; }
```

- *Type:* string

---

##### `TerraformMetaArguments`<sup>Required</sup> <a name="TerraformMetaArguments" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.terraformMetaArguments"></a>

```csharp
public System.Collections.Generic.IDictionary<string, object> TerraformMetaArguments { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, object>

---

##### `TerraformResourceType`<sup>Required</sup> <a name="TerraformResourceType" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.terraformResourceType"></a>

```csharp
public string TerraformResourceType { get; }
```

- *Type:* string

---

##### `TerraformGeneratorMetadata`<sup>Optional</sup> <a name="TerraformGeneratorMetadata" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.terraformGeneratorMetadata"></a>

```csharp
public TerraformProviderGeneratorMetadata TerraformGeneratorMetadata { get; }
```

- *Type:* HashiCorp.Cdktf.TerraformProviderGeneratorMetadata

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.connection"></a>

```csharp
public object Connection { get; }
```

- *Type:* object

---

##### `Count`<sup>Optional</sup> <a name="Count" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.count"></a>

```csharp
public object Count { get; }
```

- *Type:* object

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.dependsOn"></a>

```csharp
public string[] DependsOn { get; }
```

- *Type:* string[]

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.forEach"></a>

```csharp
public ITerraformIterator ForEach { get; }
```

- *Type:* HashiCorp.Cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.lifecycle"></a>

```csharp
public TerraformResourceLifecycle Lifecycle { get; }
```

- *Type:* HashiCorp.Cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.provider"></a>

```csharp
public TerraformProvider Provider { get; }
```

- *Type:* HashiCorp.Cdktf.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.provisioners"></a>

```csharp
public object[] Provisioners { get; }
```

- *Type:* object[]

---

##### `ApiKey`<sup>Required</sup> <a name="ApiKey" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.apiKey"></a>

```csharp
public string ApiKey { get; }
```

- *Type:* string

---

##### `Responders`<sup>Required</sup> <a name="Responders" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.responders"></a>

```csharp
public ApiIntegrationRespondersList Responders { get; }
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersList">ApiIntegrationRespondersList</a>

---

##### `AllowWriteAccessInput`<sup>Optional</sup> <a name="AllowWriteAccessInput" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.allowWriteAccessInput"></a>

```csharp
public object AllowWriteAccessInput { get; }
```

- *Type:* object

---

##### `EnabledInput`<sup>Optional</sup> <a name="EnabledInput" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.enabledInput"></a>

```csharp
public object EnabledInput { get; }
```

- *Type:* object

---

##### `HeadersInput`<sup>Optional</sup> <a name="HeadersInput" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.headersInput"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> HeadersInput { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

---

##### `IdInput`<sup>Optional</sup> <a name="IdInput" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.idInput"></a>

```csharp
public string IdInput { get; }
```

- *Type:* string

---

##### `IgnoreRespondersFromPayloadInput`<sup>Optional</sup> <a name="IgnoreRespondersFromPayloadInput" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.ignoreRespondersFromPayloadInput"></a>

```csharp
public object IgnoreRespondersFromPayloadInput { get; }
```

- *Type:* object

---

##### `NameInput`<sup>Optional</sup> <a name="NameInput" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.nameInput"></a>

```csharp
public string NameInput { get; }
```

- *Type:* string

---

##### `OwnerTeamIdInput`<sup>Optional</sup> <a name="OwnerTeamIdInput" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.ownerTeamIdInput"></a>

```csharp
public string OwnerTeamIdInput { get; }
```

- *Type:* string

---

##### `RespondersInput`<sup>Optional</sup> <a name="RespondersInput" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.respondersInput"></a>

```csharp
public object RespondersInput { get; }
```

- *Type:* object

---

##### `SuppressNotificationsInput`<sup>Optional</sup> <a name="SuppressNotificationsInput" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.suppressNotificationsInput"></a>

```csharp
public object SuppressNotificationsInput { get; }
```

- *Type:* object

---

##### `TypeInput`<sup>Optional</sup> <a name="TypeInput" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.typeInput"></a>

```csharp
public string TypeInput { get; }
```

- *Type:* string

---

##### `WebhookUrlInput`<sup>Optional</sup> <a name="WebhookUrlInput" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.webhookUrlInput"></a>

```csharp
public string WebhookUrlInput { get; }
```

- *Type:* string

---

##### `AllowWriteAccess`<sup>Required</sup> <a name="AllowWriteAccess" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.allowWriteAccess"></a>

```csharp
public object AllowWriteAccess { get; }
```

- *Type:* object

---

##### `Enabled`<sup>Required</sup> <a name="Enabled" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.enabled"></a>

```csharp
public object Enabled { get; }
```

- *Type:* object

---

##### `Headers`<sup>Required</sup> <a name="Headers" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.headers"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> Headers { get; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

---

##### `Id`<sup>Required</sup> <a name="Id" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.id"></a>

```csharp
public string Id { get; }
```

- *Type:* string

---

##### `IgnoreRespondersFromPayload`<sup>Required</sup> <a name="IgnoreRespondersFromPayload" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.ignoreRespondersFromPayload"></a>

```csharp
public object IgnoreRespondersFromPayload { get; }
```

- *Type:* object

---

##### `Name`<sup>Required</sup> <a name="Name" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.name"></a>

```csharp
public string Name { get; }
```

- *Type:* string

---

##### `OwnerTeamId`<sup>Required</sup> <a name="OwnerTeamId" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.ownerTeamId"></a>

```csharp
public string OwnerTeamId { get; }
```

- *Type:* string

---

##### `SuppressNotifications`<sup>Required</sup> <a name="SuppressNotifications" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.suppressNotifications"></a>

```csharp
public object SuppressNotifications { get; }
```

- *Type:* object

---

##### `Type`<sup>Required</sup> <a name="Type" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.type"></a>

```csharp
public string Type { get; }
```

- *Type:* string

---

##### `WebhookUrl`<sup>Required</sup> <a name="WebhookUrl" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.webhookUrl"></a>

```csharp
public string WebhookUrl { get; }
```

- *Type:* string

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.tfResourceType">TfResourceType</a></code> | <code>string</code> | *No description.* |

---

##### `TfResourceType`<sup>Required</sup> <a name="TfResourceType" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegration.property.tfResourceType"></a>

```csharp
public string TfResourceType { get; }
```

- *Type:* string

---

## Structs <a name="Structs" id="Structs"></a>

### ApiIntegrationConfig <a name="ApiIntegrationConfig" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new ApiIntegrationConfig {
    object Connection = null,
    object Count = null,
    ITerraformDependable[] DependsOn = null,
    ITerraformIterator ForEach = null,
    TerraformResourceLifecycle Lifecycle = null,
    TerraformProvider Provider = null,
    object[] Provisioners = null,
    string Name,
    object AllowWriteAccess = null,
    object Enabled = null,
    System.Collections.Generic.IDictionary<string, string> Headers = null,
    string Id = null,
    object IgnoreRespondersFromPayload = null,
    string OwnerTeamId = null,
    object Responders = null,
    object SuppressNotifications = null,
    string Type = null,
    string WebhookUrl = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig.property.connection">Connection</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig.property.count">Count</a></code> | <code>object</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig.property.dependsOn">DependsOn</a></code> | <code>HashiCorp.Cdktf.ITerraformDependable[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig.property.forEach">ForEach</a></code> | <code>HashiCorp.Cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig.property.lifecycle">Lifecycle</a></code> | <code>HashiCorp.Cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig.property.provider">Provider</a></code> | <code>HashiCorp.Cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig.property.provisioners">Provisioners</a></code> | <code>object[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig.property.name">Name</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/api_integration#name ApiIntegration#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig.property.allowWriteAccess">AllowWriteAccess</a></code> | <code>object</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/api_integration#allow_write_access ApiIntegration#allow_write_access}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig.property.enabled">Enabled</a></code> | <code>object</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/api_integration#enabled ApiIntegration#enabled}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig.property.headers">Headers</a></code> | <code>System.Collections.Generic.IDictionary<string, string></code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/api_integration#headers ApiIntegration#headers}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig.property.id">Id</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/api_integration#id ApiIntegration#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig.property.ignoreRespondersFromPayload">IgnoreRespondersFromPayload</a></code> | <code>object</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/api_integration#ignore_responders_from_payload ApiIntegration#ignore_responders_from_payload}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig.property.ownerTeamId">OwnerTeamId</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/api_integration#owner_team_id ApiIntegration#owner_team_id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig.property.responders">Responders</a></code> | <code>object</code> | responders block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig.property.suppressNotifications">SuppressNotifications</a></code> | <code>object</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/api_integration#suppress_notifications ApiIntegration#suppress_notifications}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig.property.type">Type</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/api_integration#type ApiIntegration#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig.property.webhookUrl">WebhookUrl</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/api_integration#webhook_url ApiIntegration#webhook_url}. |

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig.property.connection"></a>

```csharp
public object Connection { get; set; }
```

- *Type:* object

---

##### `Count`<sup>Optional</sup> <a name="Count" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig.property.count"></a>

```csharp
public object Count { get; set; }
```

- *Type:* object

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig.property.dependsOn"></a>

```csharp
public ITerraformDependable[] DependsOn { get; set; }
```

- *Type:* HashiCorp.Cdktf.ITerraformDependable[]

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig.property.forEach"></a>

```csharp
public ITerraformIterator ForEach { get; set; }
```

- *Type:* HashiCorp.Cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig.property.lifecycle"></a>

```csharp
public TerraformResourceLifecycle Lifecycle { get; set; }
```

- *Type:* HashiCorp.Cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig.property.provider"></a>

```csharp
public TerraformProvider Provider { get; set; }
```

- *Type:* HashiCorp.Cdktf.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig.property.provisioners"></a>

```csharp
public object[] Provisioners { get; set; }
```

- *Type:* object[]

---

##### `Name`<sup>Required</sup> <a name="Name" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig.property.name"></a>

```csharp
public string Name { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/api_integration#name ApiIntegration#name}.

---

##### `AllowWriteAccess`<sup>Optional</sup> <a name="AllowWriteAccess" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig.property.allowWriteAccess"></a>

```csharp
public object AllowWriteAccess { get; set; }
```

- *Type:* object

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/api_integration#allow_write_access ApiIntegration#allow_write_access}.

---

##### `Enabled`<sup>Optional</sup> <a name="Enabled" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig.property.enabled"></a>

```csharp
public object Enabled { get; set; }
```

- *Type:* object

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/api_integration#enabled ApiIntegration#enabled}.

---

##### `Headers`<sup>Optional</sup> <a name="Headers" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig.property.headers"></a>

```csharp
public System.Collections.Generic.IDictionary<string, string> Headers { get; set; }
```

- *Type:* System.Collections.Generic.IDictionary<string, string>

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/api_integration#headers ApiIntegration#headers}.

---

##### `Id`<sup>Optional</sup> <a name="Id" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig.property.id"></a>

```csharp
public string Id { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/api_integration#id ApiIntegration#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `IgnoreRespondersFromPayload`<sup>Optional</sup> <a name="IgnoreRespondersFromPayload" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig.property.ignoreRespondersFromPayload"></a>

```csharp
public object IgnoreRespondersFromPayload { get; set; }
```

- *Type:* object

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/api_integration#ignore_responders_from_payload ApiIntegration#ignore_responders_from_payload}.

---

##### `OwnerTeamId`<sup>Optional</sup> <a name="OwnerTeamId" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig.property.ownerTeamId"></a>

```csharp
public string OwnerTeamId { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/api_integration#owner_team_id ApiIntegration#owner_team_id}.

---

##### `Responders`<sup>Optional</sup> <a name="Responders" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig.property.responders"></a>

```csharp
public object Responders { get; set; }
```

- *Type:* object

responders block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/api_integration#responders ApiIntegration#responders}

---

##### `SuppressNotifications`<sup>Optional</sup> <a name="SuppressNotifications" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig.property.suppressNotifications"></a>

```csharp
public object SuppressNotifications { get; set; }
```

- *Type:* object

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/api_integration#suppress_notifications ApiIntegration#suppress_notifications}.

---

##### `Type`<sup>Optional</sup> <a name="Type" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig.property.type"></a>

```csharp
public string Type { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/api_integration#type ApiIntegration#type}.

---

##### `WebhookUrl`<sup>Optional</sup> <a name="WebhookUrl" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationConfig.property.webhookUrl"></a>

```csharp
public string WebhookUrl { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/api_integration#webhook_url ApiIntegration#webhook_url}.

---

### ApiIntegrationResponders <a name="ApiIntegrationResponders" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationResponders"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationResponders.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new ApiIntegrationResponders {
    string Id = null,
    string Type = null
};
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationResponders.property.id">Id</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/api_integration#id ApiIntegration#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationResponders.property.type">Type</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/api_integration#type ApiIntegration#type}. |

---

##### `Id`<sup>Optional</sup> <a name="Id" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationResponders.property.id"></a>

```csharp
public string Id { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/api_integration#id ApiIntegration#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `Type`<sup>Optional</sup> <a name="Type" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationResponders.property.type"></a>

```csharp
public string Type { get; set; }
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/api_integration#type ApiIntegration#type}.

---

## Classes <a name="Classes" id="Classes"></a>

### ApiIntegrationRespondersList <a name="ApiIntegrationRespondersList" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersList.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new ApiIntegrationRespondersList(IInterpolatingParent TerraformResource, string TerraformAttribute, bool WrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersList.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>HashiCorp.Cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersList.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersList.Initializer.parameter.wrapsSet">WrapsSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersList.Initializer.parameter.terraformResource"></a>

- *Type:* HashiCorp.Cdktf.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `WrapsSet`<sup>Required</sup> <a name="WrapsSet" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersList.Initializer.parameter.wrapsSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersList.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersList.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersList.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersList.get">Get</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersList.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersList.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersList.resolve.parameter._context"></a>

- *Type:* HashiCorp.Cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersList.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `Get` <a name="Get" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersList.get"></a>

```csharp
private ApiIntegrationRespondersOutputReference Get(double Index)
```

###### `Index`<sup>Required</sup> <a name="Index" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersList.get.parameter.index"></a>

- *Type:* double

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersList.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersList.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersList.property.internalValue">InternalValue</a></code> | <code>object</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersList.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersList.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersList.property.internalValue"></a>

```csharp
public object InternalValue { get; }
```

- *Type:* object

---


### ApiIntegrationRespondersOutputReference <a name="ApiIntegrationRespondersOutputReference" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.Initializer"></a>

```csharp
using HashiCorp.Cdktf.Providers.Opsgenie;

new ApiIntegrationRespondersOutputReference(IInterpolatingParent TerraformResource, string TerraformAttribute, double ComplexObjectIndex, bool ComplexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.Initializer.parameter.terraformResource">TerraformResource</a></code> | <code>HashiCorp.Cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.Initializer.parameter.terraformAttribute">TerraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.Initializer.parameter.complexObjectIndex">ComplexObjectIndex</a></code> | <code>double</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.Initializer.parameter.complexObjectIsFromSet">ComplexObjectIsFromSet</a></code> | <code>bool</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `TerraformResource`<sup>Required</sup> <a name="TerraformResource" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* HashiCorp.Cdktf.IInterpolatingParent

The parent resource.

---

##### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `ComplexObjectIndex`<sup>Required</sup> <a name="ComplexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* double

the index of this item in the list.

---

##### `ComplexObjectIsFromSet`<sup>Required</sup> <a name="ComplexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* bool

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.computeFqn">ComputeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.resolve">Resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.toString">ToString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.resetId">ResetId</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.resetType">ResetType</a></code> | *No description.* |

---

##### `ComputeFqn` <a name="ComputeFqn" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.computeFqn"></a>

```csharp
private string ComputeFqn()
```

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.getAnyMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, object> GetAnyMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.getBooleanAttribute"></a>

```csharp
private IResolvable GetBooleanAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.getBooleanMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, bool> GetBooleanMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.getListAttribute"></a>

```csharp
private string[] GetListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.getNumberAttribute"></a>

```csharp
private double GetNumberAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.getNumberListAttribute"></a>

```csharp
private double[] GetNumberListAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.getNumberMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, double> GetNumberMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.getStringAttribute"></a>

```csharp
private string GetStringAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.getStringMapAttribute"></a>

```csharp
private System.Collections.Generic.IDictionary<string, string> GetStringMapAttribute(string TerraformAttribute)
```

###### `TerraformAttribute`<sup>Required</sup> <a name="TerraformAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.interpolationForAttribute"></a>

```csharp
private IResolvable InterpolationForAttribute(string Property)
```

###### `Property`<sup>Required</sup> <a name="Property" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `Resolve` <a name="Resolve" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.resolve"></a>

```csharp
private object Resolve(IResolveContext Context)
```

Produce the Token's value at resolution time.

###### `Context`<sup>Required</sup> <a name="Context" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.resolve.parameter._context"></a>

- *Type:* HashiCorp.Cdktf.IResolveContext

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.toString"></a>

```csharp
private string ToString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `ResetId` <a name="ResetId" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.resetId"></a>

```csharp
private void ResetId()
```

##### `ResetType` <a name="ResetType" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.resetType"></a>

```csharp
private void ResetType()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.property.creationStack">CreationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.property.fqn">Fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.property.idInput">IdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.property.typeInput">TypeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.property.id">Id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.property.type">Type</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.property.internalValue">InternalValue</a></code> | <code>object</code> | *No description.* |

---

##### `CreationStack`<sup>Required</sup> <a name="CreationStack" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.property.creationStack"></a>

```csharp
public string[] CreationStack { get; }
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.property.fqn"></a>

```csharp
public string Fqn { get; }
```

- *Type:* string

---

##### `IdInput`<sup>Optional</sup> <a name="IdInput" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.property.idInput"></a>

```csharp
public string IdInput { get; }
```

- *Type:* string

---

##### `TypeInput`<sup>Optional</sup> <a name="TypeInput" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.property.typeInput"></a>

```csharp
public string TypeInput { get; }
```

- *Type:* string

---

##### `Id`<sup>Required</sup> <a name="Id" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.property.id"></a>

```csharp
public string Id { get; }
```

- *Type:* string

---

##### `Type`<sup>Required</sup> <a name="Type" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.property.type"></a>

```csharp
public string Type { get; }
```

- *Type:* string

---

##### `InternalValue`<sup>Optional</sup> <a name="InternalValue" id="rhizo-co-terraform-provider-opsgenie.apiIntegration.ApiIntegrationRespondersOutputReference.property.internalValue"></a>

```csharp
public object InternalValue { get; }
```

- *Type:* object

---



