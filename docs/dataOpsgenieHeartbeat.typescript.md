# `data_opsgenie_heartbeat`

Refer to the Terraform Registory for docs: [`data_opsgenie_heartbeat`](https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat).

# `dataOpsgenieHeartbeat` Submodule <a name="`dataOpsgenieHeartbeat` Submodule" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### DataOpsgenieHeartbeat <a name="DataOpsgenieHeartbeat" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat"></a>

Represents a {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat opsgenie_heartbeat}.

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer"></a>

```typescript
import { dataOpsgenieHeartbeat } from 'rhizo-co-terraform-provider-opsgenie'

new dataOpsgenieHeartbeat.DataOpsgenieHeartbeat(scope: Construct, id: string, config: DataOpsgenieHeartbeatConfig)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.id">id</a></code> | <code>string</code> | The scoped construct ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.config">config</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig">DataOpsgenieHeartbeatConfig</a></code> | *No description.* |

---

##### `scope`<sup>Required</sup> <a name="scope" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.id"></a>

- *Type:* string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Required</sup> <a name="config" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.config"></a>

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig">DataOpsgenieHeartbeatConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.toString">toString</a></code> | Returns a string representation of this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.addOverride">addOverride</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.overrideLogicalId">overrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetOverrideLogicalId">resetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.toMetadata">toMetadata</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.toTerraform">toTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetAlertMessage">resetAlertMessage</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetAlertPriority">resetAlertPriority</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetAlertTags">resetAlertTags</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetDescription">resetDescription</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetEnabled">resetEnabled</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetId">resetId</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetInterval">resetInterval</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetIntervalUnit">resetIntervalUnit</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetOwnerTeamId">resetOwnerTeamId</a></code> | *No description.* |

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.toString"></a>

```typescript
public toString(): string
```

Returns a string representation of this construct.

##### `addOverride` <a name="addOverride" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.addOverride"></a>

```typescript
public addOverride(path: string, value: any): void
```

###### `path`<sup>Required</sup> <a name="path" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.addOverride.parameter.path"></a>

- *Type:* string

---

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.addOverride.parameter.value"></a>

- *Type:* any

---

##### `overrideLogicalId` <a name="overrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.overrideLogicalId"></a>

```typescript
public overrideLogicalId(newLogicalId: string): void
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* string

The new logical ID to use for this stack element.

---

##### `resetOverrideLogicalId` <a name="resetOverrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetOverrideLogicalId"></a>

```typescript
public resetOverrideLogicalId(): void
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `toMetadata` <a name="toMetadata" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.toMetadata"></a>

```typescript
public toMetadata(): any
```

##### `toTerraform` <a name="toTerraform" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.toTerraform"></a>

```typescript
public toTerraform(): any
```

Adds this resource to the terraform JSON output.

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `resetAlertMessage` <a name="resetAlertMessage" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetAlertMessage"></a>

```typescript
public resetAlertMessage(): void
```

##### `resetAlertPriority` <a name="resetAlertPriority" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetAlertPriority"></a>

```typescript
public resetAlertPriority(): void
```

##### `resetAlertTags` <a name="resetAlertTags" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetAlertTags"></a>

```typescript
public resetAlertTags(): void
```

##### `resetDescription` <a name="resetDescription" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetDescription"></a>

```typescript
public resetDescription(): void
```

##### `resetEnabled` <a name="resetEnabled" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetEnabled"></a>

```typescript
public resetEnabled(): void
```

##### `resetId` <a name="resetId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetId"></a>

```typescript
public resetId(): void
```

##### `resetInterval` <a name="resetInterval" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetInterval"></a>

```typescript
public resetInterval(): void
```

##### `resetIntervalUnit` <a name="resetIntervalUnit" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetIntervalUnit"></a>

```typescript
public resetIntervalUnit(): void
```

##### `resetOwnerTeamId` <a name="resetOwnerTeamId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetOwnerTeamId"></a>

```typescript
public resetOwnerTeamId(): void
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isConstruct">isConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isTerraformElement">isTerraformElement</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isTerraformDataSource">isTerraformDataSource</a></code> | *No description.* |

