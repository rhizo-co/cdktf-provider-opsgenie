# `data_opsgenie_team`

Refer to the Terraform Registory for docs: [`data_opsgenie_team`](https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/team).

# `dataOpsgenieTeam` Submodule <a name="`dataOpsgenieTeam` Submodule" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### DataOpsgenieTeam <a name="DataOpsgenieTeam" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam"></a>

Represents a {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/team opsgenie_team}.

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.Initializer"></a>

```typescript
import { dataOpsgenieTeam } from 'rhizo-co-terraform-provider-opsgenie'

new dataOpsgenieTeam.DataOpsgenieTeam(scope: Construct, id: string, config: DataOpsgenieTeamConfig)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.Initializer.parameter.id">id</a></code> | <code>string</code> | The scoped construct ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.Initializer.parameter.config">config</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig">DataOpsgenieTeamConfig</a></code> | *No description.* |

---

##### `scope`<sup>Required</sup> <a name="scope" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.Initializer.parameter.id"></a>

- *Type:* string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Required</sup> <a name="config" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.Initializer.parameter.config"></a>

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig">DataOpsgenieTeamConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.toString">toString</a></code> | Returns a string representation of this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.addOverride">addOverride</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.overrideLogicalId">overrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.resetOverrideLogicalId">resetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.toMetadata">toMetadata</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.toTerraform">toTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.putMember">putMember</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.resetDescription">resetDescription</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.resetId">resetId</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.resetMember">resetMember</a></code> | *No description.* |

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.toString"></a>

```typescript
public toString(): string
```

Returns a string representation of this construct.

##### `addOverride` <a name="addOverride" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.addOverride"></a>

```typescript
public addOverride(path: string, value: any): void
```

###### `path`<sup>Required</sup> <a name="path" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.addOverride.parameter.path"></a>

- *Type:* string

---

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.addOverride.parameter.value"></a>

- *Type:* any

---

##### `overrideLogicalId` <a name="overrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.overrideLogicalId"></a>

```typescript
public overrideLogicalId(newLogicalId: string): void
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* string

The new logical ID to use for this stack element.

---

##### `resetOverrideLogicalId` <a name="resetOverrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.resetOverrideLogicalId"></a>

