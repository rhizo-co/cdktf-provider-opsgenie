# `opsgenie_heartbeat`

Refer to the Terraform Registory for docs: [`opsgenie_heartbeat`](https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/heartbeat).

# `heartbeat` Submodule <a name="`heartbeat` Submodule" id="rhizo-co-terraform-provider-opsgenie.heartbeat"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### Heartbeat <a name="Heartbeat" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat"></a>

Represents a {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/heartbeat opsgenie_heartbeat}.

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.Initializer"></a>

```typescript
import { heartbeat } from 'rhizo-co-terraform-provider-opsgenie'

new heartbeat.Heartbeat(scope: Construct, id: string, config: HeartbeatConfig)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.Initializer.parameter.id">id</a></code> | <code>string</code> | The scoped construct ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.Initializer.parameter.config">config</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.HeartbeatConfig">HeartbeatConfig</a></code> | *No description.* |

---

##### `scope`<sup>Required</sup> <a name="scope" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.Initializer.parameter.id"></a>

- *Type:* string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Required</sup> <a name="config" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.Initializer.parameter.config"></a>

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.HeartbeatConfig">HeartbeatConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.toString">toString</a></code> | Returns a string representation of this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.addOverride">addOverride</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.overrideLogicalId">overrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.resetOverrideLogicalId">resetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.toMetadata">toMetadata</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.toTerraform">toTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.resetAlertMessage">resetAlertMessage</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.resetAlertPriority">resetAlertPriority</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.resetAlertTags">resetAlertTags</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.resetDescription">resetDescription</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.resetId">resetId</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.resetOwnerTeamId">resetOwnerTeamId</a></code> | *No description.* |

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.toString"></a>

```typescript
public toString(): string
```

Returns a string representation of this construct.

##### `addOverride` <a name="addOverride" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.addOverride"></a>

```typescript
public addOverride(path: string, value: any): void
```

###### `path`<sup>Required</sup> <a name="path" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.addOverride.parameter.path"></a>

- *Type:* string

---

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.addOverride.parameter.value"></a>

- *Type:* any

---

##### `overrideLogicalId` <a name="overrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.overrideLogicalId"></a>

```typescript
public overrideLogicalId(newLogicalId: string): void
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* string

The new logical ID to use for this stack element.

---

##### `resetOverrideLogicalId` <a name="resetOverrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.resetOverrideLogicalId"></a>

```typescript
public resetOverrideLogicalId(): void
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `toMetadata` <a name="toMetadata" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.toMetadata"></a>

```typescript
public toMetadata(): any
```

##### `toTerraform` <a name="toTerraform" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.toTerraform"></a>

```typescript
public toTerraform(): any
```

Adds this resource to the terraform JSON output.

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `resetAlertMessage` <a name="resetAlertMessage" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.resetAlertMessage"></a>

```typescript
public resetAlertMessage(): void
```

##### `resetAlertPriority` <a name="resetAlertPriority" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.resetAlertPriority"></a>

```typescript
public resetAlertPriority(): void
```

##### `resetAlertTags` <a name="resetAlertTags" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.resetAlertTags"></a>

```typescript
public resetAlertTags(): void
```

##### `resetDescription` <a name="resetDescription" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.resetDescription"></a>

```typescript
public resetDescription(): void
```

##### `resetId` <a name="resetId" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.resetId"></a>

```typescript
public resetId(): void
```

##### `resetOwnerTeamId` <a name="resetOwnerTeamId" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.resetOwnerTeamId"></a>

```typescript
public resetOwnerTeamId(): void
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.isConstruct">isConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.isTerraformElement">isTerraformElement</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.isTerraformResource">isTerraformResource</a></code> | *No description.* |

---

##### `isConstruct` <a name="isConstruct" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.isConstruct"></a>

```typescript
import { heartbeat } from 'rhizo-co-terraform-provider-opsgenie'

heartbeat.Heartbeat.isConstruct(x: any)
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

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.isConstruct.parameter.x"></a>

- *Type:* any

Any object.

---

##### `isTerraformElement` <a name="isTerraformElement" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.isTerraformElement"></a>

```typescript
import { heartbeat } from 'rhizo-co-terraform-provider-opsgenie'

heartbeat.Heartbeat.isTerraformElement(x: any)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.isTerraformElement.parameter.x"></a>

- *Type:* any

---

##### `isTerraformResource` <a name="isTerraformResource" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.isTerraformResource"></a>