---

##### `isConstruct` <a name="isConstruct" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isConstruct"></a>

```typescript
import { dataOpsgenieHeartbeat } from 'rhizo-co-terraform-provider-opsgenie'

dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isConstruct(x: any)
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

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isConstruct.parameter.x"></a>

- *Type:* any

Any object.

---

##### `isTerraformElement` <a name="isTerraformElement" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isTerraformElement"></a>

```typescript
import { dataOpsgenieHeartbeat } from 'rhizo-co-terraform-provider-opsgenie'

dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isTerraformElement(x: any)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isTerraformElement.parameter.x"></a>

- *Type:* any

---

##### `isTerraformDataSource` <a name="isTerraformDataSource" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isTerraformDataSource"></a>

```typescript
import { dataOpsgenieHeartbeat } from 'rhizo-co-terraform-provider-opsgenie'

dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isTerraformDataSource(x: any)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isTerraformDataSource.parameter.x"></a>

- *Type:* any

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.node">node</a></code> | <code>constructs.Node</code> | The tree node. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.cdktfStack">cdktfStack</a></code> | <code>cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.friendlyUniqueId">friendlyUniqueId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.terraformMetaArguments">terraformMetaArguments</a></code> | <code>{[ key: string ]: any}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.terraformResourceType">terraformResourceType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.terraformGeneratorMetadata">terraformGeneratorMetadata</a></code> | <code>cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.count">count</a></code> | <code>number \| cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.dependsOn">dependsOn</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.forEach">forEach</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertMessageInput">alertMessageInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertPriorityInput">alertPriorityInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertTagsInput">alertTagsInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.descriptionInput">descriptionInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.enabledInput">enabledInput</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.idInput">idInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.intervalInput">intervalInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.intervalUnitInput">intervalUnitInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.nameInput">nameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.ownerTeamIdInput">ownerTeamIdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertMessage">alertMessage</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertPriority">alertPriority</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertTags">alertTags</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.description">description</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.enabled">enabled</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.id">id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.interval">interval</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.intervalUnit">intervalUnit</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.name">name</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.ownerTeamId">ownerTeamId</a></code> | <code>string</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.node"></a>

```typescript
public readonly node: Node;
```

- *Type:* constructs.Node

The tree node.

---

##### `cdktfStack`<sup>Required</sup> <a name="cdktfStack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.cdktfStack"></a>

```typescript
public readonly cdktfStack: TerraformStack;
```

- *Type:* cdktf.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `friendlyUniqueId`<sup>Required</sup> <a name="friendlyUniqueId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.friendlyUniqueId"></a>

```typescript
public readonly friendlyUniqueId: string;
```

- *Type:* string

---

##### `terraformMetaArguments`<sup>Required</sup> <a name="terraformMetaArguments" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.terraformMetaArguments"></a>

```typescript
public readonly terraformMetaArguments: {[ key: string ]: any};
```

- *Type:* {[ key: string ]: any}

---

##### `terraformResourceType`<sup>Required</sup> <a name="terraformResourceType" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.terraformResourceType"></a>

```typescript
public readonly terraformResourceType: string;
```

- *Type:* string

---

##### `terraformGeneratorMetadata`<sup>Optional</sup> <a name="terraformGeneratorMetadata" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.terraformGeneratorMetadata"></a>

```typescript
public readonly terraformGeneratorMetadata: TerraformProviderGeneratorMetadata;
```

- *Type:* cdktf.TerraformProviderGeneratorMetadata

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.count"></a>

```typescript
public readonly count: number | TerraformCount;
```

- *Type:* number | cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.dependsOn"></a>

```typescript
public readonly dependsOn: string[];
```

- *Type:* string[]

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.forEach"></a>

```typescript
public readonly forEach: ITerraformIterator;
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* cdktf.TerraformProvider

