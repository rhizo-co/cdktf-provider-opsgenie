# `data_opsgenie_escalation`

Refer to the Terraform Registory for docs: [`data_opsgenie_escalation`](https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation).

# `dataOpsgenieEscalation` Submodule <a name="`dataOpsgenieEscalation` Submodule" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### DataOpsgenieEscalation <a name="DataOpsgenieEscalation" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation"></a>

Represents a {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation opsgenie_escalation}.

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer"></a>

```typescript
import { dataOpsgenieEscalation } from 'rhizo-co-terraform-provider-opsgenie'

new dataOpsgenieEscalation.DataOpsgenieEscalation(scope: Construct, id: string, config: DataOpsgenieEscalationConfig)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.id">id</a></code> | <code>string</code> | The scoped construct ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.config">config</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig">DataOpsgenieEscalationConfig</a></code> | *No description.* |

---

##### `scope`<sup>Required</sup> <a name="scope" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.id"></a>

- *Type:* string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Required</sup> <a name="config" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.config"></a>

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig">DataOpsgenieEscalationConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.toString">toString</a></code> | Returns a string representation of this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.addOverride">addOverride</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.overrideLogicalId">overrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetOverrideLogicalId">resetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.toMetadata">toMetadata</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.toTerraform">toTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.putRepeat">putRepeat</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.putRules">putRules</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetDescription">resetDescription</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetId">resetId</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetOwnerTeamId">resetOwnerTeamId</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetRepeat">resetRepeat</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetRules">resetRules</a></code> | *No description.* |

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.toString"></a>

```typescript
public toString(): string
```

Returns a string representation of this construct.

##### `addOverride` <a name="addOverride" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.addOverride"></a>

```typescript
public addOverride(path: string, value: any): void
```

###### `path`<sup>Required</sup> <a name="path" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.addOverride.parameter.path"></a>

- *Type:* string

---

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.addOverride.parameter.value"></a>

- *Type:* any

---

##### `overrideLogicalId` <a name="overrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.overrideLogicalId"></a>

```typescript
public overrideLogicalId(newLogicalId: string): void
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* string

The new logical ID to use for this stack element.

---

##### `resetOverrideLogicalId` <a name="resetOverrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetOverrideLogicalId"></a>