```typescript
import { heartbeat } from 'rhizo-co-terraform-provider-opsgenie'

heartbeat.Heartbeat.isTerraformResource(x: any)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.isTerraformResource.parameter.x"></a>

- *Type:* any

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.node">node</a></code> | <code>constructs.Node</code> | The tree node. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.cdktfStack">cdktfStack</a></code> | <code>cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.friendlyUniqueId">friendlyUniqueId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.terraformMetaArguments">terraformMetaArguments</a></code> | <code>{[ key: string ]: any}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.terraformResourceType">terraformResourceType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.terraformGeneratorMetadata">terraformGeneratorMetadata</a></code> | <code>cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.connection">connection</a></code> | <code>cdktf.SSHProvisionerConnection \| cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.count">count</a></code> | <code>number \| cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.dependsOn">dependsOn</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.forEach">forEach</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.provisioners">provisioners</a></code> | <code>cdktf.FileProvisioner \| cdktf.LocalExecProvisioner \| cdktf.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.alertMessageInput">alertMessageInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.alertPriorityInput">alertPriorityInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.alertTagsInput">alertTagsInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.descriptionInput">descriptionInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.enabledInput">enabledInput</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.idInput">idInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.intervalInput">intervalInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.intervalUnitInput">intervalUnitInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.nameInput">nameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.ownerTeamIdInput">ownerTeamIdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.alertMessage">alertMessage</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.alertPriority">alertPriority</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.alertTags">alertTags</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.description">description</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.enabled">enabled</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.id">id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.interval">interval</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.intervalUnit">intervalUnit</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.name">name</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.ownerTeamId">ownerTeamId</a></code> | <code>string</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.node"></a>

```typescript
public readonly node: Node;
```

- *Type:* constructs.Node

The tree node.

---

##### `cdktfStack`<sup>Required</sup> <a name="cdktfStack" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.cdktfStack"></a>

```typescript
public readonly cdktfStack: TerraformStack;
```

- *Type:* cdktf.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `friendlyUniqueId`<sup>Required</sup> <a name="friendlyUniqueId" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.friendlyUniqueId"></a>

```typescript
public readonly friendlyUniqueId: string;
```

- *Type:* string

---

##### `terraformMetaArguments`<sup>Required</sup> <a name="terraformMetaArguments" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.terraformMetaArguments"></a>

```typescript
public readonly terraformMetaArguments: {[ key: string ]: any};
```

- *Type:* {[ key: string ]: any}

---

##### `terraformResourceType`<sup>Required</sup> <a name="terraformResourceType" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.terraformResourceType"></a>

```typescript
public readonly terraformResourceType: string;
```

- *Type:* string

---

##### `terraformGeneratorMetadata`<sup>Optional</sup> <a name="terraformGeneratorMetadata" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.terraformGeneratorMetadata"></a>

```typescript
public readonly terraformGeneratorMetadata: TerraformProviderGeneratorMetadata;
```

- *Type:* cdktf.TerraformProviderGeneratorMetadata

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.connection"></a>

```typescript
public readonly connection: SSHProvisionerConnection | WinrmProvisionerConnection;
```

- *Type:* cdktf.SSHProvisionerConnection | cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.count"></a>

```typescript
public readonly count: number | TerraformCount;
```

- *Type:* number | cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.dependsOn"></a>

```typescript
public readonly dependsOn: string[];
```

- *Type:* string[]

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.forEach"></a>

```typescript
public readonly forEach: ITerraformIterator;
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.provisioners"></a>

```typescript
public readonly provisioners: FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner[];
```

- *Type:* cdktf.FileProvisioner | cdktf.LocalExecProvisioner | cdktf.RemoteExecProvisioner[]

---

##### `alertMessageInput`<sup>Optional</sup> <a name="alertMessageInput" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.alertMessageInput"></a>

```typescript
public readonly alertMessageInput: string;
```

- *Type:* string

---

##### `alertPriorityInput`<sup>Optional</sup> <a name="alertPriorityInput" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.alertPriorityInput"></a>

```typescript
public readonly alertPriorityInput: string;
```

- *Type:* string

---

##### `alertTagsInput`<sup>Optional</sup> <a name="alertTagsInput" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.alertTagsInput"></a>

```typescript
public readonly alertTagsInput: string[];
```

- *Type:* string[]

---

##### `descriptionInput`<sup>Optional</sup> <a name="descriptionInput" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.descriptionInput"></a>

