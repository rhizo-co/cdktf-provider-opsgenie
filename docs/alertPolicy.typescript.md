# `opsgenie_alert_policy`

Refer to the Terraform Registory for docs: [`opsgenie_alert_policy`](https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy).

# `alertPolicy` Submodule <a name="`alertPolicy` Submodule" id="rhizo-co-terraform-provider-opsgenie.alertPolicy"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### AlertPolicy <a name="AlertPolicy" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy"></a>

Represents a {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy opsgenie_alert_policy}.

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer"></a>

```typescript
import { alertPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new alertPolicy.AlertPolicy(scope: Construct, id: string, config: AlertPolicyConfig)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.id">id</a></code> | <code>string</code> | The scoped construct ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.config">config</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig">AlertPolicyConfig</a></code> | *No description.* |

---

##### `scope`<sup>Required</sup> <a name="scope" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.id"></a>

- *Type:* string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Required</sup> <a name="config" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.Initializer.parameter.config"></a>

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig">AlertPolicyConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.toString">toString</a></code> | Returns a string representation of this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.addOverride">addOverride</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.overrideLogicalId">overrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetOverrideLogicalId">resetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.toMetadata">toMetadata</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.toTerraform">toTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.putFilter">putFilter</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.putResponders">putResponders</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.putTimeRestriction">putTimeRestriction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetActions">resetActions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetAlertDescription">resetAlertDescription</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetAlias">resetAlias</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetContinuePolicy">resetContinuePolicy</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetEnabled">resetEnabled</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetEntity">resetEntity</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetFilter">resetFilter</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetId">resetId</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetIgnoreOriginalActions">resetIgnoreOriginalActions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetIgnoreOriginalDetails">resetIgnoreOriginalDetails</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetIgnoreOriginalResponders">resetIgnoreOriginalResponders</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetIgnoreOriginalTags">resetIgnoreOriginalTags</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetPolicyDescription">resetPolicyDescription</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetPriority">resetPriority</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetResponders">resetResponders</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetSource">resetSource</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetTags">resetTags</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetTeamId">resetTeamId</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetTimeRestriction">resetTimeRestriction</a></code> | *No description.* |

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.toString"></a>

```typescript
public toString(): string
```

Returns a string representation of this construct.

##### `addOverride` <a name="addOverride" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.addOverride"></a>

```typescript
public addOverride(path: string, value: any): void
```

###### `path`<sup>Required</sup> <a name="path" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.addOverride.parameter.path"></a>

- *Type:* string

---

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.addOverride.parameter.value"></a>

- *Type:* any

---

##### `overrideLogicalId` <a name="overrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.overrideLogicalId"></a>

```typescript
public overrideLogicalId(newLogicalId: string): void
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* string

The new logical ID to use for this stack element.

---

##### `resetOverrideLogicalId` <a name="resetOverrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetOverrideLogicalId"></a>