```typescript
public resetOverrideLogicalId(): void
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `toMetadata` <a name="toMetadata" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.toMetadata"></a>

```typescript
public toMetadata(): any
```

##### `toTerraform` <a name="toTerraform" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.toTerraform"></a>

```typescript
public toTerraform(): any
```

Adds this resource to the terraform JSON output.

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `putRepeat` <a name="putRepeat" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.putRepeat"></a>

```typescript
public putRepeat(value: IResolvable | DataOpsgenieEscalationRepeat[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.putRepeat.parameter.value"></a>

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat">DataOpsgenieEscalationRepeat</a>[]

---

##### `putRules` <a name="putRules" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.putRules"></a>

```typescript
public putRules(value: IResolvable | DataOpsgenieEscalationRules[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.putRules.parameter.value"></a>

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules">DataOpsgenieEscalationRules</a>[]

---

##### `resetDescription` <a name="resetDescription" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetDescription"></a>

```typescript
public resetDescription(): void
```

##### `resetId` <a name="resetId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetId"></a>

```typescript
public resetId(): void
```

##### `resetOwnerTeamId` <a name="resetOwnerTeamId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetOwnerTeamId"></a>

```typescript
public resetOwnerTeamId(): void
```

##### `resetRepeat` <a name="resetRepeat" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetRepeat"></a>

```typescript
public resetRepeat(): void
```

##### `resetRules` <a name="resetRules" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetRules"></a>

```typescript
public resetRules(): void
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.isConstruct">isConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.isTerraformElement">isTerraformElement</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.isTerraformDataSource">isTerraformDataSource</a></code> | *No description.* |

---

##### `isConstruct` <a name="isConstruct" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.isConstruct"></a>

```typescript
import { dataOpsgenieEscalation } from 'rhizo-co-terraform-provider-opsgenie'

dataOpsgenieEscalation.DataOpsgenieEscalation.isConstruct(x: any)
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

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.isConstruct.parameter.x"></a>

- *Type:* any

Any object.

---

##### `isTerraformElement` <a name="isTerraformElement" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.isTerraformElement"></a>

```typescript
import { dataOpsgenieEscalation } from 'rhizo-co-terraform-provider-opsgenie'

dataOpsgenieEscalation.DataOpsgenieEscalation.isTerraformElement(x: any)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.isTerraformElement.parameter.x"></a>

- *Type:* any

---

##### `isTerraformDataSource` <a name="isTerraformDataSource" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.isTerraformDataSource"></a>

```typescript
import { dataOpsgenieEscalation } from 'rhizo-co-terraform-provider-opsgenie'

dataOpsgenieEscalation.DataOpsgenieEscalation.isTerraformDataSource(x: any)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.isTerraformDataSource.parameter.x"></a>

- *Type:* any

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.node">node</a></code> | <code>constructs.Node</code> | The tree node. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.cdktfStack">cdktfStack</a></code> | <code>cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.friendlyUniqueId">friendlyUniqueId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.terraformMetaArguments">terraformMetaArguments</a></code> | <code>{[ key: string ]: any}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.terraformResourceType">terraformResourceType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.terraformGeneratorMetadata">terraformGeneratorMetadata</a></code> | <code>cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.count">count</a></code> | <code>number \| cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.dependsOn">dependsOn</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.forEach">forEach</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.repeat">repeat</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList">DataOpsgenieEscalationRepeatList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.rules">rules</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList">DataOpsgenieEscalationRulesList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.descriptionInput">descriptionInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.idInput">idInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.nameInput">nameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.ownerTeamIdInput">ownerTeamIdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.repeatInput">repeatInput</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat">DataOpsgenieEscalationRepeat</a>[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.rulesInput">rulesInput</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules">DataOpsgenieEscalationRules</a>[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.description">description</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.id">id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.name">name</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.ownerTeamId">ownerTeamId</a></code> | <code>string</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.node"></a>

```typescript
public readonly node: Node;
```

- *Type:* constructs.Node

The tree node.

---

##### `cdktfStack`<sup>Required</sup> <a name="cdktfStack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.cdktfStack"></a>

```typescript
public readonly cdktfStack: TerraformStack;
```

- *Type:* cdktf.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `friendlyUniqueId`<sup>Required</sup> <a name="friendlyUniqueId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.friendlyUniqueId"></a>

```typescript
public readonly friendlyUniqueId: string;
```

- *Type:* string

---

##### `terraformMetaArguments`<sup>Required</sup> <a name="terraformMetaArguments" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.terraformMetaArguments"></a>

```typescript
public readonly terraformMetaArguments: {[ key: string ]: any};
```

- *Type:* {[ key: string ]: any}

---

##### `terraformResourceType`<sup>Required</sup> <a name="terraformResourceType" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.terraformResourceType"></a>

```typescript
public readonly terraformResourceType: string;
```

- *Type:* string

---

##### `terraformGeneratorMetadata`<sup>Optional</sup> <a name="terraformGeneratorMetadata" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.terraformGeneratorMetadata"></a>

```typescript
public readonly terraformGeneratorMetadata: TerraformProviderGeneratorMetadata;
```

- *Type:* cdktf.TerraformProviderGeneratorMetadata

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.count"></a>

```typescript
public readonly count: number | TerraformCount;
```

- *Type:* number | cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.dependsOn"></a>

```typescript
public readonly dependsOn: string[];
```

- *Type:* string[]

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.forEach"></a>

```typescript
public readonly forEach: ITerraformIterator;
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* cdktf.TerraformProvider

---

##### `repeat`<sup>Required</sup> <a name="repeat" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.repeat"></a>

```typescript
public readonly repeat: DataOpsgenieEscalationRepeatList;
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList">DataOpsgenieEscalationRepeatList</a>

---

##### `rules`<sup>Required</sup> <a name="rules" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.rules"></a>

```typescript
public readonly rules: DataOpsgenieEscalationRulesList;
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList">DataOpsgenieEscalationRulesList</a>

---

##### `descriptionInput`<sup>Optional</sup> <a name="descriptionInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.descriptionInput"></a>

```typescript
public readonly descriptionInput: string;
```

- *Type:* string

---

##### `idInput`<sup>Optional</sup> <a name="idInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.idInput"></a>

```typescript
public readonly idInput: string;
```

- *Type:* string

---

##### `nameInput`<sup>Optional</sup> <a name="nameInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.nameInput"></a>

```typescript
public readonly nameInput: string;
```

- *Type:* string

---

##### `ownerTeamIdInput`<sup>Optional</sup> <a name="ownerTeamIdInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.ownerTeamIdInput"></a>

```typescript
public readonly ownerTeamIdInput: string;
```

- *Type:* string

---

##### `repeatInput`<sup>Optional</sup> <a name="repeatInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.repeatInput"></a>

```typescript
public readonly repeatInput: IResolvable | DataOpsgenieEscalationRepeat[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat">DataOpsgenieEscalationRepeat</a>[]

---

##### `rulesInput`<sup>Optional</sup> <a name="rulesInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.rulesInput"></a>

```typescript
public readonly rulesInput: IResolvable | DataOpsgenieEscalationRules[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules">DataOpsgenieEscalationRules</a>[]

---

##### `description`<sup>Required</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.description"></a>

```typescript
public readonly description: string;
```

- *Type:* string

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.name"></a>

```typescript
public readonly name: string;
```

- *Type:* string

---

##### `ownerTeamId`<sup>Required</sup> <a name="ownerTeamId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.ownerTeamId"></a>

```typescript
public readonly ownerTeamId: string;
```

- *Type:* string

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.tfResourceType">tfResourceType</a></code> | <code>string</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.tfResourceType"></a>

```typescript
public readonly tfResourceType: string;
```

- *Type:* string

---

## Structs <a name="Structs" id="Structs"></a>

### DataOpsgenieEscalationConfig <a name="DataOpsgenieEscalationConfig" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.Initializer"></a>

```typescript
import { dataOpsgenieEscalation } from 'rhizo-co-terraform-provider-opsgenie'

const dataOpsgenieEscalationConfig: dataOpsgenieEscalation.DataOpsgenieEscalationConfig = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.connection">connection</a></code> | <code>cdktf.SSHProvisionerConnection \| cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.count">count</a></code> | <code>number \| cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.dependsOn">dependsOn</a></code> | <code>cdktf.ITerraformDependable[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.forEach">forEach</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.provisioners">provisioners</a></code> | <code>cdktf.FileProvisioner \| cdktf.LocalExecProvisioner \| cdktf.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.name">name</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#name DataOpsgenieEscalation#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.description">description</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#description DataOpsgenieEscalation#description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.id">id</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#id DataOpsgenieEscalation#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.ownerTeamId">ownerTeamId</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#owner_team_id DataOpsgenieEscalation#owner_team_id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.repeat">repeat</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat">DataOpsgenieEscalationRepeat</a>[]</code> | repeat block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.rules">rules</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules">DataOpsgenieEscalationRules</a>[]</code> | rules block. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.connection"></a>

```typescript
public readonly connection: SSHProvisionerConnection | WinrmProvisionerConnection;
```

- *Type:* cdktf.SSHProvisionerConnection | cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.count"></a>

```typescript
public readonly count: number | TerraformCount;
```

- *Type:* number | cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.dependsOn"></a>

```typescript
public readonly dependsOn: ITerraformDependable[];
```

- *Type:* cdktf.ITerraformDependable[]

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.forEach"></a>

```typescript
public readonly forEach: ITerraformIterator;
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.provisioners"></a>

```typescript
public readonly provisioners: FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner[];
```

- *Type:* cdktf.FileProvisioner | cdktf.LocalExecProvisioner | cdktf.RemoteExecProvisioner[]

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.name"></a>

```typescript
public readonly name: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#name DataOpsgenieEscalation#name}.

---

##### `description`<sup>Optional</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.description"></a>

```typescript
public readonly description: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#description DataOpsgenieEscalation#description}.

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#id DataOpsgenieEscalation#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `ownerTeamId`<sup>Optional</sup> <a name="ownerTeamId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.ownerTeamId"></a>

```typescript
public readonly ownerTeamId: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#owner_team_id DataOpsgenieEscalation#owner_team_id}.

---

##### `repeat`<sup>Optional</sup> <a name="repeat" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.repeat"></a>

```typescript
public readonly repeat: IResolvable | DataOpsgenieEscalationRepeat[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat">DataOpsgenieEscalationRepeat</a>[]

repeat block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#repeat DataOpsgenieEscalation#repeat}

---

##### `rules`<sup>Optional</sup> <a name="rules" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.rules"></a>

```typescript
public readonly rules: IResolvable | DataOpsgenieEscalationRules[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules">DataOpsgenieEscalationRules</a>[]

rules block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#rules DataOpsgenieEscalation#rules}

---

### DataOpsgenieEscalationRepeat <a name="DataOpsgenieEscalationRepeat" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat.Initializer"></a>

```typescript
import { dataOpsgenieEscalation } from 'rhizo-co-terraform-provider-opsgenie'

const dataOpsgenieEscalationRepeat: dataOpsgenieEscalation.DataOpsgenieEscalationRepeat = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat.property.closeAlertAfterAll">closeAlertAfterAll</a></code> | <code>boolean \| cdktf.IResolvable</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#close_alert_after_all DataOpsgenieEscalation#close_alert_after_all}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat.property.count">count</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#count DataOpsgenieEscalation#count}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat.property.resetRecipientStates">resetRecipientStates</a></code> | <code>boolean \| cdktf.IResolvable</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#reset_recipient_states DataOpsgenieEscalation#reset_recipient_states}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat.property.waitInterval">waitInterval</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#wait_interval DataOpsgenieEscalation#wait_interval}. |

---

##### `closeAlertAfterAll`<sup>Optional</sup> <a name="closeAlertAfterAll" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat.property.closeAlertAfterAll"></a>

```typescript
public readonly closeAlertAfterAll: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#close_alert_after_all DataOpsgenieEscalation#close_alert_after_all}.

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat.property.count"></a>

```typescript
public readonly count: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#count DataOpsgenieEscalation#count}.

---

##### `resetRecipientStates`<sup>Optional</sup> <a name="resetRecipientStates" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat.property.resetRecipientStates"></a>

```typescript
public readonly resetRecipientStates: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#reset_recipient_states DataOpsgenieEscalation#reset_recipient_states}.

---

##### `waitInterval`<sup>Optional</sup> <a name="waitInterval" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat.property.waitInterval"></a>

```typescript
public readonly waitInterval: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#wait_interval DataOpsgenieEscalation#wait_interval}.

---

### DataOpsgenieEscalationRules <a name="DataOpsgenieEscalationRules" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules.Initializer"></a>

```typescript
import { dataOpsgenieEscalation } from 'rhizo-co-terraform-provider-opsgenie'

const dataOpsgenieEscalationRules: dataOpsgenieEscalation.DataOpsgenieEscalationRules = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules.property.condition">condition</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#condition DataOpsgenieEscalation#condition}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules.property.delay">delay</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#delay DataOpsgenieEscalation#delay}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules.property.notifyType">notifyType</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#notify_type DataOpsgenieEscalation#notify_type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules.property.recipient">recipient</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient">DataOpsgenieEscalationRulesRecipient</a>[]</code> | recipient block. |

---

##### `condition`<sup>Required</sup> <a name="condition" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules.property.condition"></a>

```typescript
public readonly condition: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#condition DataOpsgenieEscalation#condition}.

---

##### `delay`<sup>Required</sup> <a name="delay" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules.property.delay"></a>

```typescript
public readonly delay: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#delay DataOpsgenieEscalation#delay}.

---

##### `notifyType`<sup>Required</sup> <a name="notifyType" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules.property.notifyType"></a>

```typescript
public readonly notifyType: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#notify_type DataOpsgenieEscalation#notify_type}.

---

##### `recipient`<sup>Required</sup> <a name="recipient" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules.property.recipient"></a>

```typescript
public readonly recipient: IResolvable | DataOpsgenieEscalationRulesRecipient[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient">DataOpsgenieEscalationRulesRecipient</a>[]

recipient block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#recipient DataOpsgenieEscalation#recipient}

---

### DataOpsgenieEscalationRulesRecipient <a name="DataOpsgenieEscalationRulesRecipient" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient.Initializer"></a>

```typescript
import { dataOpsgenieEscalation } from 'rhizo-co-terraform-provider-opsgenie'

const dataOpsgenieEscalationRulesRecipient: dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient.property.id">id</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#id DataOpsgenieEscalation#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient.property.type">type</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#type DataOpsgenieEscalation#type}. |

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#id DataOpsgenieEscalation#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `type`<sup>Optional</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient.property.type"></a>

```typescript
public readonly type: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#type DataOpsgenieEscalation#type}.

---

## Classes <a name="Classes" id="Classes"></a>

### DataOpsgenieEscalationRepeatList <a name="DataOpsgenieEscalationRepeatList" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.Initializer"></a>

```typescript
import { dataOpsgenieEscalation } from 'rhizo-co-terraform-provider-opsgenie'

new dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.get"></a>

```typescript
public get(index: number): DataOpsgenieEscalationRepeatOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat">DataOpsgenieEscalationRepeat</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | DataOpsgenieEscalationRepeat[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat">DataOpsgenieEscalationRepeat</a>[]

---


### DataOpsgenieEscalationRepeatOutputReference <a name="DataOpsgenieEscalationRepeatOutputReference" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.Initializer"></a>

```typescript
import { dataOpsgenieEscalation } from 'rhizo-co-terraform-provider-opsgenie'

new dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resetCloseAlertAfterAll">resetCloseAlertAfterAll</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resetCount">resetCount</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resetResetRecipientStates">resetResetRecipientStates</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resetWaitInterval">resetWaitInterval</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetCloseAlertAfterAll` <a name="resetCloseAlertAfterAll" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resetCloseAlertAfterAll"></a>

```typescript
public resetCloseAlertAfterAll(): void
```

##### `resetCount` <a name="resetCount" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resetCount"></a>

```typescript
public resetCount(): void
```

##### `resetResetRecipientStates` <a name="resetResetRecipientStates" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resetResetRecipientStates"></a>

```typescript
public resetResetRecipientStates(): void
```

##### `resetWaitInterval` <a name="resetWaitInterval" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resetWaitInterval"></a>

```typescript
public resetWaitInterval(): void
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.closeAlertAfterAllInput">closeAlertAfterAllInput</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.countInput">countInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.resetRecipientStatesInput">resetRecipientStatesInput</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.waitIntervalInput">waitIntervalInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.closeAlertAfterAll">closeAlertAfterAll</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.count">count</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.resetRecipientStates">resetRecipientStates</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.waitInterval">waitInterval</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat">DataOpsgenieEscalationRepeat</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `closeAlertAfterAllInput`<sup>Optional</sup> <a name="closeAlertAfterAllInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.closeAlertAfterAllInput"></a>

```typescript
public readonly closeAlertAfterAllInput: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `countInput`<sup>Optional</sup> <a name="countInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.countInput"></a>

```typescript
public readonly countInput: number;
```

- *Type:* number

---

##### `resetRecipientStatesInput`<sup>Optional</sup> <a name="resetRecipientStatesInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.resetRecipientStatesInput"></a>

```typescript
public readonly resetRecipientStatesInput: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `waitIntervalInput`<sup>Optional</sup> <a name="waitIntervalInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.waitIntervalInput"></a>

```typescript
public readonly waitIntervalInput: number;
```

- *Type:* number

---

##### `closeAlertAfterAll`<sup>Required</sup> <a name="closeAlertAfterAll" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.closeAlertAfterAll"></a>

```typescript
public readonly closeAlertAfterAll: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `count`<sup>Required</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.count"></a>

```typescript
public readonly count: number;
```

- *Type:* number

---

##### `resetRecipientStates`<sup>Required</sup> <a name="resetRecipientStates" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.resetRecipientStates"></a>

```typescript
public readonly resetRecipientStates: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `waitInterval`<sup>Required</sup> <a name="waitInterval" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.waitInterval"></a>

```typescript
public readonly waitInterval: number;
```

- *Type:* number

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | DataOpsgenieEscalationRepeat;
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat">DataOpsgenieEscalationRepeat</a>

---


### DataOpsgenieEscalationRulesList <a name="DataOpsgenieEscalationRulesList" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.Initializer"></a>

```typescript
import { dataOpsgenieEscalation } from 'rhizo-co-terraform-provider-opsgenie'

new dataOpsgenieEscalation.DataOpsgenieEscalationRulesList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.get"></a>

```typescript
public get(index: number): DataOpsgenieEscalationRulesOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules">DataOpsgenieEscalationRules</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | DataOpsgenieEscalationRules[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules">DataOpsgenieEscalationRules</a>[]

---


### DataOpsgenieEscalationRulesOutputReference <a name="DataOpsgenieEscalationRulesOutputReference" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.Initializer"></a>

```typescript
import { dataOpsgenieEscalation } from 'rhizo-co-terraform-provider-opsgenie'

new dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.putRecipient">putRecipient</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `putRecipient` <a name="putRecipient" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.putRecipient"></a>

```typescript
public putRecipient(value: IResolvable | DataOpsgenieEscalationRulesRecipient[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.putRecipient.parameter.value"></a>

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient">DataOpsgenieEscalationRulesRecipient</a>[]

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.recipient">recipient</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList">DataOpsgenieEscalationRulesRecipientList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.conditionInput">conditionInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.delayInput">delayInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.notifyTypeInput">notifyTypeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.recipientInput">recipientInput</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient">DataOpsgenieEscalationRulesRecipient</a>[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.condition">condition</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.delay">delay</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.notifyType">notifyType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules">DataOpsgenieEscalationRules</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `recipient`<sup>Required</sup> <a name="recipient" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.recipient"></a>

```typescript
public readonly recipient: DataOpsgenieEscalationRulesRecipientList;
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList">DataOpsgenieEscalationRulesRecipientList</a>

---

##### `conditionInput`<sup>Optional</sup> <a name="conditionInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.conditionInput"></a>

```typescript
public readonly conditionInput: string;
```

- *Type:* string

---

##### `delayInput`<sup>Optional</sup> <a name="delayInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.delayInput"></a>

```typescript
public readonly delayInput: number;
```

- *Type:* number

---

##### `notifyTypeInput`<sup>Optional</sup> <a name="notifyTypeInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.notifyTypeInput"></a>

```typescript
public readonly notifyTypeInput: string;
```

- *Type:* string

---

##### `recipientInput`<sup>Optional</sup> <a name="recipientInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.recipientInput"></a>

```typescript
public readonly recipientInput: IResolvable | DataOpsgenieEscalationRulesRecipient[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient">DataOpsgenieEscalationRulesRecipient</a>[]

---

##### `condition`<sup>Required</sup> <a name="condition" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.condition"></a>

```typescript
public readonly condition: string;
```

- *Type:* string

---

##### `delay`<sup>Required</sup> <a name="delay" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.delay"></a>

```typescript
public readonly delay: number;
```

- *Type:* number

---

##### `notifyType`<sup>Required</sup> <a name="notifyType" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.notifyType"></a>

```typescript
public readonly notifyType: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | DataOpsgenieEscalationRules;
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules">DataOpsgenieEscalationRules</a>

---


### DataOpsgenieEscalationRulesRecipientList <a name="DataOpsgenieEscalationRulesRecipientList" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.Initializer"></a>

```typescript
import { dataOpsgenieEscalation } from 'rhizo-co-terraform-provider-opsgenie'

new dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.get"></a>

```typescript
public get(index: number): DataOpsgenieEscalationRulesRecipientOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient">DataOpsgenieEscalationRulesRecipient</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | DataOpsgenieEscalationRulesRecipient[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient">DataOpsgenieEscalationRulesRecipient</a>[]

---


### DataOpsgenieEscalationRulesRecipientOutputReference <a name="DataOpsgenieEscalationRulesRecipientOutputReference" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.Initializer"></a>

```typescript
import { dataOpsgenieEscalation } from 'rhizo-co-terraform-provider-opsgenie'

new dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.resetId">resetId</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.resetType">resetType</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetId` <a name="resetId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.resetId"></a>

```typescript
public resetId(): void
```

##### `resetType` <a name="resetType" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.resetType"></a>

```typescript
public resetType(): void
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.idInput">idInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.typeInput">typeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.id">id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.type">type</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient">DataOpsgenieEscalationRulesRecipient</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `idInput`<sup>Optional</sup> <a name="idInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.idInput"></a>

```typescript
public readonly idInput: string;
```

- *Type:* string

---

##### `typeInput`<sup>Optional</sup> <a name="typeInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.typeInput"></a>

```typescript
public readonly typeInput: string;
```

- *Type:* string

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.type"></a>

```typescript
public readonly type: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | DataOpsgenieEscalationRulesRecipient;
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient">DataOpsgenieEscalationRulesRecipient</a>

---



