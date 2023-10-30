# `opsgenie_maintenance`

Refer to the Terraform Registory for docs: [`opsgenie_maintenance`](https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/maintenance).

# `maintenance` Submodule <a name="`maintenance` Submodule" id="rhizo-co-terraform-provider-opsgenie.maintenance"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### Maintenance <a name="Maintenance" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance"></a>

Represents a {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/maintenance opsgenie_maintenance}.

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.Initializer"></a>

```typescript
import { maintenance } from 'rhizo-co-terraform-provider-opsgenie'

new maintenance.Maintenance(scope: Construct, id: string, config: MaintenanceConfig)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.Initializer.parameter.id">id</a></code> | <code>string</code> | The scoped construct ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.Initializer.parameter.config">config</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceConfig">MaintenanceConfig</a></code> | *No description.* |

---

##### `scope`<sup>Required</sup> <a name="scope" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.Initializer.parameter.id"></a>

- *Type:* string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Required</sup> <a name="config" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.Initializer.parameter.config"></a>

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceConfig">MaintenanceConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.toString">toString</a></code> | Returns a string representation of this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.addOverride">addOverride</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.overrideLogicalId">overrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.resetOverrideLogicalId">resetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.toMetadata">toMetadata</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.toTerraform">toTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.putRules">putRules</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.putTime">putTime</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.resetId">resetId</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.resetTime">resetTime</a></code> | *No description.* |

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.toString"></a>

```typescript
public toString(): string
```

Returns a string representation of this construct.

##### `addOverride` <a name="addOverride" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.addOverride"></a>

```typescript
public addOverride(path: string, value: any): void
```

###### `path`<sup>Required</sup> <a name="path" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.addOverride.parameter.path"></a>

- *Type:* string

---

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.addOverride.parameter.value"></a>

- *Type:* any

---

##### `overrideLogicalId` <a name="overrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.overrideLogicalId"></a>

```typescript
public overrideLogicalId(newLogicalId: string): void
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* string

The new logical ID to use for this stack element.

---

##### `resetOverrideLogicalId` <a name="resetOverrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.resetOverrideLogicalId"></a>