```typescript
public resetOverrideLogicalId(): void
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `toMetadata` <a name="toMetadata" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.toMetadata"></a>

```typescript
public toMetadata(): any
```

##### `toTerraform` <a name="toTerraform" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.toTerraform"></a>

```typescript
public toTerraform(): any
```

Adds this resource to the terraform JSON output.

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `putFilter` <a name="putFilter" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.putFilter"></a>

```typescript
public putFilter(value: IResolvable | AlertPolicyFilter[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.putFilter.parameter.value"></a>

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilter">AlertPolicyFilter</a>[]

---

##### `putResponders` <a name="putResponders" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.putResponders"></a>

```typescript
public putResponders(value: IResolvable | AlertPolicyResponders[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.putResponders.parameter.value"></a>

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders">AlertPolicyResponders</a>[]

---

##### `putTimeRestriction` <a name="putTimeRestriction" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.putTimeRestriction"></a>

```typescript
public putTimeRestriction(value: IResolvable | AlertPolicyTimeRestriction[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.putTimeRestriction.parameter.value"></a>

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction">AlertPolicyTimeRestriction</a>[]

---

##### `resetActions` <a name="resetActions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetActions"></a>

```typescript
public resetActions(): void
```

##### `resetAlertDescription` <a name="resetAlertDescription" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetAlertDescription"></a>

```typescript
public resetAlertDescription(): void
```

##### `resetAlias` <a name="resetAlias" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetAlias"></a>

```typescript
public resetAlias(): void
```

##### `resetContinuePolicy` <a name="resetContinuePolicy" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetContinuePolicy"></a>

```typescript
public resetContinuePolicy(): void
```

##### `resetEnabled` <a name="resetEnabled" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetEnabled"></a>

```typescript
public resetEnabled(): void
```

##### `resetEntity` <a name="resetEntity" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetEntity"></a>

```typescript
public resetEntity(): void
```

##### `resetFilter` <a name="resetFilter" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetFilter"></a>

```typescript
public resetFilter(): void
```

##### `resetId` <a name="resetId" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetId"></a>

```typescript
public resetId(): void
```

##### `resetIgnoreOriginalActions` <a name="resetIgnoreOriginalActions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetIgnoreOriginalActions"></a>

```typescript
public resetIgnoreOriginalActions(): void
```

##### `resetIgnoreOriginalDetails` <a name="resetIgnoreOriginalDetails" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetIgnoreOriginalDetails"></a>

```typescript
public resetIgnoreOriginalDetails(): void
```

##### `resetIgnoreOriginalResponders` <a name="resetIgnoreOriginalResponders" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetIgnoreOriginalResponders"></a>

```typescript
public resetIgnoreOriginalResponders(): void
```

##### `resetIgnoreOriginalTags` <a name="resetIgnoreOriginalTags" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetIgnoreOriginalTags"></a>

```typescript
public resetIgnoreOriginalTags(): void
```

##### `resetPolicyDescription` <a name="resetPolicyDescription" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetPolicyDescription"></a>

```typescript
public resetPolicyDescription(): void
```

##### `resetPriority` <a name="resetPriority" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetPriority"></a>

```typescript
public resetPriority(): void
```

##### `resetResponders` <a name="resetResponders" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetResponders"></a>

```typescript
public resetResponders(): void
```

##### `resetSource` <a name="resetSource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetSource"></a>

```typescript
public resetSource(): void
```

##### `resetTags` <a name="resetTags" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetTags"></a>

```typescript
public resetTags(): void
```

##### `resetTeamId` <a name="resetTeamId" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetTeamId"></a>

```typescript
public resetTeamId(): void
```

##### `resetTimeRestriction` <a name="resetTimeRestriction" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.resetTimeRestriction"></a>

```typescript
public resetTimeRestriction(): void
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.isConstruct">isConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.isTerraformElement">isTerraformElement</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.isTerraformResource">isTerraformResource</a></code> | *No description.* |

---

##### `isConstruct` <a name="isConstruct" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.isConstruct"></a>

```typescript
import { alertPolicy } from 'rhizo-co-terraform-provider-opsgenie'

alertPolicy.AlertPolicy.isConstruct(x: any)
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

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.isConstruct.parameter.x"></a>

- *Type:* any

Any object.

---

##### `isTerraformElement` <a name="isTerraformElement" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.isTerraformElement"></a>

```typescript
import { alertPolicy } from 'rhizo-co-terraform-provider-opsgenie'

alertPolicy.AlertPolicy.isTerraformElement(x: any)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.isTerraformElement.parameter.x"></a>

- *Type:* any

---

##### `isTerraformResource` <a name="isTerraformResource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.isTerraformResource"></a>

```typescript
import { alertPolicy } from 'rhizo-co-terraform-provider-opsgenie'

alertPolicy.AlertPolicy.isTerraformResource(x: any)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.isTerraformResource.parameter.x"></a>

- *Type:* any

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.node">node</a></code> | <code>constructs.Node</code> | The tree node. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.cdktfStack">cdktfStack</a></code> | <code>cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.friendlyUniqueId">friendlyUniqueId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.terraformMetaArguments">terraformMetaArguments</a></code> | <code>{[ key: string ]: any}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.terraformResourceType">terraformResourceType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.terraformGeneratorMetadata">terraformGeneratorMetadata</a></code> | <code>cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.connection">connection</a></code> | <code>cdktf.SSHProvisionerConnection \| cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.count">count</a></code> | <code>number \| cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.dependsOn">dependsOn</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.forEach">forEach</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.provisioners">provisioners</a></code> | <code>cdktf.FileProvisioner \| cdktf.LocalExecProvisioner \| cdktf.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.filter">filter</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList">AlertPolicyFilterList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.responders">responders</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList">AlertPolicyRespondersList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.timeRestriction">timeRestriction</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList">AlertPolicyTimeRestrictionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.actionsInput">actionsInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.alertDescriptionInput">alertDescriptionInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.aliasInput">aliasInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.continuePolicyInput">continuePolicyInput</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.enabledInput">enabledInput</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.entityInput">entityInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.filterInput">filterInput</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilter">AlertPolicyFilter</a>[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.idInput">idInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalActionsInput">ignoreOriginalActionsInput</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalDetailsInput">ignoreOriginalDetailsInput</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalRespondersInput">ignoreOriginalRespondersInput</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalTagsInput">ignoreOriginalTagsInput</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.messageInput">messageInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.nameInput">nameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.policyDescriptionInput">policyDescriptionInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.priorityInput">priorityInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.respondersInput">respondersInput</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders">AlertPolicyResponders</a>[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.sourceInput">sourceInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.tagsInput">tagsInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.teamIdInput">teamIdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.timeRestrictionInput">timeRestrictionInput</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction">AlertPolicyTimeRestriction</a>[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.actions">actions</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.alertDescription">alertDescription</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.alias">alias</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.continuePolicy">continuePolicy</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.enabled">enabled</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.entity">entity</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.id">id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalActions">ignoreOriginalActions</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalDetails">ignoreOriginalDetails</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalResponders">ignoreOriginalResponders</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalTags">ignoreOriginalTags</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.message">message</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.name">name</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.policyDescription">policyDescription</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.priority">priority</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.source">source</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.tags">tags</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.teamId">teamId</a></code> | <code>string</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.node"></a>

```typescript
public readonly node: Node;
```

- *Type:* constructs.Node

The tree node.

---

##### `cdktfStack`<sup>Required</sup> <a name="cdktfStack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.cdktfStack"></a>

```typescript
public readonly cdktfStack: TerraformStack;
```

- *Type:* cdktf.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `friendlyUniqueId`<sup>Required</sup> <a name="friendlyUniqueId" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.friendlyUniqueId"></a>

```typescript
public readonly friendlyUniqueId: string;
```

- *Type:* string

---

##### `terraformMetaArguments`<sup>Required</sup> <a name="terraformMetaArguments" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.terraformMetaArguments"></a>

```typescript
public readonly terraformMetaArguments: {[ key: string ]: any};
```

- *Type:* {[ key: string ]: any}

---

##### `terraformResourceType`<sup>Required</sup> <a name="terraformResourceType" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.terraformResourceType"></a>

```typescript
public readonly terraformResourceType: string;
```

- *Type:* string

---

##### `terraformGeneratorMetadata`<sup>Optional</sup> <a name="terraformGeneratorMetadata" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.terraformGeneratorMetadata"></a>

```typescript
public readonly terraformGeneratorMetadata: TerraformProviderGeneratorMetadata;
```

- *Type:* cdktf.TerraformProviderGeneratorMetadata

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.connection"></a>

```typescript
public readonly connection: SSHProvisionerConnection | WinrmProvisionerConnection;
```

- *Type:* cdktf.SSHProvisionerConnection | cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.count"></a>

```typescript
public readonly count: number | TerraformCount;
```

- *Type:* number | cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.dependsOn"></a>

```typescript
public readonly dependsOn: string[];
```

- *Type:* string[]

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.forEach"></a>

```typescript
public readonly forEach: ITerraformIterator;
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.provisioners"></a>

```typescript
public readonly provisioners: FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner[];
```

- *Type:* cdktf.FileProvisioner | cdktf.LocalExecProvisioner | cdktf.RemoteExecProvisioner[]

---

##### `filter`<sup>Required</sup> <a name="filter" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.filter"></a>

```typescript
public readonly filter: AlertPolicyFilterList;
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList">AlertPolicyFilterList</a>

---

##### `responders`<sup>Required</sup> <a name="responders" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.responders"></a>

```typescript
public readonly responders: AlertPolicyRespondersList;
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList">AlertPolicyRespondersList</a>

---

##### `timeRestriction`<sup>Required</sup> <a name="timeRestriction" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.timeRestriction"></a>

```typescript
public readonly timeRestriction: AlertPolicyTimeRestrictionList;
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList">AlertPolicyTimeRestrictionList</a>

---

##### `actionsInput`<sup>Optional</sup> <a name="actionsInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.actionsInput"></a>

```typescript
public readonly actionsInput: string[];
```

- *Type:* string[]

---

##### `alertDescriptionInput`<sup>Optional</sup> <a name="alertDescriptionInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.alertDescriptionInput"></a>

```typescript
public readonly alertDescriptionInput: string;
```

- *Type:* string

---

##### `aliasInput`<sup>Optional</sup> <a name="aliasInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.aliasInput"></a>

```typescript
public readonly aliasInput: string;
```

- *Type:* string

---

##### `continuePolicyInput`<sup>Optional</sup> <a name="continuePolicyInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.continuePolicyInput"></a>

```typescript
public readonly continuePolicyInput: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `enabledInput`<sup>Optional</sup> <a name="enabledInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.enabledInput"></a>

```typescript
public readonly enabledInput: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `entityInput`<sup>Optional</sup> <a name="entityInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.entityInput"></a>

```typescript
public readonly entityInput: string;
```

- *Type:* string

---

##### `filterInput`<sup>Optional</sup> <a name="filterInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.filterInput"></a>

```typescript
public readonly filterInput: IResolvable | AlertPolicyFilter[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilter">AlertPolicyFilter</a>[]

---

##### `idInput`<sup>Optional</sup> <a name="idInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.idInput"></a>

```typescript
public readonly idInput: string;
```

- *Type:* string

---

##### `ignoreOriginalActionsInput`<sup>Optional</sup> <a name="ignoreOriginalActionsInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalActionsInput"></a>

```typescript
public readonly ignoreOriginalActionsInput: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `ignoreOriginalDetailsInput`<sup>Optional</sup> <a name="ignoreOriginalDetailsInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalDetailsInput"></a>

```typescript
public readonly ignoreOriginalDetailsInput: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `ignoreOriginalRespondersInput`<sup>Optional</sup> <a name="ignoreOriginalRespondersInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalRespondersInput"></a>

```typescript
public readonly ignoreOriginalRespondersInput: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `ignoreOriginalTagsInput`<sup>Optional</sup> <a name="ignoreOriginalTagsInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalTagsInput"></a>

```typescript
public readonly ignoreOriginalTagsInput: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `messageInput`<sup>Optional</sup> <a name="messageInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.messageInput"></a>

```typescript
public readonly messageInput: string;
```

- *Type:* string

---

##### `nameInput`<sup>Optional</sup> <a name="nameInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.nameInput"></a>

```typescript
public readonly nameInput: string;
```

- *Type:* string

---

##### `policyDescriptionInput`<sup>Optional</sup> <a name="policyDescriptionInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.policyDescriptionInput"></a>

```typescript
public readonly policyDescriptionInput: string;
```

- *Type:* string

---

##### `priorityInput`<sup>Optional</sup> <a name="priorityInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.priorityInput"></a>

```typescript
public readonly priorityInput: string;
```

- *Type:* string

---

##### `respondersInput`<sup>Optional</sup> <a name="respondersInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.respondersInput"></a>

```typescript
public readonly respondersInput: IResolvable | AlertPolicyResponders[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders">AlertPolicyResponders</a>[]

---

##### `sourceInput`<sup>Optional</sup> <a name="sourceInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.sourceInput"></a>

```typescript
public readonly sourceInput: string;
```

- *Type:* string

---

##### `tagsInput`<sup>Optional</sup> <a name="tagsInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.tagsInput"></a>

```typescript
public readonly tagsInput: string[];
```

- *Type:* string[]

---

##### `teamIdInput`<sup>Optional</sup> <a name="teamIdInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.teamIdInput"></a>

```typescript
public readonly teamIdInput: string;
```

- *Type:* string

---

##### `timeRestrictionInput`<sup>Optional</sup> <a name="timeRestrictionInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.timeRestrictionInput"></a>

```typescript
public readonly timeRestrictionInput: IResolvable | AlertPolicyTimeRestriction[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction">AlertPolicyTimeRestriction</a>[]

---

##### `actions`<sup>Required</sup> <a name="actions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.actions"></a>

```typescript
public readonly actions: string[];
```

- *Type:* string[]

---

##### `alertDescription`<sup>Required</sup> <a name="alertDescription" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.alertDescription"></a>

```typescript
public readonly alertDescription: string;
```

- *Type:* string

---

##### `alias`<sup>Required</sup> <a name="alias" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.alias"></a>

```typescript
public readonly alias: string;
```

- *Type:* string

---

##### `continuePolicy`<sup>Required</sup> <a name="continuePolicy" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.continuePolicy"></a>

```typescript
public readonly continuePolicy: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `enabled`<sup>Required</sup> <a name="enabled" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.enabled"></a>

```typescript
public readonly enabled: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `entity`<sup>Required</sup> <a name="entity" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.entity"></a>

```typescript
public readonly entity: string;
```

- *Type:* string

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

---

##### `ignoreOriginalActions`<sup>Required</sup> <a name="ignoreOriginalActions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalActions"></a>

```typescript
public readonly ignoreOriginalActions: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `ignoreOriginalDetails`<sup>Required</sup> <a name="ignoreOriginalDetails" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalDetails"></a>

```typescript
public readonly ignoreOriginalDetails: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `ignoreOriginalResponders`<sup>Required</sup> <a name="ignoreOriginalResponders" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalResponders"></a>

```typescript
public readonly ignoreOriginalResponders: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `ignoreOriginalTags`<sup>Required</sup> <a name="ignoreOriginalTags" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.ignoreOriginalTags"></a>

```typescript
public readonly ignoreOriginalTags: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `message`<sup>Required</sup> <a name="message" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.message"></a>

```typescript
public readonly message: string;
```

- *Type:* string

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.name"></a>

```typescript
public readonly name: string;
```

- *Type:* string

---

##### `policyDescription`<sup>Required</sup> <a name="policyDescription" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.policyDescription"></a>

```typescript
public readonly policyDescription: string;
```

- *Type:* string

---

##### `priority`<sup>Required</sup> <a name="priority" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.priority"></a>

```typescript
public readonly priority: string;
```

- *Type:* string

---

##### `source`<sup>Required</sup> <a name="source" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.source"></a>

```typescript
public readonly source: string;
```

- *Type:* string

---

##### `tags`<sup>Required</sup> <a name="tags" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.tags"></a>

```typescript
public readonly tags: string[];
```

- *Type:* string[]

---

##### `teamId`<sup>Required</sup> <a name="teamId" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.teamId"></a>

```typescript
public readonly teamId: string;
```

- *Type:* string

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.tfResourceType">tfResourceType</a></code> | <code>string</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicy.property.tfResourceType"></a>

```typescript
public readonly tfResourceType: string;
```

- *Type:* string

---

## Structs <a name="Structs" id="Structs"></a>

### AlertPolicyConfig <a name="AlertPolicyConfig" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.Initializer"></a>

```typescript
import { alertPolicy } from 'rhizo-co-terraform-provider-opsgenie'

const alertPolicyConfig: alertPolicy.AlertPolicyConfig = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.connection">connection</a></code> | <code>cdktf.SSHProvisionerConnection \| cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.count">count</a></code> | <code>number \| cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.dependsOn">dependsOn</a></code> | <code>cdktf.ITerraformDependable[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.forEach">forEach</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.provisioners">provisioners</a></code> | <code>cdktf.FileProvisioner \| cdktf.LocalExecProvisioner \| cdktf.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.message">message</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#message AlertPolicy#message}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.name">name</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#name AlertPolicy#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.actions">actions</a></code> | <code>string[]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#actions AlertPolicy#actions}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.alertDescription">alertDescription</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#alert_description AlertPolicy#alert_description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.alias">alias</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#alias AlertPolicy#alias}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.continuePolicy">continuePolicy</a></code> | <code>boolean \| cdktf.IResolvable</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#continue_policy AlertPolicy#continue_policy}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.enabled">enabled</a></code> | <code>boolean \| cdktf.IResolvable</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#enabled AlertPolicy#enabled}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.entity">entity</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#entity AlertPolicy#entity}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.filter">filter</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilter">AlertPolicyFilter</a>[]</code> | filter block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.id">id</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#id AlertPolicy#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.ignoreOriginalActions">ignoreOriginalActions</a></code> | <code>boolean \| cdktf.IResolvable</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#ignore_original_actions AlertPolicy#ignore_original_actions}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.ignoreOriginalDetails">ignoreOriginalDetails</a></code> | <code>boolean \| cdktf.IResolvable</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#ignore_original_details AlertPolicy#ignore_original_details}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.ignoreOriginalResponders">ignoreOriginalResponders</a></code> | <code>boolean \| cdktf.IResolvable</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#ignore_original_responders AlertPolicy#ignore_original_responders}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.ignoreOriginalTags">ignoreOriginalTags</a></code> | <code>boolean \| cdktf.IResolvable</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#ignore_original_tags AlertPolicy#ignore_original_tags}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.policyDescription">policyDescription</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#policy_description AlertPolicy#policy_description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.priority">priority</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#priority AlertPolicy#priority}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.responders">responders</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders">AlertPolicyResponders</a>[]</code> | responders block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.source">source</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#source AlertPolicy#source}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.tags">tags</a></code> | <code>string[]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#tags AlertPolicy#tags}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.teamId">teamId</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#team_id AlertPolicy#team_id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.timeRestriction">timeRestriction</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction">AlertPolicyTimeRestriction</a>[]</code> | time_restriction block. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.connection"></a>

```typescript
public readonly connection: SSHProvisionerConnection | WinrmProvisionerConnection;
```

- *Type:* cdktf.SSHProvisionerConnection | cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.count"></a>

```typescript
public readonly count: number | TerraformCount;
```

- *Type:* number | cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.dependsOn"></a>

```typescript
public readonly dependsOn: ITerraformDependable[];
```

- *Type:* cdktf.ITerraformDependable[]

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.forEach"></a>

```typescript
public readonly forEach: ITerraformIterator;
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.provisioners"></a>

```typescript
public readonly provisioners: FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner[];
```

- *Type:* cdktf.FileProvisioner | cdktf.LocalExecProvisioner | cdktf.RemoteExecProvisioner[]

---

##### `message`<sup>Required</sup> <a name="message" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.message"></a>

```typescript
public readonly message: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#message AlertPolicy#message}.

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.name"></a>

```typescript
public readonly name: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#name AlertPolicy#name}.

---

##### `actions`<sup>Optional</sup> <a name="actions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.actions"></a>

```typescript
public readonly actions: string[];
```

- *Type:* string[]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#actions AlertPolicy#actions}.

---

##### `alertDescription`<sup>Optional</sup> <a name="alertDescription" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.alertDescription"></a>

```typescript
public readonly alertDescription: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#alert_description AlertPolicy#alert_description}.

---

##### `alias`<sup>Optional</sup> <a name="alias" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.alias"></a>

```typescript
public readonly alias: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#alias AlertPolicy#alias}.

---

##### `continuePolicy`<sup>Optional</sup> <a name="continuePolicy" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.continuePolicy"></a>

```typescript
public readonly continuePolicy: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#continue_policy AlertPolicy#continue_policy}.

---

##### `enabled`<sup>Optional</sup> <a name="enabled" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.enabled"></a>

```typescript
public readonly enabled: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#enabled AlertPolicy#enabled}.

---

##### `entity`<sup>Optional</sup> <a name="entity" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.entity"></a>

```typescript
public readonly entity: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#entity AlertPolicy#entity}.

---

##### `filter`<sup>Optional</sup> <a name="filter" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.filter"></a>

```typescript
public readonly filter: IResolvable | AlertPolicyFilter[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilter">AlertPolicyFilter</a>[]

filter block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#filter AlertPolicy#filter}

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#id AlertPolicy#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `ignoreOriginalActions`<sup>Optional</sup> <a name="ignoreOriginalActions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.ignoreOriginalActions"></a>

```typescript
public readonly ignoreOriginalActions: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#ignore_original_actions AlertPolicy#ignore_original_actions}.

---

##### `ignoreOriginalDetails`<sup>Optional</sup> <a name="ignoreOriginalDetails" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.ignoreOriginalDetails"></a>

```typescript
public readonly ignoreOriginalDetails: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#ignore_original_details AlertPolicy#ignore_original_details}.

---

##### `ignoreOriginalResponders`<sup>Optional</sup> <a name="ignoreOriginalResponders" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.ignoreOriginalResponders"></a>

```typescript
public readonly ignoreOriginalResponders: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#ignore_original_responders AlertPolicy#ignore_original_responders}.

---

##### `ignoreOriginalTags`<sup>Optional</sup> <a name="ignoreOriginalTags" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.ignoreOriginalTags"></a>

```typescript
public readonly ignoreOriginalTags: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#ignore_original_tags AlertPolicy#ignore_original_tags}.

---

##### `policyDescription`<sup>Optional</sup> <a name="policyDescription" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.policyDescription"></a>

```typescript
public readonly policyDescription: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#policy_description AlertPolicy#policy_description}.

---

##### `priority`<sup>Optional</sup> <a name="priority" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.priority"></a>

```typescript
public readonly priority: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#priority AlertPolicy#priority}.

---

##### `responders`<sup>Optional</sup> <a name="responders" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.responders"></a>

```typescript
public readonly responders: IResolvable | AlertPolicyResponders[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders">AlertPolicyResponders</a>[]

responders block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#responders AlertPolicy#responders}

---

##### `source`<sup>Optional</sup> <a name="source" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.source"></a>

```typescript
public readonly source: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#source AlertPolicy#source}.

---

##### `tags`<sup>Optional</sup> <a name="tags" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.tags"></a>

```typescript
public readonly tags: string[];
```

- *Type:* string[]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#tags AlertPolicy#tags}.

---

##### `teamId`<sup>Optional</sup> <a name="teamId" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.teamId"></a>

```typescript
public readonly teamId: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#team_id AlertPolicy#team_id}.

---

##### `timeRestriction`<sup>Optional</sup> <a name="timeRestriction" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyConfig.property.timeRestriction"></a>

```typescript
public readonly timeRestriction: IResolvable | AlertPolicyTimeRestriction[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction">AlertPolicyTimeRestriction</a>[]

time_restriction block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#time_restriction AlertPolicy#time_restriction}

---

### AlertPolicyFilter <a name="AlertPolicyFilter" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilter"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilter.Initializer"></a>

```typescript
import { alertPolicy } from 'rhizo-co-terraform-provider-opsgenie'

const alertPolicyFilter: alertPolicy.AlertPolicyFilter = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilter.property.conditions">conditions</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions">AlertPolicyFilterConditions</a>[]</code> | conditions block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilter.property.type">type</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#type AlertPolicy#type}. |

---

##### `conditions`<sup>Optional</sup> <a name="conditions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilter.property.conditions"></a>

```typescript
public readonly conditions: IResolvable | AlertPolicyFilterConditions[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions">AlertPolicyFilterConditions</a>[]

conditions block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#conditions AlertPolicy#conditions}

---

##### `type`<sup>Optional</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilter.property.type"></a>

```typescript
public readonly type: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#type AlertPolicy#type}.

---

### AlertPolicyFilterConditions <a name="AlertPolicyFilterConditions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.Initializer"></a>

```typescript
import { alertPolicy } from 'rhizo-co-terraform-provider-opsgenie'

const alertPolicyFilterConditions: alertPolicy.AlertPolicyFilterConditions = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.property.field">field</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#field AlertPolicy#field}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.property.operation">operation</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#operation AlertPolicy#operation}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.property.expectedValue">expectedValue</a></code> | <code>string</code> | User defined value that will be compared with alert field according to the operation. Default value is empty string. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.property.key">key</a></code> | <code>string</code> | If 'field' is set as 'extra-properties', key could be used for key-value pair. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.property.not">not</a></code> | <code>boolean \| cdktf.IResolvable</code> | Indicates behaviour of the given operation. Default value is false. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.property.order">order</a></code> | <code>number</code> | Order of the condition in conditions list. |

---

##### `field`<sup>Required</sup> <a name="field" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.property.field"></a>

```typescript
public readonly field: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#field AlertPolicy#field}.

---

##### `operation`<sup>Required</sup> <a name="operation" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.property.operation"></a>

```typescript
public readonly operation: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#operation AlertPolicy#operation}.

---

##### `expectedValue`<sup>Optional</sup> <a name="expectedValue" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.property.expectedValue"></a>

```typescript
public readonly expectedValue: string;
```

- *Type:* string

User defined value that will be compared with alert field according to the operation. Default value is empty string.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#expected_value AlertPolicy#expected_value}

---

##### `key`<sup>Optional</sup> <a name="key" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.property.key"></a>

```typescript
public readonly key: string;
```

- *Type:* string

If 'field' is set as 'extra-properties', key could be used for key-value pair.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#key AlertPolicy#key}

---

##### `not`<sup>Optional</sup> <a name="not" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.property.not"></a>

```typescript
public readonly not: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

Indicates behaviour of the given operation. Default value is false.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#not AlertPolicy#not}

---

##### `order`<sup>Optional</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions.property.order"></a>

```typescript
public readonly order: number;
```

- *Type:* number

Order of the condition in conditions list.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#order AlertPolicy#order}

---

### AlertPolicyResponders <a name="AlertPolicyResponders" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders.Initializer"></a>

```typescript
import { alertPolicy } from 'rhizo-co-terraform-provider-opsgenie'

const alertPolicyResponders: alertPolicy.AlertPolicyResponders = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders.property.id">id</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#id AlertPolicy#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders.property.type">type</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#type AlertPolicy#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders.property.name">name</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#name AlertPolicy#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders.property.username">username</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#username AlertPolicy#username}. |

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#id AlertPolicy#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders.property.type"></a>

```typescript
public readonly type: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#type AlertPolicy#type}.

---

##### `name`<sup>Optional</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders.property.name"></a>

```typescript
public readonly name: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#name AlertPolicy#name}.

---

##### `username`<sup>Optional</sup> <a name="username" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders.property.username"></a>

```typescript
public readonly username: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#username AlertPolicy#username}.

---

### AlertPolicyTimeRestriction <a name="AlertPolicyTimeRestriction" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction.Initializer"></a>

```typescript
import { alertPolicy } from 'rhizo-co-terraform-provider-opsgenie'

const alertPolicyTimeRestriction: alertPolicy.AlertPolicyTimeRestriction = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction.property.type">type</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#type AlertPolicy#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction.property.restriction">restriction</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction">AlertPolicyTimeRestrictionRestriction</a>[]</code> | restriction block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction.property.restrictions">restrictions</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions">AlertPolicyTimeRestrictionRestrictions</a>[]</code> | restrictions block. |

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction.property.type"></a>

```typescript
public readonly type: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#type AlertPolicy#type}.

---

##### `restriction`<sup>Optional</sup> <a name="restriction" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction.property.restriction"></a>

```typescript
public readonly restriction: IResolvable | AlertPolicyTimeRestrictionRestriction[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction">AlertPolicyTimeRestrictionRestriction</a>[]

restriction block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#restriction AlertPolicy#restriction}

---

##### `restrictions`<sup>Optional</sup> <a name="restrictions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction.property.restrictions"></a>

```typescript
public readonly restrictions: IResolvable | AlertPolicyTimeRestrictionRestrictions[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions">AlertPolicyTimeRestrictionRestrictions</a>[]

restrictions block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#restrictions AlertPolicy#restrictions}

---

### AlertPolicyTimeRestrictionRestriction <a name="AlertPolicyTimeRestrictionRestriction" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction.Initializer"></a>

```typescript
import { alertPolicy } from 'rhizo-co-terraform-provider-opsgenie'

const alertPolicyTimeRestrictionRestriction: alertPolicy.AlertPolicyTimeRestrictionRestriction = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction.property.endHour">endHour</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#end_hour AlertPolicy#end_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction.property.endMin">endMin</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#end_min AlertPolicy#end_min}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction.property.startHour">startHour</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#start_hour AlertPolicy#start_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction.property.startMin">startMin</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#start_min AlertPolicy#start_min}. |

---

##### `endHour`<sup>Required</sup> <a name="endHour" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction.property.endHour"></a>

```typescript
public readonly endHour: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#end_hour AlertPolicy#end_hour}.

---

##### `endMin`<sup>Required</sup> <a name="endMin" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction.property.endMin"></a>

```typescript
public readonly endMin: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#end_min AlertPolicy#end_min}.

---

##### `startHour`<sup>Required</sup> <a name="startHour" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction.property.startHour"></a>

```typescript
public readonly startHour: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#start_hour AlertPolicy#start_hour}.

---

##### `startMin`<sup>Required</sup> <a name="startMin" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction.property.startMin"></a>

```typescript
public readonly startMin: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#start_min AlertPolicy#start_min}.

---

### AlertPolicyTimeRestrictionRestrictions <a name="AlertPolicyTimeRestrictionRestrictions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.Initializer"></a>

```typescript
import { alertPolicy } from 'rhizo-co-terraform-provider-opsgenie'

const alertPolicyTimeRestrictionRestrictions: alertPolicy.AlertPolicyTimeRestrictionRestrictions = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.property.endDay">endDay</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#end_day AlertPolicy#end_day}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.property.endHour">endHour</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#end_hour AlertPolicy#end_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.property.endMin">endMin</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#end_min AlertPolicy#end_min}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.property.startDay">startDay</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#start_day AlertPolicy#start_day}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.property.startHour">startHour</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#start_hour AlertPolicy#start_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.property.startMin">startMin</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#start_min AlertPolicy#start_min}. |

---

##### `endDay`<sup>Required</sup> <a name="endDay" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.property.endDay"></a>

```typescript
public readonly endDay: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#end_day AlertPolicy#end_day}.

---

##### `endHour`<sup>Required</sup> <a name="endHour" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.property.endHour"></a>

```typescript
public readonly endHour: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#end_hour AlertPolicy#end_hour}.

---

##### `endMin`<sup>Required</sup> <a name="endMin" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.property.endMin"></a>

```typescript
public readonly endMin: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#end_min AlertPolicy#end_min}.

---

##### `startDay`<sup>Required</sup> <a name="startDay" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.property.startDay"></a>

```typescript
public readonly startDay: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#start_day AlertPolicy#start_day}.

---

##### `startHour`<sup>Required</sup> <a name="startHour" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.property.startHour"></a>

```typescript
public readonly startHour: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#start_hour AlertPolicy#start_hour}.

---

##### `startMin`<sup>Required</sup> <a name="startMin" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions.property.startMin"></a>

```typescript
public readonly startMin: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/alert_policy#start_min AlertPolicy#start_min}.

---

## Classes <a name="Classes" id="Classes"></a>

### AlertPolicyFilterConditionsList <a name="AlertPolicyFilterConditionsList" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.Initializer"></a>

```typescript
import { alertPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new alertPolicy.AlertPolicyFilterConditionsList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.get"></a>

```typescript
public get(index: number): AlertPolicyFilterConditionsOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions">AlertPolicyFilterConditions</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | AlertPolicyFilterConditions[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions">AlertPolicyFilterConditions</a>[]

---


### AlertPolicyFilterConditionsOutputReference <a name="AlertPolicyFilterConditionsOutputReference" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.Initializer"></a>

```typescript
import { alertPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new alertPolicy.AlertPolicyFilterConditionsOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.resetExpectedValue">resetExpectedValue</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.resetKey">resetKey</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.resetNot">resetNot</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.resetOrder">resetOrder</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetExpectedValue` <a name="resetExpectedValue" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.resetExpectedValue"></a>

```typescript
public resetExpectedValue(): void
```

##### `resetKey` <a name="resetKey" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.resetKey"></a>

```typescript
public resetKey(): void
```

##### `resetNot` <a name="resetNot" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.resetNot"></a>

```typescript
public resetNot(): void
```

##### `resetOrder` <a name="resetOrder" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.resetOrder"></a>

```typescript
public resetOrder(): void
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.expectedValueInput">expectedValueInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.fieldInput">fieldInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.keyInput">keyInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.notInput">notInput</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.operationInput">operationInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.orderInput">orderInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.expectedValue">expectedValue</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.field">field</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.key">key</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.not">not</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.operation">operation</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.order">order</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions">AlertPolicyFilterConditions</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `expectedValueInput`<sup>Optional</sup> <a name="expectedValueInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.expectedValueInput"></a>

```typescript
public readonly expectedValueInput: string;
```

- *Type:* string

---

##### `fieldInput`<sup>Optional</sup> <a name="fieldInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.fieldInput"></a>

```typescript
public readonly fieldInput: string;
```

- *Type:* string

---

##### `keyInput`<sup>Optional</sup> <a name="keyInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.keyInput"></a>

```typescript
public readonly keyInput: string;
```

- *Type:* string

---

##### `notInput`<sup>Optional</sup> <a name="notInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.notInput"></a>

```typescript
public readonly notInput: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `operationInput`<sup>Optional</sup> <a name="operationInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.operationInput"></a>

```typescript
public readonly operationInput: string;
```

- *Type:* string

---

##### `orderInput`<sup>Optional</sup> <a name="orderInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.orderInput"></a>

```typescript
public readonly orderInput: number;
```

- *Type:* number

---

##### `expectedValue`<sup>Required</sup> <a name="expectedValue" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.expectedValue"></a>

```typescript
public readonly expectedValue: string;
```

- *Type:* string

---

##### `field`<sup>Required</sup> <a name="field" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.field"></a>

```typescript
public readonly field: string;
```

- *Type:* string

---

##### `key`<sup>Required</sup> <a name="key" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.key"></a>

```typescript
public readonly key: string;
```

- *Type:* string

---

##### `not`<sup>Required</sup> <a name="not" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.not"></a>

```typescript
public readonly not: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `operation`<sup>Required</sup> <a name="operation" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.operation"></a>

```typescript
public readonly operation: string;
```

- *Type:* string

---

##### `order`<sup>Required</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.order"></a>

```typescript
public readonly order: number;
```

- *Type:* number

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | AlertPolicyFilterConditions;
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions">AlertPolicyFilterConditions</a>

---


### AlertPolicyFilterList <a name="AlertPolicyFilterList" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.Initializer"></a>

```typescript
import { alertPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new alertPolicy.AlertPolicyFilterList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.get"></a>

```typescript
public get(index: number): AlertPolicyFilterOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilter">AlertPolicyFilter</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | AlertPolicyFilter[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilter">AlertPolicyFilter</a>[]

---


### AlertPolicyFilterOutputReference <a name="AlertPolicyFilterOutputReference" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.Initializer"></a>

```typescript
import { alertPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new alertPolicy.AlertPolicyFilterOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.putConditions">putConditions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.resetConditions">resetConditions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.resetType">resetType</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `putConditions` <a name="putConditions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.putConditions"></a>

```typescript
public putConditions(value: IResolvable | AlertPolicyFilterConditions[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.putConditions.parameter.value"></a>

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions">AlertPolicyFilterConditions</a>[]

---

##### `resetConditions` <a name="resetConditions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.resetConditions"></a>

```typescript
public resetConditions(): void
```

##### `resetType` <a name="resetType" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.resetType"></a>

```typescript
public resetType(): void
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.conditions">conditions</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList">AlertPolicyFilterConditionsList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.conditionsInput">conditionsInput</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions">AlertPolicyFilterConditions</a>[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.typeInput">typeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.type">type</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilter">AlertPolicyFilter</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `conditions`<sup>Required</sup> <a name="conditions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.conditions"></a>

```typescript
public readonly conditions: AlertPolicyFilterConditionsList;
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditionsList">AlertPolicyFilterConditionsList</a>

---

##### `conditionsInput`<sup>Optional</sup> <a name="conditionsInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.conditionsInput"></a>

```typescript
public readonly conditionsInput: IResolvable | AlertPolicyFilterConditions[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterConditions">AlertPolicyFilterConditions</a>[]

---

##### `typeInput`<sup>Optional</sup> <a name="typeInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.typeInput"></a>

```typescript
public readonly typeInput: string;
```

- *Type:* string

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.type"></a>

```typescript
public readonly type: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilterOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | AlertPolicyFilter;
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyFilter">AlertPolicyFilter</a>

---


### AlertPolicyRespondersList <a name="AlertPolicyRespondersList" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.Initializer"></a>

```typescript
import { alertPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new alertPolicy.AlertPolicyRespondersList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.get"></a>

```typescript
public get(index: number): AlertPolicyRespondersOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders">AlertPolicyResponders</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | AlertPolicyResponders[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders">AlertPolicyResponders</a>[]

---


### AlertPolicyRespondersOutputReference <a name="AlertPolicyRespondersOutputReference" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.Initializer"></a>

```typescript
import { alertPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new alertPolicy.AlertPolicyRespondersOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.resetName">resetName</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.resetUsername">resetUsername</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetName` <a name="resetName" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.resetName"></a>

```typescript
public resetName(): void
```

##### `resetUsername` <a name="resetUsername" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.resetUsername"></a>

```typescript
public resetUsername(): void
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.idInput">idInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.nameInput">nameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.typeInput">typeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.usernameInput">usernameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.id">id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.name">name</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.type">type</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.username">username</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders">AlertPolicyResponders</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `idInput`<sup>Optional</sup> <a name="idInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.idInput"></a>

```typescript
public readonly idInput: string;
```

- *Type:* string

---

##### `nameInput`<sup>Optional</sup> <a name="nameInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.nameInput"></a>

```typescript
public readonly nameInput: string;
```

- *Type:* string

---

##### `typeInput`<sup>Optional</sup> <a name="typeInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.typeInput"></a>

```typescript
public readonly typeInput: string;
```

- *Type:* string

---

##### `usernameInput`<sup>Optional</sup> <a name="usernameInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.usernameInput"></a>

```typescript
public readonly usernameInput: string;
```

- *Type:* string

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.name"></a>

```typescript
public readonly name: string;
```

- *Type:* string

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.type"></a>

```typescript
public readonly type: string;
```

- *Type:* string

---

##### `username`<sup>Required</sup> <a name="username" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.username"></a>

```typescript
public readonly username: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyRespondersOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | AlertPolicyResponders;
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyResponders">AlertPolicyResponders</a>

---


### AlertPolicyTimeRestrictionList <a name="AlertPolicyTimeRestrictionList" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.Initializer"></a>

```typescript
import { alertPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new alertPolicy.AlertPolicyTimeRestrictionList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.get"></a>

```typescript
public get(index: number): AlertPolicyTimeRestrictionOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction">AlertPolicyTimeRestriction</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | AlertPolicyTimeRestriction[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction">AlertPolicyTimeRestriction</a>[]

---


### AlertPolicyTimeRestrictionOutputReference <a name="AlertPolicyTimeRestrictionOutputReference" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.Initializer"></a>

```typescript
import { alertPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new alertPolicy.AlertPolicyTimeRestrictionOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.putRestriction">putRestriction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.putRestrictions">putRestrictions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.resetRestriction">resetRestriction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.resetRestrictions">resetRestrictions</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `putRestriction` <a name="putRestriction" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.putRestriction"></a>

```typescript
public putRestriction(value: IResolvable | AlertPolicyTimeRestrictionRestriction[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.putRestriction.parameter.value"></a>

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction">AlertPolicyTimeRestrictionRestriction</a>[]

---

##### `putRestrictions` <a name="putRestrictions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.putRestrictions"></a>

```typescript
public putRestrictions(value: IResolvable | AlertPolicyTimeRestrictionRestrictions[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.putRestrictions.parameter.value"></a>

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions">AlertPolicyTimeRestrictionRestrictions</a>[]

---

##### `resetRestriction` <a name="resetRestriction" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.resetRestriction"></a>

```typescript
public resetRestriction(): void
```

##### `resetRestrictions` <a name="resetRestrictions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.resetRestrictions"></a>

```typescript
public resetRestrictions(): void
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.restriction">restriction</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList">AlertPolicyTimeRestrictionRestrictionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.restrictions">restrictions</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList">AlertPolicyTimeRestrictionRestrictionsList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.restrictionInput">restrictionInput</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction">AlertPolicyTimeRestrictionRestriction</a>[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.restrictionsInput">restrictionsInput</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions">AlertPolicyTimeRestrictionRestrictions</a>[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.typeInput">typeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.type">type</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction">AlertPolicyTimeRestriction</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `restriction`<sup>Required</sup> <a name="restriction" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.restriction"></a>

```typescript
public readonly restriction: AlertPolicyTimeRestrictionRestrictionList;
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList">AlertPolicyTimeRestrictionRestrictionList</a>

---

##### `restrictions`<sup>Required</sup> <a name="restrictions" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.restrictions"></a>

```typescript
public readonly restrictions: AlertPolicyTimeRestrictionRestrictionsList;
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList">AlertPolicyTimeRestrictionRestrictionsList</a>

---

##### `restrictionInput`<sup>Optional</sup> <a name="restrictionInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.restrictionInput"></a>

```typescript
public readonly restrictionInput: IResolvable | AlertPolicyTimeRestrictionRestriction[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction">AlertPolicyTimeRestrictionRestriction</a>[]

---

##### `restrictionsInput`<sup>Optional</sup> <a name="restrictionsInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.restrictionsInput"></a>

```typescript
public readonly restrictionsInput: IResolvable | AlertPolicyTimeRestrictionRestrictions[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions">AlertPolicyTimeRestrictionRestrictions</a>[]

---

##### `typeInput`<sup>Optional</sup> <a name="typeInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.typeInput"></a>

```typescript
public readonly typeInput: string;
```

- *Type:* string

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.type"></a>

```typescript
public readonly type: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | AlertPolicyTimeRestriction;
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestriction">AlertPolicyTimeRestriction</a>

---


### AlertPolicyTimeRestrictionRestrictionList <a name="AlertPolicyTimeRestrictionRestrictionList" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.Initializer"></a>

```typescript
import { alertPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new alertPolicy.AlertPolicyTimeRestrictionRestrictionList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.get"></a>

```typescript
public get(index: number): AlertPolicyTimeRestrictionRestrictionOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction">AlertPolicyTimeRestrictionRestriction</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | AlertPolicyTimeRestrictionRestriction[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction">AlertPolicyTimeRestrictionRestriction</a>[]

---


### AlertPolicyTimeRestrictionRestrictionOutputReference <a name="AlertPolicyTimeRestrictionRestrictionOutputReference" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.Initializer"></a>

```typescript
import { alertPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.endHourInput">endHourInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.endMinInput">endMinInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.startHourInput">startHourInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.startMinInput">startMinInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.endHour">endHour</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.endMin">endMin</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.startHour">startHour</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.startMin">startMin</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction">AlertPolicyTimeRestrictionRestriction</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `endHourInput`<sup>Optional</sup> <a name="endHourInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.endHourInput"></a>

```typescript
public readonly endHourInput: number;
```

- *Type:* number

---

##### `endMinInput`<sup>Optional</sup> <a name="endMinInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.endMinInput"></a>

```typescript
public readonly endMinInput: number;
```

- *Type:* number

---

##### `startHourInput`<sup>Optional</sup> <a name="startHourInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.startHourInput"></a>

```typescript
public readonly startHourInput: number;
```

- *Type:* number

---

##### `startMinInput`<sup>Optional</sup> <a name="startMinInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.startMinInput"></a>

```typescript
public readonly startMinInput: number;
```

- *Type:* number

---

##### `endHour`<sup>Required</sup> <a name="endHour" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.endHour"></a>

```typescript
public readonly endHour: number;
```

- *Type:* number

---

##### `endMin`<sup>Required</sup> <a name="endMin" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.endMin"></a>

```typescript
public readonly endMin: number;
```

- *Type:* number

---

##### `startHour`<sup>Required</sup> <a name="startHour" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.startHour"></a>

```typescript
public readonly startHour: number;
```

- *Type:* number

---

##### `startMin`<sup>Required</sup> <a name="startMin" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.startMin"></a>

```typescript
public readonly startMin: number;
```

- *Type:* number

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | AlertPolicyTimeRestrictionRestriction;
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestriction">AlertPolicyTimeRestrictionRestriction</a>

---


### AlertPolicyTimeRestrictionRestrictionsList <a name="AlertPolicyTimeRestrictionRestrictionsList" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.Initializer"></a>

```typescript
import { alertPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new alertPolicy.AlertPolicyTimeRestrictionRestrictionsList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.get"></a>

```typescript
public get(index: number): AlertPolicyTimeRestrictionRestrictionsOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions">AlertPolicyTimeRestrictionRestrictions</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | AlertPolicyTimeRestrictionRestrictions[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions">AlertPolicyTimeRestrictionRestrictions</a>[]

---


### AlertPolicyTimeRestrictionRestrictionsOutputReference <a name="AlertPolicyTimeRestrictionRestrictionsOutputReference" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.Initializer"></a>

```typescript
import { alertPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.endDayInput">endDayInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.endHourInput">endHourInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.endMinInput">endMinInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.startDayInput">startDayInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.startHourInput">startHourInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.startMinInput">startMinInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.endDay">endDay</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.endHour">endHour</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.endMin">endMin</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.startDay">startDay</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.startHour">startHour</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.startMin">startMin</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions">AlertPolicyTimeRestrictionRestrictions</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `endDayInput`<sup>Optional</sup> <a name="endDayInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.endDayInput"></a>

```typescript
public readonly endDayInput: string;
```

- *Type:* string

---

##### `endHourInput`<sup>Optional</sup> <a name="endHourInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.endHourInput"></a>

```typescript
public readonly endHourInput: number;
```

- *Type:* number

---

##### `endMinInput`<sup>Optional</sup> <a name="endMinInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.endMinInput"></a>

```typescript
public readonly endMinInput: number;
```

- *Type:* number

---

##### `startDayInput`<sup>Optional</sup> <a name="startDayInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.startDayInput"></a>

```typescript
public readonly startDayInput: string;
```

- *Type:* string

---

##### `startHourInput`<sup>Optional</sup> <a name="startHourInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.startHourInput"></a>

```typescript
public readonly startHourInput: number;
```

- *Type:* number

---

##### `startMinInput`<sup>Optional</sup> <a name="startMinInput" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.startMinInput"></a>

```typescript
public readonly startMinInput: number;
```

- *Type:* number

---

##### `endDay`<sup>Required</sup> <a name="endDay" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.endDay"></a>

```typescript
public readonly endDay: string;
```

- *Type:* string

---

##### `endHour`<sup>Required</sup> <a name="endHour" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.endHour"></a>

```typescript
public readonly endHour: number;
```

- *Type:* number

---

##### `endMin`<sup>Required</sup> <a name="endMin" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.endMin"></a>

```typescript
public readonly endMin: number;
```

- *Type:* number

---

##### `startDay`<sup>Required</sup> <a name="startDay" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.startDay"></a>

```typescript
public readonly startDay: string;
```

- *Type:* string

---

##### `startHour`<sup>Required</sup> <a name="startHour" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.startHour"></a>

```typescript
public readonly startHour: number;
```

- *Type:* number

---

##### `startMin`<sup>Required</sup> <a name="startMin" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.startMin"></a>

```typescript
public readonly startMin: number;
```

- *Type:* number

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictionsOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | AlertPolicyTimeRestrictionRestrictions;
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.alertPolicy.AlertPolicyTimeRestrictionRestrictions">AlertPolicyTimeRestrictionRestrictions</a>

---