```typescript
public readonly descriptionInput: string;
```

- *Type:* string

---

##### `enabledInput`<sup>Optional</sup> <a name="enabledInput" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.enabledInput"></a>

```typescript
public readonly enabledInput: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `idInput`<sup>Optional</sup> <a name="idInput" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.idInput"></a>

```typescript
public readonly idInput: string;
```

- *Type:* string

---

##### `intervalInput`<sup>Optional</sup> <a name="intervalInput" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.intervalInput"></a>

```typescript
public readonly intervalInput: number;
```

- *Type:* number

---

##### `intervalUnitInput`<sup>Optional</sup> <a name="intervalUnitInput" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.intervalUnitInput"></a>

```typescript
public readonly intervalUnitInput: string;
```

- *Type:* string

---

##### `nameInput`<sup>Optional</sup> <a name="nameInput" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.nameInput"></a>

```typescript
public readonly nameInput: string;
```

- *Type:* string

---

##### `ownerTeamIdInput`<sup>Optional</sup> <a name="ownerTeamIdInput" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.ownerTeamIdInput"></a>

```typescript
public readonly ownerTeamIdInput: string;
```

- *Type:* string

---

##### `alertMessage`<sup>Required</sup> <a name="alertMessage" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.alertMessage"></a>

```typescript
public readonly alertMessage: string;
```

- *Type:* string

---

##### `alertPriority`<sup>Required</sup> <a name="alertPriority" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.alertPriority"></a>

```typescript
public readonly alertPriority: string;
```

- *Type:* string

---

##### `alertTags`<sup>Required</sup> <a name="alertTags" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.alertTags"></a>

```typescript
public readonly alertTags: string[];
```

- *Type:* string[]

---

##### `description`<sup>Required</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.description"></a>

```typescript
public readonly description: string;
```

- *Type:* string

---

##### `enabled`<sup>Required</sup> <a name="enabled" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.enabled"></a>

```typescript
public readonly enabled: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

---

##### `interval`<sup>Required</sup> <a name="interval" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.interval"></a>

```typescript
public readonly interval: number;
```

- *Type:* number

---

##### `intervalUnit`<sup>Required</sup> <a name="intervalUnit" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.intervalUnit"></a>

```typescript
public readonly intervalUnit: string;
```

- *Type:* string

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.name"></a>

```typescript
public readonly name: string;
```

- *Type:* string

---

##### `ownerTeamId`<sup>Required</sup> <a name="ownerTeamId" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.ownerTeamId"></a>

```typescript
public readonly ownerTeamId: string;
```

- *Type:* string

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.tfResourceType">tfResourceType</a></code> | <code>string</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="rhizo-co-terraform-provider-opsgenie.heartbeat.Heartbeat.property.tfResourceType"></a>

```typescript
public readonly tfResourceType: string;
```

- *Type:* string

---

## Structs <a name="Structs" id="Structs"></a>

### HeartbeatConfig <a name="HeartbeatConfig" id="rhizo-co-terraform-provider-opsgenie.heartbeat.HeartbeatConfig"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.heartbeat.HeartbeatConfig.Initializer"></a>