---

##### `alertMessageInput`<sup>Optional</sup> <a name="alertMessageInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertMessageInput"></a>

```typescript
public readonly alertMessageInput: string;
```

- *Type:* string

---

##### `alertPriorityInput`<sup>Optional</sup> <a name="alertPriorityInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertPriorityInput"></a>

```typescript
public readonly alertPriorityInput: string;
```

- *Type:* string

---

##### `alertTagsInput`<sup>Optional</sup> <a name="alertTagsInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertTagsInput"></a>

```typescript
public readonly alertTagsInput: string[];
```

- *Type:* string[]

---

##### `descriptionInput`<sup>Optional</sup> <a name="descriptionInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.descriptionInput"></a>

```typescript
public readonly descriptionInput: string;
```

- *Type:* string

---

##### `enabledInput`<sup>Optional</sup> <a name="enabledInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.enabledInput"></a>

```typescript
public readonly enabledInput: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `idInput`<sup>Optional</sup> <a name="idInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.idInput"></a>

```typescript
public readonly idInput: string;
```

- *Type:* string

---

##### `intervalInput`<sup>Optional</sup> <a name="intervalInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.intervalInput"></a>

```typescript
public readonly intervalInput: number;
```

- *Type:* number

---

##### `intervalUnitInput`<sup>Optional</sup> <a name="intervalUnitInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.intervalUnitInput"></a>

```typescript
public readonly intervalUnitInput: string;
```

- *Type:* string

---

##### `nameInput`<sup>Optional</sup> <a name="nameInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.nameInput"></a>

```typescript
public readonly nameInput: string;
```

- *Type:* string

---

##### `ownerTeamIdInput`<sup>Optional</sup> <a name="ownerTeamIdInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.ownerTeamIdInput"></a>

```typescript
public readonly ownerTeamIdInput: string;
```

- *Type:* string

---

##### `alertMessage`<sup>Required</sup> <a name="alertMessage" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertMessage"></a>

```typescript
public readonly alertMessage: string;
```

- *Type:* string

---

##### `alertPriority`<sup>Required</sup> <a name="alertPriority" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertPriority"></a>

```typescript
public readonly alertPriority: string;
```

- *Type:* string

---

##### `alertTags`<sup>Required</sup> <a name="alertTags" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertTags"></a>

```typescript
public readonly alertTags: string[];
```

- *Type:* string[]

---

##### `description`<sup>Required</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.description"></a>

```typescript
public readonly description: string;
```

- *Type:* string

---

##### `enabled`<sup>Required</sup> <a name="enabled" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.enabled"></a>

```typescript
public readonly enabled: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

---

##### `interval`<sup>Required</sup> <a name="interval" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.interval"></a>

```typescript
public readonly interval: number;
```

- *Type:* number

---

##### `intervalUnit`<sup>Required</sup> <a name="intervalUnit" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.intervalUnit"></a>

```typescript
public readonly intervalUnit: string;
```

- *Type:* string

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.name"></a>

```typescript
public readonly name: string;
```

- *Type:* string

---

##### `ownerTeamId`<sup>Required</sup> <a name="ownerTeamId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.ownerTeamId"></a>

```typescript
public readonly ownerTeamId: string;
```

- *Type:* string

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.tfResourceType">tfResourceType</a></code> | <code>string</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.tfResourceType"></a>

```typescript
public readonly tfResourceType: string;
```

- *Type:* string

---

## Structs <a name="Structs" id="Structs"></a>

### DataOpsgenieHeartbeatConfig <a name="DataOpsgenieHeartbeatConfig" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.Initializer"></a>