```typescript
public resetOverrideLogicalId(): void
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `toMetadata` <a name="toMetadata" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.toMetadata"></a>

```typescript
public toMetadata(): any
```

##### `toTerraform` <a name="toTerraform" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.toTerraform"></a>

```typescript
public toTerraform(): any
```

Adds this resource to the terraform JSON output.

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `putMember` <a name="putMember" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.putMember"></a>

```typescript
public putMember(value: IResolvable | DataOpsgenieTeamMember[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.putMember.parameter.value"></a>

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMember">DataOpsgenieTeamMember</a>[]

---

##### `resetDescription` <a name="resetDescription" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.resetDescription"></a>

```typescript
public resetDescription(): void
```

##### `resetId` <a name="resetId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.resetId"></a>

```typescript
public resetId(): void
```

##### `resetMember` <a name="resetMember" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.resetMember"></a>

```typescript
public resetMember(): void
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.isConstruct">isConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.isTerraformElement">isTerraformElement</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.isTerraformDataSource">isTerraformDataSource</a></code> | *No description.* |

---

##### `isConstruct` <a name="isConstruct" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.isConstruct"></a>

```typescript
import { dataOpsgenieTeam } from 'rhizo-co-terraform-provider-opsgenie'

dataOpsgenieTeam.DataOpsgenieTeam.isConstruct(x: any)
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

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.isConstruct.parameter.x"></a>

- *Type:* any

Any object.

---

##### `isTerraformElement` <a name="isTerraformElement" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.isTerraformElement"></a>

```typescript
import { dataOpsgenieTeam } from 'rhizo-co-terraform-provider-opsgenie'

dataOpsgenieTeam.DataOpsgenieTeam.isTerraformElement(x: any)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.isTerraformElement.parameter.x"></a>

- *Type:* any

---

##### `isTerraformDataSource` <a name="isTerraformDataSource" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.isTerraformDataSource"></a>

```typescript
import { dataOpsgenieTeam } from 'rhizo-co-terraform-provider-opsgenie'

dataOpsgenieTeam.DataOpsgenieTeam.isTerraformDataSource(x: any)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.isTerraformDataSource.parameter.x"></a>

- *Type:* any

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.node">node</a></code> | <code>constructs.Node</code> | The tree node. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.cdktfStack">cdktfStack</a></code> | <code>cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.friendlyUniqueId">friendlyUniqueId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.terraformMetaArguments">terraformMetaArguments</a></code> | <code>{[ key: string ]: any}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.terraformResourceType">terraformResourceType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.terraformGeneratorMetadata">terraformGeneratorMetadata</a></code> | <code>cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.count">count</a></code> | <code>number \| cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.dependsOn">dependsOn</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.forEach">forEach</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.member">member</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList">DataOpsgenieTeamMemberList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.descriptionInput">descriptionInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.idInput">idInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.memberInput">memberInput</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMember">DataOpsgenieTeamMember</a>[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.nameInput">nameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.description">description</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.id">id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.name">name</a></code> | <code>string</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.node"></a>

```typescript
public readonly node: Node;
```

- *Type:* constructs.Node

The tree node.

---

##### `cdktfStack`<sup>Required</sup> <a name="cdktfStack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.cdktfStack"></a>

```typescript
public readonly cdktfStack: TerraformStack;
```

- *Type:* cdktf.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `friendlyUniqueId`<sup>Required</sup> <a name="friendlyUniqueId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.friendlyUniqueId"></a>

```typescript
public readonly friendlyUniqueId: string;
```

- *Type:* string

---

##### `terraformMetaArguments`<sup>Required</sup> <a name="terraformMetaArguments" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.terraformMetaArguments"></a>

```typescript
public readonly terraformMetaArguments: {[ key: string ]: any};
```

- *Type:* {[ key: string ]: any}

---

##### `terraformResourceType`<sup>Required</sup> <a name="terraformResourceType" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.terraformResourceType"></a>

```typescript
public readonly terraformResourceType: string;
```

- *Type:* string

---

##### `terraformGeneratorMetadata`<sup>Optional</sup> <a name="terraformGeneratorMetadata" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.terraformGeneratorMetadata"></a>

```typescript
public readonly terraformGeneratorMetadata: TerraformProviderGeneratorMetadata;
```

- *Type:* cdktf.TerraformProviderGeneratorMetadata

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.count"></a>

```typescript
public readonly count: number | TerraformCount;
```

- *Type:* number | cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.dependsOn"></a>

```typescript
public readonly dependsOn: string[];
```

- *Type:* string[]

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.forEach"></a>

```typescript
public readonly forEach: ITerraformIterator;
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* cdktf.TerraformProvider

---

##### `member`<sup>Required</sup> <a name="member" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.member"></a>

```typescript
public readonly member: DataOpsgenieTeamMemberList;
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList">DataOpsgenieTeamMemberList</a>

---

##### `descriptionInput`<sup>Optional</sup> <a name="descriptionInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.descriptionInput"></a>

```typescript
public readonly descriptionInput: string;
```

- *Type:* string

---

##### `idInput`<sup>Optional</sup> <a name="idInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.idInput"></a>

```typescript
public readonly idInput: string;
```

- *Type:* string

---

##### `memberInput`<sup>Optional</sup> <a name="memberInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.memberInput"></a>

```typescript
public readonly memberInput: IResolvable | DataOpsgenieTeamMember[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMember">DataOpsgenieTeamMember</a>[]

---

##### `nameInput`<sup>Optional</sup> <a name="nameInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.nameInput"></a>

```typescript
public readonly nameInput: string;
```

- *Type:* string

---

##### `description`<sup>Required</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.description"></a>

```typescript
public readonly description: string;
```

- *Type:* string

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.name"></a>

```typescript
public readonly name: string;
```

- *Type:* string

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.tfResourceType">tfResourceType</a></code> | <code>string</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeam.property.tfResourceType"></a>

```typescript
public readonly tfResourceType: string;
```

- *Type:* string

---

## Structs <a name="Structs" id="Structs"></a>

### DataOpsgenieTeamConfig <a name="DataOpsgenieTeamConfig" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.Initializer"></a>

```typescript
import { dataOpsgenieTeam } from 'rhizo-co-terraform-provider-opsgenie'

const dataOpsgenieTeamConfig: dataOpsgenieTeam.DataOpsgenieTeamConfig = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.connection">connection</a></code> | <code>cdktf.SSHProvisionerConnection \| cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.count">count</a></code> | <code>number \| cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.dependsOn">dependsOn</a></code> | <code>cdktf.ITerraformDependable[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.forEach">forEach</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.provisioners">provisioners</a></code> | <code>cdktf.FileProvisioner \| cdktf.LocalExecProvisioner \| cdktf.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.name">name</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/team#name DataOpsgenieTeam#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.description">description</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/team#description DataOpsgenieTeam#description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.id">id</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/team#id DataOpsgenieTeam#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.member">member</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMember">DataOpsgenieTeamMember</a>[]</code> | member block. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.connection"></a>

```typescript
public readonly connection: SSHProvisionerConnection | WinrmProvisionerConnection;
```

- *Type:* cdktf.SSHProvisionerConnection | cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.count"></a>

```typescript
public readonly count: number | TerraformCount;
```

- *Type:* number | cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.dependsOn"></a>

```typescript
public readonly dependsOn: ITerraformDependable[];
```

- *Type:* cdktf.ITerraformDependable[]

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.forEach"></a>

```typescript
public readonly forEach: ITerraformIterator;
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.provisioners"></a>

```typescript
public readonly provisioners: FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner[];
```

- *Type:* cdktf.FileProvisioner | cdktf.LocalExecProvisioner | cdktf.RemoteExecProvisioner[]

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.name"></a>

```typescript
public readonly name: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/team#name DataOpsgenieTeam#name}.

---

##### `description`<sup>Optional</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.description"></a>

```typescript
public readonly description: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/team#description DataOpsgenieTeam#description}.

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/team#id DataOpsgenieTeam#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `member`<sup>Optional</sup> <a name="member" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamConfig.property.member"></a>

```typescript
public readonly member: IResolvable | DataOpsgenieTeamMember[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMember">DataOpsgenieTeamMember</a>[]

member block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/team#member DataOpsgenieTeam#member}

---

### DataOpsgenieTeamMember <a name="DataOpsgenieTeamMember" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMember"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMember.Initializer"></a>

```typescript
import { dataOpsgenieTeam } from 'rhizo-co-terraform-provider-opsgenie'

const dataOpsgenieTeamMember: dataOpsgenieTeam.DataOpsgenieTeamMember = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMember.property.id">id</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/team#id DataOpsgenieTeam#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMember.property.role">role</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/team#role DataOpsgenieTeam#role}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMember.property.username">username</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/team#username DataOpsgenieTeam#username}. |

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMember.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/team#id DataOpsgenieTeam#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `role`<sup>Optional</sup> <a name="role" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMember.property.role"></a>

```typescript
public readonly role: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/team#role DataOpsgenieTeam#role}.

---

##### `username`<sup>Optional</sup> <a name="username" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMember.property.username"></a>

```typescript
public readonly username: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/team#username DataOpsgenieTeam#username}.

---

## Classes <a name="Classes" id="Classes"></a>

### DataOpsgenieTeamMemberList <a name="DataOpsgenieTeamMemberList" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.Initializer"></a>

```typescript
import { dataOpsgenieTeam } from 'rhizo-co-terraform-provider-opsgenie'

new dataOpsgenieTeam.DataOpsgenieTeamMemberList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.get"></a>

```typescript
public get(index: number): DataOpsgenieTeamMemberOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMember">DataOpsgenieTeamMember</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | DataOpsgenieTeamMember[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMember">DataOpsgenieTeamMember</a>[]

---


### DataOpsgenieTeamMemberOutputReference <a name="DataOpsgenieTeamMemberOutputReference" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.Initializer"></a>

```typescript
import { dataOpsgenieTeam } from 'rhizo-co-terraform-provider-opsgenie'

new dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.resetId">resetId</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.resetRole">resetRole</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.resetUsername">resetUsername</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetId` <a name="resetId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.resetId"></a>

```typescript
public resetId(): void
```

##### `resetRole` <a name="resetRole" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.resetRole"></a>

```typescript
public resetRole(): void
```

##### `resetUsername` <a name="resetUsername" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.resetUsername"></a>

```typescript
public resetUsername(): void
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.property.idInput">idInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.property.roleInput">roleInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.property.usernameInput">usernameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.property.id">id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.property.role">role</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.property.username">username</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMember">DataOpsgenieTeamMember</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `idInput`<sup>Optional</sup> <a name="idInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.property.idInput"></a>

```typescript
public readonly idInput: string;
```

- *Type:* string

---

##### `roleInput`<sup>Optional</sup> <a name="roleInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.property.roleInput"></a>

```typescript
public readonly roleInput: string;
```

- *Type:* string

---

##### `usernameInput`<sup>Optional</sup> <a name="usernameInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.property.usernameInput"></a>

```typescript
public readonly usernameInput: string;
```

- *Type:* string

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

---

##### `role`<sup>Required</sup> <a name="role" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.property.role"></a>

```typescript
public readonly role: string;
```

- *Type:* string

---

##### `username`<sup>Required</sup> <a name="username" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.property.username"></a>

```typescript
public readonly username: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMemberOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | DataOpsgenieTeamMember;
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieTeam.DataOpsgenieTeamMember">DataOpsgenieTeamMember</a>

---