```typescript
public resetOverrideLogicalId(): void
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `toMetadata` <a name="toMetadata" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.toMetadata"></a>

```typescript
public toMetadata(): any
```

##### `toTerraform` <a name="toTerraform" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.toTerraform"></a>

```typescript
public toTerraform(): any
```

Adds this resource to the terraform JSON output.

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `putRules` <a name="putRules" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.putRules"></a>

```typescript
public putRules(value: IResolvable | MaintenanceRules[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.putRules.parameter.value"></a>

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRules">MaintenanceRules</a>[]

---

##### `putTime` <a name="putTime" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.putTime"></a>

```typescript
public putTime(value: IResolvable | MaintenanceTime[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.putTime.parameter.value"></a>

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTime">MaintenanceTime</a>[]

---

##### `resetId` <a name="resetId" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.resetId"></a>

```typescript
public resetId(): void
```

##### `resetTime` <a name="resetTime" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.resetTime"></a>

```typescript
public resetTime(): void
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.isConstruct">isConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.isTerraformElement">isTerraformElement</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.isTerraformResource">isTerraformResource</a></code> | *No description.* |

---

##### `isConstruct` <a name="isConstruct" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.isConstruct"></a>

```typescript
import { maintenance } from 'rhizo-co-terraform-provider-opsgenie'

maintenance.Maintenance.isConstruct(x: any)
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

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.isConstruct.parameter.x"></a>

- *Type:* any

Any object.

---

##### `isTerraformElement` <a name="isTerraformElement" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.isTerraformElement"></a>

```typescript
import { maintenance } from 'rhizo-co-terraform-provider-opsgenie'

maintenance.Maintenance.isTerraformElement(x: any)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.isTerraformElement.parameter.x"></a>

- *Type:* any

---

##### `isTerraformResource` <a name="isTerraformResource" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.isTerraformResource"></a>

```typescript
import { maintenance } from 'rhizo-co-terraform-provider-opsgenie'

maintenance.Maintenance.isTerraformResource(x: any)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.isTerraformResource.parameter.x"></a>

- *Type:* any

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.node">node</a></code> | <code>constructs.Node</code> | The tree node. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.cdktfStack">cdktfStack</a></code> | <code>cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.friendlyUniqueId">friendlyUniqueId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.terraformMetaArguments">terraformMetaArguments</a></code> | <code>{[ key: string ]: any}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.terraformResourceType">terraformResourceType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.terraformGeneratorMetadata">terraformGeneratorMetadata</a></code> | <code>cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.connection">connection</a></code> | <code>cdktf.SSHProvisionerConnection \| cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.count">count</a></code> | <code>number \| cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.dependsOn">dependsOn</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.forEach">forEach</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.provisioners">provisioners</a></code> | <code>cdktf.FileProvisioner \| cdktf.LocalExecProvisioner \| cdktf.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.rules">rules</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesList">MaintenanceRulesList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.time">time</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeList">MaintenanceTimeList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.descriptionInput">descriptionInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.idInput">idInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.rulesInput">rulesInput</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRules">MaintenanceRules</a>[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.timeInput">timeInput</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTime">MaintenanceTime</a>[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.description">description</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.id">id</a></code> | <code>string</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.node"></a>

```typescript
public readonly node: Node;
```

- *Type:* constructs.Node

The tree node.

---

##### `cdktfStack`<sup>Required</sup> <a name="cdktfStack" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.cdktfStack"></a>

```typescript
public readonly cdktfStack: TerraformStack;
```

- *Type:* cdktf.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `friendlyUniqueId`<sup>Required</sup> <a name="friendlyUniqueId" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.friendlyUniqueId"></a>

```typescript
public readonly friendlyUniqueId: string;
```

- *Type:* string

---

##### `terraformMetaArguments`<sup>Required</sup> <a name="terraformMetaArguments" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.terraformMetaArguments"></a>

```typescript
public readonly terraformMetaArguments: {[ key: string ]: any};
```

- *Type:* {[ key: string ]: any}

---

##### `terraformResourceType`<sup>Required</sup> <a name="terraformResourceType" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.terraformResourceType"></a>

```typescript
public readonly terraformResourceType: string;
```

- *Type:* string

---

##### `terraformGeneratorMetadata`<sup>Optional</sup> <a name="terraformGeneratorMetadata" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.terraformGeneratorMetadata"></a>

```typescript
public readonly terraformGeneratorMetadata: TerraformProviderGeneratorMetadata;
```

- *Type:* cdktf.TerraformProviderGeneratorMetadata

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.connection"></a>

```typescript
public readonly connection: SSHProvisionerConnection | WinrmProvisionerConnection;
```

- *Type:* cdktf.SSHProvisionerConnection | cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.count"></a>

```typescript
public readonly count: number | TerraformCount;
```

- *Type:* number | cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.dependsOn"></a>

```typescript
public readonly dependsOn: string[];
```

- *Type:* string[]

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.forEach"></a>

```typescript
public readonly forEach: ITerraformIterator;
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.provisioners"></a>

```typescript
public readonly provisioners: FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner[];
```

- *Type:* cdktf.FileProvisioner | cdktf.LocalExecProvisioner | cdktf.RemoteExecProvisioner[]

---

##### `rules`<sup>Required</sup> <a name="rules" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.rules"></a>

```typescript
public readonly rules: MaintenanceRulesList;
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesList">MaintenanceRulesList</a>

---

##### `time`<sup>Required</sup> <a name="time" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.time"></a>

```typescript
public readonly time: MaintenanceTimeList;
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeList">MaintenanceTimeList</a>

---

##### `descriptionInput`<sup>Optional</sup> <a name="descriptionInput" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.descriptionInput"></a>

```typescript
public readonly descriptionInput: string;
```

- *Type:* string

---

##### `idInput`<sup>Optional</sup> <a name="idInput" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.idInput"></a>

```typescript
public readonly idInput: string;
```

- *Type:* string

---

##### `rulesInput`<sup>Optional</sup> <a name="rulesInput" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.rulesInput"></a>

```typescript
public readonly rulesInput: IResolvable | MaintenanceRules[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRules">MaintenanceRules</a>[]

---

##### `timeInput`<sup>Optional</sup> <a name="timeInput" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.timeInput"></a>

```typescript
public readonly timeInput: IResolvable | MaintenanceTime[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTime">MaintenanceTime</a>[]

---

##### `description`<sup>Required</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.description"></a>

```typescript
public readonly description: string;
```

- *Type:* string

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.tfResourceType">tfResourceType</a></code> | <code>string</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="rhizo-co-terraform-provider-opsgenie.maintenance.Maintenance.property.tfResourceType"></a>

```typescript
public readonly tfResourceType: string;
```

- *Type:* string

---

## Structs <a name="Structs" id="Structs"></a>

### MaintenanceConfig <a name="MaintenanceConfig" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceConfig"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceConfig.Initializer"></a>

```typescript
import { maintenance } from 'rhizo-co-terraform-provider-opsgenie'

const maintenanceConfig: maintenance.MaintenanceConfig = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceConfig.property.connection">connection</a></code> | <code>cdktf.SSHProvisionerConnection \| cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceConfig.property.count">count</a></code> | <code>number \| cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceConfig.property.dependsOn">dependsOn</a></code> | <code>cdktf.ITerraformDependable[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceConfig.property.forEach">forEach</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceConfig.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceConfig.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceConfig.property.provisioners">provisioners</a></code> | <code>cdktf.FileProvisioner \| cdktf.LocalExecProvisioner \| cdktf.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceConfig.property.description">description</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/maintenance#description Maintenance#description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceConfig.property.rules">rules</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRules">MaintenanceRules</a>[]</code> | rules block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceConfig.property.id">id</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/maintenance#id Maintenance#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceConfig.property.time">time</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTime">MaintenanceTime</a>[]</code> | time block. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceConfig.property.connection"></a>

```typescript
public readonly connection: SSHProvisionerConnection | WinrmProvisionerConnection;
```

- *Type:* cdktf.SSHProvisionerConnection | cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceConfig.property.count"></a>

```typescript
public readonly count: number | TerraformCount;
```

- *Type:* number | cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceConfig.property.dependsOn"></a>

```typescript
public readonly dependsOn: ITerraformDependable[];
```

- *Type:* cdktf.ITerraformDependable[]

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceConfig.property.forEach"></a>

```typescript
public readonly forEach: ITerraformIterator;
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceConfig.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceConfig.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceConfig.property.provisioners"></a>

```typescript
public readonly provisioners: FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner[];
```

- *Type:* cdktf.FileProvisioner | cdktf.LocalExecProvisioner | cdktf.RemoteExecProvisioner[]

---

##### `description`<sup>Required</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceConfig.property.description"></a>

```typescript
public readonly description: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/maintenance#description Maintenance#description}.

---

##### `rules`<sup>Required</sup> <a name="rules" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceConfig.property.rules"></a>

```typescript
public readonly rules: IResolvable | MaintenanceRules[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRules">MaintenanceRules</a>[]

rules block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/maintenance#rules Maintenance#rules}

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceConfig.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/maintenance#id Maintenance#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `time`<sup>Optional</sup> <a name="time" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceConfig.property.time"></a>

```typescript
public readonly time: IResolvable | MaintenanceTime[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTime">MaintenanceTime</a>[]

time block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/maintenance#time Maintenance#time}

---

### MaintenanceRules <a name="MaintenanceRules" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRules"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRules.Initializer"></a>

```typescript
import { maintenance } from 'rhizo-co-terraform-provider-opsgenie'

const maintenanceRules: maintenance.MaintenanceRules = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRules.property.entity">entity</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntity">MaintenanceRulesEntity</a>[]</code> | entity block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRules.property.state">state</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/maintenance#state Maintenance#state}. |

---

##### `entity`<sup>Required</sup> <a name="entity" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRules.property.entity"></a>

```typescript
public readonly entity: IResolvable | MaintenanceRulesEntity[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntity">MaintenanceRulesEntity</a>[]

entity block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/maintenance#entity Maintenance#entity}

---

##### `state`<sup>Optional</sup> <a name="state" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRules.property.state"></a>

```typescript
public readonly state: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/maintenance#state Maintenance#state}.

---

### MaintenanceRulesEntity <a name="MaintenanceRulesEntity" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntity"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntity.Initializer"></a>

```typescript
import { maintenance } from 'rhizo-co-terraform-provider-opsgenie'

const maintenanceRulesEntity: maintenance.MaintenanceRulesEntity = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntity.property.id">id</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/maintenance#id Maintenance#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntity.property.type">type</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/maintenance#type Maintenance#type}. |

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntity.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/maintenance#id Maintenance#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `type`<sup>Optional</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntity.property.type"></a>

```typescript
public readonly type: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/maintenance#type Maintenance#type}.

---

### MaintenanceTime <a name="MaintenanceTime" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTime"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTime.Initializer"></a>

```typescript
import { maintenance } from 'rhizo-co-terraform-provider-opsgenie'

const maintenanceTime: maintenance.MaintenanceTime = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTime.property.type">type</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/maintenance#type Maintenance#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTime.property.endDate">endDate</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/maintenance#end_date Maintenance#end_date}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTime.property.startDate">startDate</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/maintenance#start_date Maintenance#start_date}. |

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTime.property.type"></a>

```typescript
public readonly type: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/maintenance#type Maintenance#type}.

---

##### `endDate`<sup>Optional</sup> <a name="endDate" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTime.property.endDate"></a>

```typescript
public readonly endDate: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/maintenance#end_date Maintenance#end_date}.

---

##### `startDate`<sup>Optional</sup> <a name="startDate" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTime.property.startDate"></a>

```typescript
public readonly startDate: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/maintenance#start_date Maintenance#start_date}.

---

## Classes <a name="Classes" id="Classes"></a>

### MaintenanceRulesEntityList <a name="MaintenanceRulesEntityList" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityList.Initializer"></a>

```typescript
import { maintenance } from 'rhizo-co-terraform-provider-opsgenie'

new maintenance.MaintenanceRulesEntityList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityList.get"></a>

```typescript
public get(index: number): MaintenanceRulesEntityOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityList.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntity">MaintenanceRulesEntity</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | MaintenanceRulesEntity[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntity">MaintenanceRulesEntity</a>[]

---


### MaintenanceRulesEntityOutputReference <a name="MaintenanceRulesEntityOutputReference" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.Initializer"></a>

```typescript
import { maintenance } from 'rhizo-co-terraform-provider-opsgenie'

new maintenance.MaintenanceRulesEntityOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.resetId">resetId</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.resetType">resetType</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetId` <a name="resetId" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.resetId"></a>

```typescript
public resetId(): void
```

##### `resetType` <a name="resetType" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.resetType"></a>

```typescript
public resetType(): void
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.property.idInput">idInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.property.typeInput">typeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.property.id">id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.property.type">type</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntity">MaintenanceRulesEntity</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `idInput`<sup>Optional</sup> <a name="idInput" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.property.idInput"></a>

```typescript
public readonly idInput: string;
```

- *Type:* string

---

##### `typeInput`<sup>Optional</sup> <a name="typeInput" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.property.typeInput"></a>

```typescript
public readonly typeInput: string;
```

- *Type:* string

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.property.type"></a>

```typescript
public readonly type: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | MaintenanceRulesEntity;
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntity">MaintenanceRulesEntity</a>

---


### MaintenanceRulesList <a name="MaintenanceRulesList" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesList.Initializer"></a>

```typescript
import { maintenance } from 'rhizo-co-terraform-provider-opsgenie'

new maintenance.MaintenanceRulesList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesList.get"></a>

```typescript
public get(index: number): MaintenanceRulesOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesList.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRules">MaintenanceRules</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | MaintenanceRules[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRules">MaintenanceRules</a>[]

---


### MaintenanceRulesOutputReference <a name="MaintenanceRulesOutputReference" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.Initializer"></a>

```typescript
import { maintenance } from 'rhizo-co-terraform-provider-opsgenie'

new maintenance.MaintenanceRulesOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.putEntity">putEntity</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.resetState">resetState</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `putEntity` <a name="putEntity" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.putEntity"></a>

```typescript
public putEntity(value: IResolvable | MaintenanceRulesEntity[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.putEntity.parameter.value"></a>

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntity">MaintenanceRulesEntity</a>[]

---

##### `resetState` <a name="resetState" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.resetState"></a>

```typescript
public resetState(): void
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.property.entity">entity</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityList">MaintenanceRulesEntityList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.property.entityInput">entityInput</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntity">MaintenanceRulesEntity</a>[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.property.stateInput">stateInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.property.state">state</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRules">MaintenanceRules</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `entity`<sup>Required</sup> <a name="entity" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.property.entity"></a>

```typescript
public readonly entity: MaintenanceRulesEntityList;
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntityList">MaintenanceRulesEntityList</a>

---

##### `entityInput`<sup>Optional</sup> <a name="entityInput" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.property.entityInput"></a>

```typescript
public readonly entityInput: IResolvable | MaintenanceRulesEntity[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesEntity">MaintenanceRulesEntity</a>[]

---

##### `stateInput`<sup>Optional</sup> <a name="stateInput" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.property.stateInput"></a>

```typescript
public readonly stateInput: string;
```

- *Type:* string

---

##### `state`<sup>Required</sup> <a name="state" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.property.state"></a>

```typescript
public readonly state: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRulesOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | MaintenanceRules;
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceRules">MaintenanceRules</a>

---


### MaintenanceTimeList <a name="MaintenanceTimeList" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeList.Initializer"></a>

```typescript
import { maintenance } from 'rhizo-co-terraform-provider-opsgenie'

new maintenance.MaintenanceTimeList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeList.get"></a>

```typescript
public get(index: number): MaintenanceTimeOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeList.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTime">MaintenanceTime</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | MaintenanceTime[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTime">MaintenanceTime</a>[]

---


### MaintenanceTimeOutputReference <a name="MaintenanceTimeOutputReference" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.Initializer"></a>

```typescript
import { maintenance } from 'rhizo-co-terraform-provider-opsgenie'

new maintenance.MaintenanceTimeOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.resetEndDate">resetEndDate</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.resetStartDate">resetStartDate</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetEndDate` <a name="resetEndDate" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.resetEndDate"></a>

```typescript
public resetEndDate(): void
```

##### `resetStartDate` <a name="resetStartDate" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.resetStartDate"></a>

```typescript
public resetStartDate(): void
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.property.endDateInput">endDateInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.property.startDateInput">startDateInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.property.typeInput">typeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.property.endDate">endDate</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.property.startDate">startDate</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.property.type">type</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTime">MaintenanceTime</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `endDateInput`<sup>Optional</sup> <a name="endDateInput" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.property.endDateInput"></a>

```typescript
public readonly endDateInput: string;
```

- *Type:* string

---

##### `startDateInput`<sup>Optional</sup> <a name="startDateInput" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.property.startDateInput"></a>

```typescript
public readonly startDateInput: string;
```

- *Type:* string

---

##### `typeInput`<sup>Optional</sup> <a name="typeInput" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.property.typeInput"></a>

```typescript
public readonly typeInput: string;
```

- *Type:* string

---

##### `endDate`<sup>Required</sup> <a name="endDate" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.property.endDate"></a>

```typescript
public readonly endDate: string;
```

- *Type:* string

---

##### `startDate`<sup>Required</sup> <a name="startDate" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.property.startDate"></a>

```typescript
public readonly startDate: string;
```

- *Type:* string

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.property.type"></a>

```typescript
public readonly type: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTimeOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | MaintenanceTime;
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.maintenance.MaintenanceTime">MaintenanceTime</a>

---