```typescript
import { dataOpsgenieHeartbeat } from 'rhizo-co-terraform-provider-opsgenie'

const dataOpsgenieHeartbeatConfig: dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.connection">connection</a></code> | <code>cdktf.SSHProvisionerConnection \| cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.count">count</a></code> | <code>number \| cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.dependsOn">dependsOn</a></code> | <code>cdktf.ITerraformDependable[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.forEach">forEach</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.provisioners">provisioners</a></code> | <code>cdktf.FileProvisioner \| cdktf.LocalExecProvisioner \| cdktf.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.name">name</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#name DataOpsgenieHeartbeat#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.alertMessage">alertMessage</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_message DataOpsgenieHeartbeat#alert_message}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.alertPriority">alertPriority</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_priority DataOpsgenieHeartbeat#alert_priority}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.alertTags">alertTags</a></code> | <code>string[]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_tags DataOpsgenieHeartbeat#alert_tags}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.description">description</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#description DataOpsgenieHeartbeat#description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.enabled">enabled</a></code> | <code>boolean \| cdktf.IResolvable</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#enabled DataOpsgenieHeartbeat#enabled}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.id">id</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#id DataOpsgenieHeartbeat#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.interval">interval</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#interval DataOpsgenieHeartbeat#interval}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.intervalUnit">intervalUnit</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#interval_unit DataOpsgenieHeartbeat#interval_unit}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.ownerTeamId">ownerTeamId</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#owner_team_id DataOpsgenieHeartbeat#owner_team_id}. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.connection"></a>

```typescript
public readonly connection: SSHProvisionerConnection | WinrmProvisionerConnection;
```

- *Type:* cdktf.SSHProvisionerConnection | cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.count"></a>

```typescript
public readonly count: number | TerraformCount;
```

- *Type:* number | cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.dependsOn"></a>

```typescript
public readonly dependsOn: ITerraformDependable[];
```

- *Type:* cdktf.ITerraformDependable[]

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.forEach"></a>

```typescript
public readonly forEach: ITerraformIterator;
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.provisioners"></a>

```typescript
public readonly provisioners: FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner[];
```

- *Type:* cdktf.FileProvisioner | cdktf.LocalExecProvisioner | cdktf.RemoteExecProvisioner[]

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.name"></a>

```typescript
public readonly name: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#name DataOpsgenieHeartbeat#name}.

---

##### `alertMessage`<sup>Optional</sup> <a name="alertMessage" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.alertMessage"></a>

```typescript
public readonly alertMessage: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_message DataOpsgenieHeartbeat#alert_message}.

---

##### `alertPriority`<sup>Optional</sup> <a name="alertPriority" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.alertPriority"></a>

```typescript
public readonly alertPriority: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_priority DataOpsgenieHeartbeat#alert_priority}.

---

##### `alertTags`<sup>Optional</sup> <a name="alertTags" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.alertTags"></a>

```typescript
public readonly alertTags: string[];
```

- *Type:* string[]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_tags DataOpsgenieHeartbeat#alert_tags}.

---

##### `description`<sup>Optional</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.description"></a>

```typescript
public readonly description: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#description DataOpsgenieHeartbeat#description}.

---

##### `enabled`<sup>Optional</sup> <a name="enabled" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.enabled"></a>

```typescript
public readonly enabled: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#enabled DataOpsgenieHeartbeat#enabled}.

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#id DataOpsgenieHeartbeat#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `interval`<sup>Optional</sup> <a name="interval" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.interval"></a>

```typescript
public readonly interval: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#interval DataOpsgenieHeartbeat#interval}.

---

##### `intervalUnit`<sup>Optional</sup> <a name="intervalUnit" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.intervalUnit"></a>

```typescript
public readonly intervalUnit: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#interval_unit DataOpsgenieHeartbeat#interval_unit}.

---

##### `ownerTeamId`<sup>Optional</sup> <a name="ownerTeamId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.ownerTeamId"></a>

```typescript
public readonly ownerTeamId: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#owner_team_id DataOpsgenieHeartbeat#owner_team_id}.

---