```typescript
import { heartbeat } from 'rhizo-co-terraform-provider-opsgenie'

const heartbeatConfig: heartbeat.HeartbeatConfig = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.HeartbeatConfig.property.connection">connection</a></code> | <code>cdktf.SSHProvisionerConnection \| cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.HeartbeatConfig.property.count">count</a></code> | <code>number \| cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.HeartbeatConfig.property.dependsOn">dependsOn</a></code> | <code>cdktf.ITerraformDependable[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.HeartbeatConfig.property.forEach">forEach</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.HeartbeatConfig.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.HeartbeatConfig.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.HeartbeatConfig.property.provisioners">provisioners</a></code> | <code>cdktf.FileProvisioner \| cdktf.LocalExecProvisioner \| cdktf.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.HeartbeatConfig.property.enabled">enabled</a></code> | <code>boolean \| cdktf.IResolvable</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/heartbeat#enabled Heartbeat#enabled}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.HeartbeatConfig.property.interval">interval</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/heartbeat#interval Heartbeat#interval}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.HeartbeatConfig.property.intervalUnit">intervalUnit</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/heartbeat#interval_unit Heartbeat#interval_unit}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.HeartbeatConfig.property.name">name</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/heartbeat#name Heartbeat#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.HeartbeatConfig.property.alertMessage">alertMessage</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/heartbeat#alert_message Heartbeat#alert_message}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.HeartbeatConfig.property.alertPriority">alertPriority</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/heartbeat#alert_priority Heartbeat#alert_priority}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.HeartbeatConfig.property.alertTags">alertTags</a></code> | <code>string[]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/heartbeat#alert_tags Heartbeat#alert_tags}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.HeartbeatConfig.property.description">description</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/heartbeat#description Heartbeat#description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.HeartbeatConfig.property.id">id</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/heartbeat#id Heartbeat#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.heartbeat.HeartbeatConfig.property.ownerTeamId">ownerTeamId</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/heartbeat#owner_team_id Heartbeat#owner_team_id}. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.heartbeat.HeartbeatConfig.property.connection"></a>

```typescript
public readonly connection: SSHProvisionerConnection | WinrmProvisionerConnection;
```

- *Type:* cdktf.SSHProvisionerConnection | cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.heartbeat.HeartbeatConfig.property.count"></a>

```typescript
public readonly count: number | TerraformCount;
```

- *Type:* number | cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="rhizo-co-terraform-provider-opsgenie.heartbeat.HeartbeatConfig.property.dependsOn"></a>

```typescript
public readonly dependsOn: ITerraformDependable[];
```

- *Type:* cdktf.ITerraformDependable[]

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="rhizo-co-terraform-provider-opsgenie.heartbeat.HeartbeatConfig.property.forEach"></a>

```typescript
public readonly forEach: ITerraformIterator;
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.heartbeat.HeartbeatConfig.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.heartbeat.HeartbeatConfig.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.heartbeat.HeartbeatConfig.property.provisioners"></a>

```typescript
public readonly provisioners: FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner[];
```

- *Type:* cdktf.FileProvisioner | cdktf.LocalExecProvisioner | cdktf.RemoteExecProvisioner[]

---

##### `enabled`<sup>Required</sup> <a name="enabled" id="rhizo-co-terraform-provider-opsgenie.heartbeat.HeartbeatConfig.property.enabled"></a>

```typescript
public readonly enabled: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/heartbeat#enabled Heartbeat#enabled}.

---

##### `interval`<sup>Required</sup> <a name="interval" id="rhizo-co-terraform-provider-opsgenie.heartbeat.HeartbeatConfig.property.interval"></a>

```typescript
public readonly interval: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/heartbeat#interval Heartbeat#interval}.

---

##### `intervalUnit`<sup>Required</sup> <a name="intervalUnit" id="rhizo-co-terraform-provider-opsgenie.heartbeat.HeartbeatConfig.property.intervalUnit"></a>

```typescript
public readonly intervalUnit: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/heartbeat#interval_unit Heartbeat#interval_unit}.

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.heartbeat.HeartbeatConfig.property.name"></a>

```typescript
public readonly name: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/heartbeat#name Heartbeat#name}.

---

##### `alertMessage`<sup>Optional</sup> <a name="alertMessage" id="rhizo-co-terraform-provider-opsgenie.heartbeat.HeartbeatConfig.property.alertMessage"></a>

```typescript
public readonly alertMessage: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/heartbeat#alert_message Heartbeat#alert_message}.

---

##### `alertPriority`<sup>Optional</sup> <a name="alertPriority" id="rhizo-co-terraform-provider-opsgenie.heartbeat.HeartbeatConfig.property.alertPriority"></a>

```typescript
public readonly alertPriority: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/heartbeat#alert_priority Heartbeat#alert_priority}.

---

##### `alertTags`<sup>Optional</sup> <a name="alertTags" id="rhizo-co-terraform-provider-opsgenie.heartbeat.HeartbeatConfig.property.alertTags"></a>

```typescript
public readonly alertTags: string[];
```

- *Type:* string[]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/heartbeat#alert_tags Heartbeat#alert_tags}.

---

##### `description`<sup>Optional</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.heartbeat.HeartbeatConfig.property.description"></a>

```typescript
public readonly description: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/heartbeat#description Heartbeat#description}.

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.heartbeat.HeartbeatConfig.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/heartbeat#id Heartbeat#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `ownerTeamId`<sup>Optional</sup> <a name="ownerTeamId" id="rhizo-co-terraform-provider-opsgenie.heartbeat.HeartbeatConfig.property.ownerTeamId"></a>

```typescript
public readonly ownerTeamId: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/heartbeat#owner_team_id Heartbeat#owner_team_id}.

---



