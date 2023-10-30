# `opsgenie_notification_policy`

Refer to the Terraform Registory for docs: [`opsgenie_notification_policy`](https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy).

# `notificationPolicy` Submodule <a name="`notificationPolicy` Submodule" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### NotificationPolicy <a name="NotificationPolicy" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy"></a>

Represents a {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy opsgenie_notification_policy}.

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new notificationPolicy.NotificationPolicy(scope: Construct, id: string, config: NotificationPolicyConfig)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.id">id</a></code> | <code>string</code> | The scoped construct ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.config">config</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig">NotificationPolicyConfig</a></code> | *No description.* |

---

##### `scope`<sup>Required</sup> <a name="scope" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.id"></a>

- *Type:* string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Required</sup> <a name="config" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.config"></a>

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig">NotificationPolicyConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.toString">toString</a></code> | Returns a string representation of this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.addOverride">addOverride</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.overrideLogicalId">overrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetOverrideLogicalId">resetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.toMetadata">toMetadata</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.toTerraform">toTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putAutoCloseAction">putAutoCloseAction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putAutoRestartAction">putAutoRestartAction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putDeDuplicationAction">putDeDuplicationAction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putDelayAction">putDelayAction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putFilter">putFilter</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putTimeRestriction">putTimeRestriction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetAutoCloseAction">resetAutoCloseAction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetAutoRestartAction">resetAutoRestartAction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetDeDuplicationAction">resetDeDuplicationAction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetDelayAction">resetDelayAction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetEnabled">resetEnabled</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetId">resetId</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetPolicyDescription">resetPolicyDescription</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetSuppress">resetSuppress</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetTimeRestriction">resetTimeRestriction</a></code> | *No description.* |

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.toString"></a>

```typescript
public toString(): string
```

Returns a string representation of this construct.

##### `addOverride` <a name="addOverride" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.addOverride"></a>

```typescript
public addOverride(path: string, value: any): void
```

###### `path`<sup>Required</sup> <a name="path" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.addOverride.parameter.path"></a>

- *Type:* string

---

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.addOverride.parameter.value"></a>

- *Type:* any

---

##### `overrideLogicalId` <a name="overrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.overrideLogicalId"></a>

```typescript
public overrideLogicalId(newLogicalId: string): void
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* string

The new logical ID to use for this stack element.

---

##### `resetOverrideLogicalId` <a name="resetOverrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetOverrideLogicalId"></a>

```typescript
public resetOverrideLogicalId(): void
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `toMetadata` <a name="toMetadata" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.toMetadata"></a>

```typescript
public toMetadata(): any
```

##### `toTerraform` <a name="toTerraform" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.toTerraform"></a>

```typescript
public toTerraform(): any
```

Adds this resource to the terraform JSON output.

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `putAutoCloseAction` <a name="putAutoCloseAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putAutoCloseAction"></a>

```typescript
public putAutoCloseAction(value: IResolvable | NotificationPolicyAutoCloseAction[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putAutoCloseAction.parameter.value"></a>

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction">NotificationPolicyAutoCloseAction</a>[]

---

##### `putAutoRestartAction` <a name="putAutoRestartAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putAutoRestartAction"></a>

```typescript
public putAutoRestartAction(value: IResolvable | NotificationPolicyAutoRestartAction[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putAutoRestartAction.parameter.value"></a>

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction">NotificationPolicyAutoRestartAction</a>[]

---

##### `putDeDuplicationAction` <a name="putDeDuplicationAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putDeDuplicationAction"></a>

```typescript
public putDeDuplicationAction(value: IResolvable | NotificationPolicyDeDuplicationAction[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putDeDuplicationAction.parameter.value"></a>

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction">NotificationPolicyDeDuplicationAction</a>[]

---

##### `putDelayAction` <a name="putDelayAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putDelayAction"></a>

```typescript
public putDelayAction(value: IResolvable | NotificationPolicyDelayAction[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putDelayAction.parameter.value"></a>

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction">NotificationPolicyDelayAction</a>[]

---

##### `putFilter` <a name="putFilter" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putFilter"></a>

```typescript
public putFilter(value: IResolvable | NotificationPolicyFilter[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putFilter.parameter.value"></a>

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter">NotificationPolicyFilter</a>[]

---

##### `putTimeRestriction` <a name="putTimeRestriction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putTimeRestriction"></a>

```typescript
public putTimeRestriction(value: IResolvable | NotificationPolicyTimeRestriction[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putTimeRestriction.parameter.value"></a>

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction">NotificationPolicyTimeRestriction</a>[]

---

##### `resetAutoCloseAction` <a name="resetAutoCloseAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetAutoCloseAction"></a>

```typescript
public resetAutoCloseAction(): void
```

##### `resetAutoRestartAction` <a name="resetAutoRestartAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetAutoRestartAction"></a>

```typescript
public resetAutoRestartAction(): void
```

##### `resetDeDuplicationAction` <a name="resetDeDuplicationAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetDeDuplicationAction"></a>

```typescript
public resetDeDuplicationAction(): void
```

##### `resetDelayAction` <a name="resetDelayAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetDelayAction"></a>

```typescript
public resetDelayAction(): void
```

##### `resetEnabled` <a name="resetEnabled" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetEnabled"></a>

```typescript
public resetEnabled(): void
```

##### `resetId` <a name="resetId" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetId"></a>

```typescript
public resetId(): void
```

##### `resetPolicyDescription` <a name="resetPolicyDescription" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetPolicyDescription"></a>

```typescript
public resetPolicyDescription(): void
```

##### `resetSuppress` <a name="resetSuppress" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetSuppress"></a>

```typescript
public resetSuppress(): void
```

##### `resetTimeRestriction` <a name="resetTimeRestriction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetTimeRestriction"></a>

```typescript
public resetTimeRestriction(): void
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.isConstruct">isConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.isTerraformElement">isTerraformElement</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.isTerraformResource">isTerraformResource</a></code> | *No description.* |

---

##### `isConstruct` <a name="isConstruct" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.isConstruct"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

notificationPolicy.NotificationPolicy.isConstruct(x: any)
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

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.isConstruct.parameter.x"></a>

- *Type:* any

Any object.

---

##### `isTerraformElement` <a name="isTerraformElement" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.isTerraformElement"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

notificationPolicy.NotificationPolicy.isTerraformElement(x: any)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.isTerraformElement.parameter.x"></a>

- *Type:* any

---

##### `isTerraformResource` <a name="isTerraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.isTerraformResource"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

notificationPolicy.NotificationPolicy.isTerraformResource(x: any)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.isTerraformResource.parameter.x"></a>

- *Type:* any

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.node">node</a></code> | <code>constructs.Node</code> | The tree node. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.cdktfStack">cdktfStack</a></code> | <code>cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.friendlyUniqueId">friendlyUniqueId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.terraformMetaArguments">terraformMetaArguments</a></code> | <code>{[ key: string ]: any}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.terraformResourceType">terraformResourceType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.terraformGeneratorMetadata">terraformGeneratorMetadata</a></code> | <code>cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.connection">connection</a></code> | <code>cdktf.SSHProvisionerConnection \| cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.count">count</a></code> | <code>number \| cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.dependsOn">dependsOn</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.forEach">forEach</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.provisioners">provisioners</a></code> | <code>cdktf.FileProvisioner \| cdktf.LocalExecProvisioner \| cdktf.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.autoCloseAction">autoCloseAction</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList">NotificationPolicyAutoCloseActionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.autoRestartAction">autoRestartAction</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList">NotificationPolicyAutoRestartActionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.deDuplicationAction">deDuplicationAction</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList">NotificationPolicyDeDuplicationActionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.delayAction">delayAction</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList">NotificationPolicyDelayActionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.filter">filter</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList">NotificationPolicyFilterList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.timeRestriction">timeRestriction</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList">NotificationPolicyTimeRestrictionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.autoCloseActionInput">autoCloseActionInput</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction">NotificationPolicyAutoCloseAction</a>[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.autoRestartActionInput">autoRestartActionInput</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction">NotificationPolicyAutoRestartAction</a>[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.deDuplicationActionInput">deDuplicationActionInput</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction">NotificationPolicyDeDuplicationAction</a>[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.delayActionInput">delayActionInput</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction">NotificationPolicyDelayAction</a>[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.enabledInput">enabledInput</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.filterInput">filterInput</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter">NotificationPolicyFilter</a>[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.idInput">idInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.nameInput">nameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.policyDescriptionInput">policyDescriptionInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.suppressInput">suppressInput</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.teamIdInput">teamIdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.timeRestrictionInput">timeRestrictionInput</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction">NotificationPolicyTimeRestriction</a>[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.enabled">enabled</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.id">id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.name">name</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.policyDescription">policyDescription</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.suppress">suppress</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.teamId">teamId</a></code> | <code>string</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.node"></a>

```typescript
public readonly node: Node;
```

- *Type:* constructs.Node

The tree node.

---

##### `cdktfStack`<sup>Required</sup> <a name="cdktfStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.cdktfStack"></a>

```typescript
public readonly cdktfStack: TerraformStack;
```

- *Type:* cdktf.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `friendlyUniqueId`<sup>Required</sup> <a name="friendlyUniqueId" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.friendlyUniqueId"></a>

```typescript
public readonly friendlyUniqueId: string;
```

- *Type:* string

---

##### `terraformMetaArguments`<sup>Required</sup> <a name="terraformMetaArguments" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.terraformMetaArguments"></a>

```typescript
public readonly terraformMetaArguments: {[ key: string ]: any};
```

- *Type:* {[ key: string ]: any}

---

##### `terraformResourceType`<sup>Required</sup> <a name="terraformResourceType" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.terraformResourceType"></a>

```typescript
public readonly terraformResourceType: string;
```

- *Type:* string

---

##### `terraformGeneratorMetadata`<sup>Optional</sup> <a name="terraformGeneratorMetadata" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.terraformGeneratorMetadata"></a>

```typescript
public readonly terraformGeneratorMetadata: TerraformProviderGeneratorMetadata;
```

- *Type:* cdktf.TerraformProviderGeneratorMetadata

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.connection"></a>

```typescript
public readonly connection: SSHProvisionerConnection | WinrmProvisionerConnection;
```

- *Type:* cdktf.SSHProvisionerConnection | cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.count"></a>

```typescript
public readonly count: number | TerraformCount;
```

- *Type:* number | cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.dependsOn"></a>

```typescript
public readonly dependsOn: string[];
```

- *Type:* string[]

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.forEach"></a>

```typescript
public readonly forEach: ITerraformIterator;
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.provisioners"></a>

```typescript
public readonly provisioners: FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner[];
```

- *Type:* cdktf.FileProvisioner | cdktf.LocalExecProvisioner | cdktf.RemoteExecProvisioner[]

---

##### `autoCloseAction`<sup>Required</sup> <a name="autoCloseAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.autoCloseAction"></a>

```typescript
public readonly autoCloseAction: NotificationPolicyAutoCloseActionList;
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList">NotificationPolicyAutoCloseActionList</a>

---

##### `autoRestartAction`<sup>Required</sup> <a name="autoRestartAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.autoRestartAction"></a>

```typescript
public readonly autoRestartAction: NotificationPolicyAutoRestartActionList;
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList">NotificationPolicyAutoRestartActionList</a>

---

##### `deDuplicationAction`<sup>Required</sup> <a name="deDuplicationAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.deDuplicationAction"></a>

```typescript
public readonly deDuplicationAction: NotificationPolicyDeDuplicationActionList;
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList">NotificationPolicyDeDuplicationActionList</a>

---

##### `delayAction`<sup>Required</sup> <a name="delayAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.delayAction"></a>

```typescript
public readonly delayAction: NotificationPolicyDelayActionList;
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList">NotificationPolicyDelayActionList</a>

---

##### `filter`<sup>Required</sup> <a name="filter" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.filter"></a>

```typescript
public readonly filter: NotificationPolicyFilterList;
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList">NotificationPolicyFilterList</a>

---

##### `timeRestriction`<sup>Required</sup> <a name="timeRestriction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.timeRestriction"></a>

```typescript
public readonly timeRestriction: NotificationPolicyTimeRestrictionList;
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList">NotificationPolicyTimeRestrictionList</a>

---

##### `autoCloseActionInput`<sup>Optional</sup> <a name="autoCloseActionInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.autoCloseActionInput"></a>

```typescript
public readonly autoCloseActionInput: IResolvable | NotificationPolicyAutoCloseAction[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction">NotificationPolicyAutoCloseAction</a>[]

---

##### `autoRestartActionInput`<sup>Optional</sup> <a name="autoRestartActionInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.autoRestartActionInput"></a>

```typescript
public readonly autoRestartActionInput: IResolvable | NotificationPolicyAutoRestartAction[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction">NotificationPolicyAutoRestartAction</a>[]

---

##### `deDuplicationActionInput`<sup>Optional</sup> <a name="deDuplicationActionInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.deDuplicationActionInput"></a>

```typescript
public readonly deDuplicationActionInput: IResolvable | NotificationPolicyDeDuplicationAction[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction">NotificationPolicyDeDuplicationAction</a>[]

---

##### `delayActionInput`<sup>Optional</sup> <a name="delayActionInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.delayActionInput"></a>

```typescript
public readonly delayActionInput: IResolvable | NotificationPolicyDelayAction[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction">NotificationPolicyDelayAction</a>[]

---

##### `enabledInput`<sup>Optional</sup> <a name="enabledInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.enabledInput"></a>

```typescript
public readonly enabledInput: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `filterInput`<sup>Optional</sup> <a name="filterInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.filterInput"></a>

```typescript
public readonly filterInput: IResolvable | NotificationPolicyFilter[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter">NotificationPolicyFilter</a>[]

---

##### `idInput`<sup>Optional</sup> <a name="idInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.idInput"></a>

```typescript
public readonly idInput: string;
```

- *Type:* string

---

##### `nameInput`<sup>Optional</sup> <a name="nameInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.nameInput"></a>

```typescript
public readonly nameInput: string;
```

- *Type:* string

---

##### `policyDescriptionInput`<sup>Optional</sup> <a name="policyDescriptionInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.policyDescriptionInput"></a>

```typescript
public readonly policyDescriptionInput: string;
```

- *Type:* string

---

##### `suppressInput`<sup>Optional</sup> <a name="suppressInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.suppressInput"></a>

```typescript
public readonly suppressInput: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `teamIdInput`<sup>Optional</sup> <a name="teamIdInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.teamIdInput"></a>

```typescript
public readonly teamIdInput: string;
```

- *Type:* string

---

##### `timeRestrictionInput`<sup>Optional</sup> <a name="timeRestrictionInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.timeRestrictionInput"></a>

```typescript
public readonly timeRestrictionInput: IResolvable | NotificationPolicyTimeRestriction[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction">NotificationPolicyTimeRestriction</a>[]

---

##### `enabled`<sup>Required</sup> <a name="enabled" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.enabled"></a>

```typescript
public readonly enabled: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.name"></a>

```typescript
public readonly name: string;
```

- *Type:* string

---

##### `policyDescription`<sup>Required</sup> <a name="policyDescription" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.policyDescription"></a>

```typescript
public readonly policyDescription: string;
```

- *Type:* string

---

##### `suppress`<sup>Required</sup> <a name="suppress" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.suppress"></a>

```typescript
public readonly suppress: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `teamId`<sup>Required</sup> <a name="teamId" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.teamId"></a>

```typescript
public readonly teamId: string;
```

- *Type:* string

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.tfResourceType">tfResourceType</a></code> | <code>string</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.tfResourceType"></a>

```typescript
public readonly tfResourceType: string;
```

- *Type:* string

---

## Structs <a name="Structs" id="Structs"></a>

### NotificationPolicyAutoCloseAction <a name="NotificationPolicyAutoCloseAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

const notificationPolicyAutoCloseAction: notificationPolicy.NotificationPolicyAutoCloseAction = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction.property.duration">duration</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration">NotificationPolicyAutoCloseActionDuration</a>[]</code> | duration block. |

---

##### `duration`<sup>Required</sup> <a name="duration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction.property.duration"></a>

```typescript
public readonly duration: IResolvable | NotificationPolicyAutoCloseActionDuration[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration">NotificationPolicyAutoCloseActionDuration</a>[]

duration block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#duration NotificationPolicy#duration}

---

### NotificationPolicyAutoCloseActionDuration <a name="NotificationPolicyAutoCloseActionDuration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

const notificationPolicyAutoCloseActionDuration: notificationPolicy.NotificationPolicyAutoCloseActionDuration = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration.property.timeAmount">timeAmount</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_amount NotificationPolicy#time_amount}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration.property.timeUnit">timeUnit</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_unit NotificationPolicy#time_unit}. |

---

##### `timeAmount`<sup>Required</sup> <a name="timeAmount" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration.property.timeAmount"></a>

```typescript
public readonly timeAmount: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_amount NotificationPolicy#time_amount}.

---

##### `timeUnit`<sup>Optional</sup> <a name="timeUnit" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration.property.timeUnit"></a>

```typescript
public readonly timeUnit: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_unit NotificationPolicy#time_unit}.

---

### NotificationPolicyAutoRestartAction <a name="NotificationPolicyAutoRestartAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

const notificationPolicyAutoRestartAction: notificationPolicy.NotificationPolicyAutoRestartAction = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction.property.duration">duration</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration">NotificationPolicyAutoRestartActionDuration</a>[]</code> | duration block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction.property.maxRepeatCount">maxRepeatCount</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#max_repeat_count NotificationPolicy#max_repeat_count}. |

---

##### `duration`<sup>Required</sup> <a name="duration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction.property.duration"></a>

```typescript
public readonly duration: IResolvable | NotificationPolicyAutoRestartActionDuration[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration">NotificationPolicyAutoRestartActionDuration</a>[]

duration block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#duration NotificationPolicy#duration}

---

##### `maxRepeatCount`<sup>Required</sup> <a name="maxRepeatCount" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction.property.maxRepeatCount"></a>

```typescript
public readonly maxRepeatCount: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#max_repeat_count NotificationPolicy#max_repeat_count}.

---

### NotificationPolicyAutoRestartActionDuration <a name="NotificationPolicyAutoRestartActionDuration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

const notificationPolicyAutoRestartActionDuration: notificationPolicy.NotificationPolicyAutoRestartActionDuration = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration.property.timeAmount">timeAmount</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_amount NotificationPolicy#time_amount}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration.property.timeUnit">timeUnit</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_unit NotificationPolicy#time_unit}. |

---

##### `timeAmount`<sup>Required</sup> <a name="timeAmount" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration.property.timeAmount"></a>

```typescript
public readonly timeAmount: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_amount NotificationPolicy#time_amount}.

---

##### `timeUnit`<sup>Optional</sup> <a name="timeUnit" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration.property.timeUnit"></a>

```typescript
public readonly timeUnit: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_unit NotificationPolicy#time_unit}.

---

### NotificationPolicyConfig <a name="NotificationPolicyConfig" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

const notificationPolicyConfig: notificationPolicy.NotificationPolicyConfig = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.connection">connection</a></code> | <code>cdktf.SSHProvisionerConnection \| cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.count">count</a></code> | <code>number \| cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.dependsOn">dependsOn</a></code> | <code>cdktf.ITerraformDependable[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.forEach">forEach</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.provisioners">provisioners</a></code> | <code>cdktf.FileProvisioner \| cdktf.LocalExecProvisioner \| cdktf.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.filter">filter</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter">NotificationPolicyFilter</a>[]</code> | filter block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.name">name</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#name NotificationPolicy#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.teamId">teamId</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#team_id NotificationPolicy#team_id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.autoCloseAction">autoCloseAction</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction">NotificationPolicyAutoCloseAction</a>[]</code> | auto_close_action block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.autoRestartAction">autoRestartAction</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction">NotificationPolicyAutoRestartAction</a>[]</code> | auto_restart_action block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.deDuplicationAction">deDuplicationAction</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction">NotificationPolicyDeDuplicationAction</a>[]</code> | de_duplication_action block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.delayAction">delayAction</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction">NotificationPolicyDelayAction</a>[]</code> | delay_action block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.enabled">enabled</a></code> | <code>boolean \| cdktf.IResolvable</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#enabled NotificationPolicy#enabled}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.id">id</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#id NotificationPolicy#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.policyDescription">policyDescription</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#policy_description NotificationPolicy#policy_description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.suppress">suppress</a></code> | <code>boolean \| cdktf.IResolvable</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#suppress NotificationPolicy#suppress}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.timeRestriction">timeRestriction</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction">NotificationPolicyTimeRestriction</a>[]</code> | time_restriction block. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.connection"></a>

```typescript
public readonly connection: SSHProvisionerConnection | WinrmProvisionerConnection;
```

- *Type:* cdktf.SSHProvisionerConnection | cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.count"></a>

```typescript
public readonly count: number | TerraformCount;
```

- *Type:* number | cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.dependsOn"></a>

```typescript
public readonly dependsOn: ITerraformDependable[];
```

- *Type:* cdktf.ITerraformDependable[]

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.forEach"></a>

```typescript
public readonly forEach: ITerraformIterator;
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.provisioners"></a>

```typescript
public readonly provisioners: FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner[];
```

- *Type:* cdktf.FileProvisioner | cdktf.LocalExecProvisioner | cdktf.RemoteExecProvisioner[]

---

##### `filter`<sup>Required</sup> <a name="filter" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.filter"></a>

```typescript
public readonly filter: IResolvable | NotificationPolicyFilter[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter">NotificationPolicyFilter</a>[]

filter block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#filter NotificationPolicy#filter}

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.name"></a>

```typescript
public readonly name: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#name NotificationPolicy#name}.

---

##### `teamId`<sup>Required</sup> <a name="teamId" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.teamId"></a>

```typescript
public readonly teamId: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#team_id NotificationPolicy#team_id}.

---

##### `autoCloseAction`<sup>Optional</sup> <a name="autoCloseAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.autoCloseAction"></a>

```typescript
public readonly autoCloseAction: IResolvable | NotificationPolicyAutoCloseAction[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction">NotificationPolicyAutoCloseAction</a>[]

auto_close_action block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#auto_close_action NotificationPolicy#auto_close_action}

---

##### `autoRestartAction`<sup>Optional</sup> <a name="autoRestartAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.autoRestartAction"></a>

```typescript
public readonly autoRestartAction: IResolvable | NotificationPolicyAutoRestartAction[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction">NotificationPolicyAutoRestartAction</a>[]

auto_restart_action block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#auto_restart_action NotificationPolicy#auto_restart_action}

---

##### `deDuplicationAction`<sup>Optional</sup> <a name="deDuplicationAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.deDuplicationAction"></a>

```typescript
public readonly deDuplicationAction: IResolvable | NotificationPolicyDeDuplicationAction[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction">NotificationPolicyDeDuplicationAction</a>[]

de_duplication_action block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#de_duplication_action NotificationPolicy#de_duplication_action}

---

##### `delayAction`<sup>Optional</sup> <a name="delayAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.delayAction"></a>

```typescript
public readonly delayAction: IResolvable | NotificationPolicyDelayAction[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction">NotificationPolicyDelayAction</a>[]

delay_action block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#delay_action NotificationPolicy#delay_action}

---

##### `enabled`<sup>Optional</sup> <a name="enabled" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.enabled"></a>

```typescript
public readonly enabled: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#enabled NotificationPolicy#enabled}.

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#id NotificationPolicy#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `policyDescription`<sup>Optional</sup> <a name="policyDescription" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.policyDescription"></a>

```typescript
public readonly policyDescription: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#policy_description NotificationPolicy#policy_description}.

---

##### `suppress`<sup>Optional</sup> <a name="suppress" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.suppress"></a>

```typescript
public readonly suppress: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#suppress NotificationPolicy#suppress}.

---

##### `timeRestriction`<sup>Optional</sup> <a name="timeRestriction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.timeRestriction"></a>

```typescript
public readonly timeRestriction: IResolvable | NotificationPolicyTimeRestriction[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction">NotificationPolicyTimeRestriction</a>[]

time_restriction block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_restriction NotificationPolicy#time_restriction}

---

### NotificationPolicyDeDuplicationAction <a name="NotificationPolicyDeDuplicationAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

const notificationPolicyDeDuplicationAction: notificationPolicy.NotificationPolicyDeDuplicationAction = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction.property.count">count</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#count NotificationPolicy#count}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction.property.deDuplicationActionType">deDuplicationActionType</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#de_duplication_action_type NotificationPolicy#de_duplication_action_type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction.property.duration">duration</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration">NotificationPolicyDeDuplicationActionDuration</a>[]</code> | duration block. |

---

##### `count`<sup>Required</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction.property.count"></a>

```typescript
public readonly count: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#count NotificationPolicy#count}.

---

##### `deDuplicationActionType`<sup>Required</sup> <a name="deDuplicationActionType" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction.property.deDuplicationActionType"></a>

```typescript
public readonly deDuplicationActionType: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#de_duplication_action_type NotificationPolicy#de_duplication_action_type}.

---

##### `duration`<sup>Optional</sup> <a name="duration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction.property.duration"></a>

```typescript
public readonly duration: IResolvable | NotificationPolicyDeDuplicationActionDuration[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration">NotificationPolicyDeDuplicationActionDuration</a>[]

duration block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#duration NotificationPolicy#duration}

---

### NotificationPolicyDeDuplicationActionDuration <a name="NotificationPolicyDeDuplicationActionDuration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

const notificationPolicyDeDuplicationActionDuration: notificationPolicy.NotificationPolicyDeDuplicationActionDuration = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration.property.timeAmount">timeAmount</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_amount NotificationPolicy#time_amount}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration.property.timeUnit">timeUnit</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_unit NotificationPolicy#time_unit}. |

---

##### `timeAmount`<sup>Required</sup> <a name="timeAmount" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration.property.timeAmount"></a>

```typescript
public readonly timeAmount: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_amount NotificationPolicy#time_amount}.

---

##### `timeUnit`<sup>Optional</sup> <a name="timeUnit" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration.property.timeUnit"></a>

```typescript
public readonly timeUnit: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_unit NotificationPolicy#time_unit}.

---

### NotificationPolicyDelayAction <a name="NotificationPolicyDelayAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

const notificationPolicyDelayAction: notificationPolicy.NotificationPolicyDelayAction = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction.property.delayOption">delayOption</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#delay_option NotificationPolicy#delay_option}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction.property.duration">duration</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration">NotificationPolicyDelayActionDuration</a>[]</code> | duration block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction.property.untilHour">untilHour</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#until_hour NotificationPolicy#until_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction.property.untilMinute">untilMinute</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#until_minute NotificationPolicy#until_minute}. |

---

##### `delayOption`<sup>Required</sup> <a name="delayOption" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction.property.delayOption"></a>

```typescript
public readonly delayOption: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#delay_option NotificationPolicy#delay_option}.

---

##### `duration`<sup>Optional</sup> <a name="duration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction.property.duration"></a>

```typescript
public readonly duration: IResolvable | NotificationPolicyDelayActionDuration[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration">NotificationPolicyDelayActionDuration</a>[]

duration block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#duration NotificationPolicy#duration}

---

##### `untilHour`<sup>Optional</sup> <a name="untilHour" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction.property.untilHour"></a>

```typescript
public readonly untilHour: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#until_hour NotificationPolicy#until_hour}.

---

##### `untilMinute`<sup>Optional</sup> <a name="untilMinute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction.property.untilMinute"></a>

```typescript
public readonly untilMinute: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#until_minute NotificationPolicy#until_minute}.

---

### NotificationPolicyDelayActionDuration <a name="NotificationPolicyDelayActionDuration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

const notificationPolicyDelayActionDuration: notificationPolicy.NotificationPolicyDelayActionDuration = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration.property.timeAmount">timeAmount</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_amount NotificationPolicy#time_amount}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration.property.timeUnit">timeUnit</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_unit NotificationPolicy#time_unit}. |

---

##### `timeAmount`<sup>Required</sup> <a name="timeAmount" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration.property.timeAmount"></a>

```typescript
public readonly timeAmount: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_amount NotificationPolicy#time_amount}.

---

##### `timeUnit`<sup>Optional</sup> <a name="timeUnit" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration.property.timeUnit"></a>

```typescript
public readonly timeUnit: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_unit NotificationPolicy#time_unit}.

---

### NotificationPolicyFilter <a name="NotificationPolicyFilter" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

const notificationPolicyFilter: notificationPolicy.NotificationPolicyFilter = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter.property.conditions">conditions</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions">NotificationPolicyFilterConditions</a>[]</code> | conditions block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter.property.type">type</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#type NotificationPolicy#type}. |

---

##### `conditions`<sup>Optional</sup> <a name="conditions" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter.property.conditions"></a>

```typescript
public readonly conditions: IResolvable | NotificationPolicyFilterConditions[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions">NotificationPolicyFilterConditions</a>[]

conditions block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#conditions NotificationPolicy#conditions}

---

##### `type`<sup>Optional</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter.property.type"></a>

```typescript
public readonly type: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#type NotificationPolicy#type}.

---

### NotificationPolicyFilterConditions <a name="NotificationPolicyFilterConditions" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

const notificationPolicyFilterConditions: notificationPolicy.NotificationPolicyFilterConditions = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.property.field">field</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#field NotificationPolicy#field}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.property.operation">operation</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#operation NotificationPolicy#operation}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.property.expectedValue">expectedValue</a></code> | <code>string</code> | User defined value that will be compared with alert field according to the operation. Default value is empty string. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.property.key">key</a></code> | <code>string</code> | If 'field' is set as 'extra-properties', key could be used for key-value pair. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.property.not">not</a></code> | <code>boolean \| cdktf.IResolvable</code> | Indicates behaviour of the given operation. Default value is false. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.property.order">order</a></code> | <code>number</code> | Order of the condition in conditions list. |

---

##### `field`<sup>Required</sup> <a name="field" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.property.field"></a>

```typescript
public readonly field: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#field NotificationPolicy#field}.

---

##### `operation`<sup>Required</sup> <a name="operation" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.property.operation"></a>

```typescript
public readonly operation: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#operation NotificationPolicy#operation}.

---

##### `expectedValue`<sup>Optional</sup> <a name="expectedValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.property.expectedValue"></a>

```typescript
public readonly expectedValue: string;
```

- *Type:* string

User defined value that will be compared with alert field according to the operation. Default value is empty string.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#expected_value NotificationPolicy#expected_value}

---

##### `key`<sup>Optional</sup> <a name="key" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.property.key"></a>

```typescript
public readonly key: string;
```

- *Type:* string

If 'field' is set as 'extra-properties', key could be used for key-value pair.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#key NotificationPolicy#key}

---

##### `not`<sup>Optional</sup> <a name="not" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.property.not"></a>

```typescript
public readonly not: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

Indicates behaviour of the given operation. Default value is false.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#not NotificationPolicy#not}

---

##### `order`<sup>Optional</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.property.order"></a>

```typescript
public readonly order: number;
```

- *Type:* number

Order of the condition in conditions list.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#order NotificationPolicy#order}

---

### NotificationPolicyTimeRestriction <a name="NotificationPolicyTimeRestriction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

const notificationPolicyTimeRestriction: notificationPolicy.NotificationPolicyTimeRestriction = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction.property.type">type</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#type NotificationPolicy#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction.property.restriction">restriction</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction">NotificationPolicyTimeRestrictionRestriction</a>[]</code> | restriction block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction.property.restrictions">restrictions</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions">NotificationPolicyTimeRestrictionRestrictions</a>[]</code> | restrictions block. |

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction.property.type"></a>

```typescript
public readonly type: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#type NotificationPolicy#type}.

---

##### `restriction`<sup>Optional</sup> <a name="restriction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction.property.restriction"></a>

```typescript
public readonly restriction: IResolvable | NotificationPolicyTimeRestrictionRestriction[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction">NotificationPolicyTimeRestrictionRestriction</a>[]

restriction block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#restriction NotificationPolicy#restriction}

---

##### `restrictions`<sup>Optional</sup> <a name="restrictions" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction.property.restrictions"></a>

```typescript
public readonly restrictions: IResolvable | NotificationPolicyTimeRestrictionRestrictions[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions">NotificationPolicyTimeRestrictionRestrictions</a>[]

restrictions block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#restrictions NotificationPolicy#restrictions}

---

### NotificationPolicyTimeRestrictionRestriction <a name="NotificationPolicyTimeRestrictionRestriction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

const notificationPolicyTimeRestrictionRestriction: notificationPolicy.NotificationPolicyTimeRestrictionRestriction = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction.property.endHour">endHour</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#end_hour NotificationPolicy#end_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction.property.endMin">endMin</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#end_min NotificationPolicy#end_min}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction.property.startHour">startHour</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#start_hour NotificationPolicy#start_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction.property.startMin">startMin</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#start_min NotificationPolicy#start_min}. |

---

##### `endHour`<sup>Required</sup> <a name="endHour" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction.property.endHour"></a>

```typescript
public readonly endHour: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#end_hour NotificationPolicy#end_hour}.

---

##### `endMin`<sup>Required</sup> <a name="endMin" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction.property.endMin"></a>

```typescript
public readonly endMin: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#end_min NotificationPolicy#end_min}.

---

##### `startHour`<sup>Required</sup> <a name="startHour" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction.property.startHour"></a>

```typescript
public readonly startHour: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#start_hour NotificationPolicy#start_hour}.

---

##### `startMin`<sup>Required</sup> <a name="startMin" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction.property.startMin"></a>

```typescript
public readonly startMin: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#start_min NotificationPolicy#start_min}.

---

### NotificationPolicyTimeRestrictionRestrictions <a name="NotificationPolicyTimeRestrictionRestrictions" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

const notificationPolicyTimeRestrictionRestrictions: notificationPolicy.NotificationPolicyTimeRestrictionRestrictions = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.property.endDay">endDay</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#end_day NotificationPolicy#end_day}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.property.endHour">endHour</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#end_hour NotificationPolicy#end_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.property.endMin">endMin</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#end_min NotificationPolicy#end_min}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.property.startDay">startDay</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#start_day NotificationPolicy#start_day}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.property.startHour">startHour</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#start_hour NotificationPolicy#start_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.property.startMin">startMin</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#start_min NotificationPolicy#start_min}. |

---

##### `endDay`<sup>Required</sup> <a name="endDay" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.property.endDay"></a>

```typescript
public readonly endDay: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#end_day NotificationPolicy#end_day}.

---

##### `endHour`<sup>Required</sup> <a name="endHour" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.property.endHour"></a>

```typescript
public readonly endHour: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#end_hour NotificationPolicy#end_hour}.

---

##### `endMin`<sup>Required</sup> <a name="endMin" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.property.endMin"></a>

```typescript
public readonly endMin: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#end_min NotificationPolicy#end_min}.

---

##### `startDay`<sup>Required</sup> <a name="startDay" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.property.startDay"></a>

```typescript
public readonly startDay: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#start_day NotificationPolicy#start_day}.

---

##### `startHour`<sup>Required</sup> <a name="startHour" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.property.startHour"></a>

```typescript
public readonly startHour: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#start_hour NotificationPolicy#start_hour}.

---

##### `startMin`<sup>Required</sup> <a name="startMin" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.property.startMin"></a>

```typescript
public readonly startMin: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#start_min NotificationPolicy#start_min}.

---

## Classes <a name="Classes" id="Classes"></a>

### NotificationPolicyAutoCloseActionDurationList <a name="NotificationPolicyAutoCloseActionDurationList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new notificationPolicy.NotificationPolicyAutoCloseActionDurationList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.get"></a>

```typescript
public get(index: number): NotificationPolicyAutoCloseActionDurationOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration">NotificationPolicyAutoCloseActionDuration</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | NotificationPolicyAutoCloseActionDuration[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration">NotificationPolicyAutoCloseActionDuration</a>[]

---


### NotificationPolicyAutoCloseActionDurationOutputReference <a name="NotificationPolicyAutoCloseActionDurationOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.resetTimeUnit">resetTimeUnit</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetTimeUnit` <a name="resetTimeUnit" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.resetTimeUnit"></a>

```typescript
public resetTimeUnit(): void
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.timeAmountInput">timeAmountInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.timeUnitInput">timeUnitInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.timeAmount">timeAmount</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.timeUnit">timeUnit</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration">NotificationPolicyAutoCloseActionDuration</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `timeAmountInput`<sup>Optional</sup> <a name="timeAmountInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.timeAmountInput"></a>

```typescript
public readonly timeAmountInput: number;
```

- *Type:* number

---

##### `timeUnitInput`<sup>Optional</sup> <a name="timeUnitInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.timeUnitInput"></a>

```typescript
public readonly timeUnitInput: string;
```

- *Type:* string

---

##### `timeAmount`<sup>Required</sup> <a name="timeAmount" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.timeAmount"></a>

```typescript
public readonly timeAmount: number;
```

- *Type:* number

---

##### `timeUnit`<sup>Required</sup> <a name="timeUnit" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.timeUnit"></a>

```typescript
public readonly timeUnit: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | NotificationPolicyAutoCloseActionDuration;
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration">NotificationPolicyAutoCloseActionDuration</a>

---


### NotificationPolicyAutoCloseActionList <a name="NotificationPolicyAutoCloseActionList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new notificationPolicy.NotificationPolicyAutoCloseActionList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.get"></a>

```typescript
public get(index: number): NotificationPolicyAutoCloseActionOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction">NotificationPolicyAutoCloseAction</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | NotificationPolicyAutoCloseAction[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction">NotificationPolicyAutoCloseAction</a>[]

---


### NotificationPolicyAutoCloseActionOutputReference <a name="NotificationPolicyAutoCloseActionOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new notificationPolicy.NotificationPolicyAutoCloseActionOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.putDuration">putDuration</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `putDuration` <a name="putDuration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.putDuration"></a>

```typescript
public putDuration(value: IResolvable | NotificationPolicyAutoCloseActionDuration[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.putDuration.parameter.value"></a>

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration">NotificationPolicyAutoCloseActionDuration</a>[]

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.property.duration">duration</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList">NotificationPolicyAutoCloseActionDurationList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.property.durationInput">durationInput</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration">NotificationPolicyAutoCloseActionDuration</a>[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction">NotificationPolicyAutoCloseAction</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `duration`<sup>Required</sup> <a name="duration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.property.duration"></a>

```typescript
public readonly duration: NotificationPolicyAutoCloseActionDurationList;
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList">NotificationPolicyAutoCloseActionDurationList</a>

---

##### `durationInput`<sup>Optional</sup> <a name="durationInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.property.durationInput"></a>

```typescript
public readonly durationInput: IResolvable | NotificationPolicyAutoCloseActionDuration[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration">NotificationPolicyAutoCloseActionDuration</a>[]

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | NotificationPolicyAutoCloseAction;
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction">NotificationPolicyAutoCloseAction</a>

---


### NotificationPolicyAutoRestartActionDurationList <a name="NotificationPolicyAutoRestartActionDurationList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new notificationPolicy.NotificationPolicyAutoRestartActionDurationList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.get"></a>

```typescript
public get(index: number): NotificationPolicyAutoRestartActionDurationOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration">NotificationPolicyAutoRestartActionDuration</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | NotificationPolicyAutoRestartActionDuration[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration">NotificationPolicyAutoRestartActionDuration</a>[]

---


### NotificationPolicyAutoRestartActionDurationOutputReference <a name="NotificationPolicyAutoRestartActionDurationOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.resetTimeUnit">resetTimeUnit</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetTimeUnit` <a name="resetTimeUnit" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.resetTimeUnit"></a>

```typescript
public resetTimeUnit(): void
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.timeAmountInput">timeAmountInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.timeUnitInput">timeUnitInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.timeAmount">timeAmount</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.timeUnit">timeUnit</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration">NotificationPolicyAutoRestartActionDuration</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `timeAmountInput`<sup>Optional</sup> <a name="timeAmountInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.timeAmountInput"></a>

```typescript
public readonly timeAmountInput: number;
```

- *Type:* number

---

##### `timeUnitInput`<sup>Optional</sup> <a name="timeUnitInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.timeUnitInput"></a>

```typescript
public readonly timeUnitInput: string;
```

- *Type:* string

---

##### `timeAmount`<sup>Required</sup> <a name="timeAmount" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.timeAmount"></a>

```typescript
public readonly timeAmount: number;
```

- *Type:* number

---

##### `timeUnit`<sup>Required</sup> <a name="timeUnit" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.timeUnit"></a>

```typescript
public readonly timeUnit: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | NotificationPolicyAutoRestartActionDuration;
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration">NotificationPolicyAutoRestartActionDuration</a>

---


### NotificationPolicyAutoRestartActionList <a name="NotificationPolicyAutoRestartActionList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new notificationPolicy.NotificationPolicyAutoRestartActionList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.get"></a>

```typescript
public get(index: number): NotificationPolicyAutoRestartActionOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction">NotificationPolicyAutoRestartAction</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | NotificationPolicyAutoRestartAction[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction">NotificationPolicyAutoRestartAction</a>[]

---


### NotificationPolicyAutoRestartActionOutputReference <a name="NotificationPolicyAutoRestartActionOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new notificationPolicy.NotificationPolicyAutoRestartActionOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.putDuration">putDuration</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `putDuration` <a name="putDuration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.putDuration"></a>

```typescript
public putDuration(value: IResolvable | NotificationPolicyAutoRestartActionDuration[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.putDuration.parameter.value"></a>

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration">NotificationPolicyAutoRestartActionDuration</a>[]

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.duration">duration</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList">NotificationPolicyAutoRestartActionDurationList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.durationInput">durationInput</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration">NotificationPolicyAutoRestartActionDuration</a>[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.maxRepeatCountInput">maxRepeatCountInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.maxRepeatCount">maxRepeatCount</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction">NotificationPolicyAutoRestartAction</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `duration`<sup>Required</sup> <a name="duration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.duration"></a>

```typescript
public readonly duration: NotificationPolicyAutoRestartActionDurationList;
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList">NotificationPolicyAutoRestartActionDurationList</a>

---

##### `durationInput`<sup>Optional</sup> <a name="durationInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.durationInput"></a>

```typescript
public readonly durationInput: IResolvable | NotificationPolicyAutoRestartActionDuration[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration">NotificationPolicyAutoRestartActionDuration</a>[]

---

##### `maxRepeatCountInput`<sup>Optional</sup> <a name="maxRepeatCountInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.maxRepeatCountInput"></a>

```typescript
public readonly maxRepeatCountInput: number;
```

- *Type:* number

---

##### `maxRepeatCount`<sup>Required</sup> <a name="maxRepeatCount" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.maxRepeatCount"></a>

```typescript
public readonly maxRepeatCount: number;
```

- *Type:* number

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | NotificationPolicyAutoRestartAction;
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction">NotificationPolicyAutoRestartAction</a>

---


### NotificationPolicyDeDuplicationActionDurationList <a name="NotificationPolicyDeDuplicationActionDurationList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new notificationPolicy.NotificationPolicyDeDuplicationActionDurationList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.get"></a>

```typescript
public get(index: number): NotificationPolicyDeDuplicationActionDurationOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration">NotificationPolicyDeDuplicationActionDuration</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | NotificationPolicyDeDuplicationActionDuration[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration">NotificationPolicyDeDuplicationActionDuration</a>[]

---


### NotificationPolicyDeDuplicationActionDurationOutputReference <a name="NotificationPolicyDeDuplicationActionDurationOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.resetTimeUnit">resetTimeUnit</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetTimeUnit` <a name="resetTimeUnit" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.resetTimeUnit"></a>

```typescript
public resetTimeUnit(): void
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.timeAmountInput">timeAmountInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.timeUnitInput">timeUnitInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.timeAmount">timeAmount</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.timeUnit">timeUnit</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration">NotificationPolicyDeDuplicationActionDuration</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `timeAmountInput`<sup>Optional</sup> <a name="timeAmountInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.timeAmountInput"></a>

```typescript
public readonly timeAmountInput: number;
```

- *Type:* number

---

##### `timeUnitInput`<sup>Optional</sup> <a name="timeUnitInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.timeUnitInput"></a>

```typescript
public readonly timeUnitInput: string;
```

- *Type:* string

---

##### `timeAmount`<sup>Required</sup> <a name="timeAmount" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.timeAmount"></a>

```typescript
public readonly timeAmount: number;
```

- *Type:* number

---

##### `timeUnit`<sup>Required</sup> <a name="timeUnit" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.timeUnit"></a>

```typescript
public readonly timeUnit: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | NotificationPolicyDeDuplicationActionDuration;
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration">NotificationPolicyDeDuplicationActionDuration</a>

---


### NotificationPolicyDeDuplicationActionList <a name="NotificationPolicyDeDuplicationActionList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new notificationPolicy.NotificationPolicyDeDuplicationActionList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.get"></a>

```typescript
public get(index: number): NotificationPolicyDeDuplicationActionOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction">NotificationPolicyDeDuplicationAction</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | NotificationPolicyDeDuplicationAction[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction">NotificationPolicyDeDuplicationAction</a>[]

---


### NotificationPolicyDeDuplicationActionOutputReference <a name="NotificationPolicyDeDuplicationActionOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.putDuration">putDuration</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.resetDuration">resetDuration</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `putDuration` <a name="putDuration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.putDuration"></a>

```typescript
public putDuration(value: IResolvable | NotificationPolicyDeDuplicationActionDuration[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.putDuration.parameter.value"></a>

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration">NotificationPolicyDeDuplicationActionDuration</a>[]

---

##### `resetDuration` <a name="resetDuration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.resetDuration"></a>

```typescript
public resetDuration(): void
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.duration">duration</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList">NotificationPolicyDeDuplicationActionDurationList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.countInput">countInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.deDuplicationActionTypeInput">deDuplicationActionTypeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.durationInput">durationInput</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration">NotificationPolicyDeDuplicationActionDuration</a>[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.count">count</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.deDuplicationActionType">deDuplicationActionType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction">NotificationPolicyDeDuplicationAction</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `duration`<sup>Required</sup> <a name="duration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.duration"></a>

```typescript
public readonly duration: NotificationPolicyDeDuplicationActionDurationList;
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList">NotificationPolicyDeDuplicationActionDurationList</a>

---

##### `countInput`<sup>Optional</sup> <a name="countInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.countInput"></a>

```typescript
public readonly countInput: number;
```

- *Type:* number

---

##### `deDuplicationActionTypeInput`<sup>Optional</sup> <a name="deDuplicationActionTypeInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.deDuplicationActionTypeInput"></a>

```typescript
public readonly deDuplicationActionTypeInput: string;
```

- *Type:* string

---

##### `durationInput`<sup>Optional</sup> <a name="durationInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.durationInput"></a>

```typescript
public readonly durationInput: IResolvable | NotificationPolicyDeDuplicationActionDuration[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration">NotificationPolicyDeDuplicationActionDuration</a>[]

---

##### `count`<sup>Required</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.count"></a>

```typescript
public readonly count: number;
```

- *Type:* number

---

##### `deDuplicationActionType`<sup>Required</sup> <a name="deDuplicationActionType" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.deDuplicationActionType"></a>

```typescript
public readonly deDuplicationActionType: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | NotificationPolicyDeDuplicationAction;
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction">NotificationPolicyDeDuplicationAction</a>

---


### NotificationPolicyDelayActionDurationList <a name="NotificationPolicyDelayActionDurationList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new notificationPolicy.NotificationPolicyDelayActionDurationList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.get"></a>

```typescript
public get(index: number): NotificationPolicyDelayActionDurationOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration">NotificationPolicyDelayActionDuration</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | NotificationPolicyDelayActionDuration[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration">NotificationPolicyDelayActionDuration</a>[]

---


### NotificationPolicyDelayActionDurationOutputReference <a name="NotificationPolicyDelayActionDurationOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new notificationPolicy.NotificationPolicyDelayActionDurationOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.resetTimeUnit">resetTimeUnit</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetTimeUnit` <a name="resetTimeUnit" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.resetTimeUnit"></a>

```typescript
public resetTimeUnit(): void
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.timeAmountInput">timeAmountInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.timeUnitInput">timeUnitInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.timeAmount">timeAmount</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.timeUnit">timeUnit</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration">NotificationPolicyDelayActionDuration</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `timeAmountInput`<sup>Optional</sup> <a name="timeAmountInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.timeAmountInput"></a>

```typescript
public readonly timeAmountInput: number;
```

- *Type:* number

---

##### `timeUnitInput`<sup>Optional</sup> <a name="timeUnitInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.timeUnitInput"></a>

```typescript
public readonly timeUnitInput: string;
```

- *Type:* string

---

##### `timeAmount`<sup>Required</sup> <a name="timeAmount" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.timeAmount"></a>

```typescript
public readonly timeAmount: number;
```

- *Type:* number

---

##### `timeUnit`<sup>Required</sup> <a name="timeUnit" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.timeUnit"></a>

```typescript
public readonly timeUnit: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | NotificationPolicyDelayActionDuration;
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration">NotificationPolicyDelayActionDuration</a>

---


### NotificationPolicyDelayActionList <a name="NotificationPolicyDelayActionList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new notificationPolicy.NotificationPolicyDelayActionList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.get"></a>

```typescript
public get(index: number): NotificationPolicyDelayActionOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction">NotificationPolicyDelayAction</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | NotificationPolicyDelayAction[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction">NotificationPolicyDelayAction</a>[]

---


### NotificationPolicyDelayActionOutputReference <a name="NotificationPolicyDelayActionOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new notificationPolicy.NotificationPolicyDelayActionOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.putDuration">putDuration</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.resetDuration">resetDuration</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.resetUntilHour">resetUntilHour</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.resetUntilMinute">resetUntilMinute</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `putDuration` <a name="putDuration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.putDuration"></a>

```typescript
public putDuration(value: IResolvable | NotificationPolicyDelayActionDuration[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.putDuration.parameter.value"></a>

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration">NotificationPolicyDelayActionDuration</a>[]

---

##### `resetDuration` <a name="resetDuration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.resetDuration"></a>

```typescript
public resetDuration(): void
```

##### `resetUntilHour` <a name="resetUntilHour" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.resetUntilHour"></a>

```typescript
public resetUntilHour(): void
```

##### `resetUntilMinute` <a name="resetUntilMinute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.resetUntilMinute"></a>

```typescript
public resetUntilMinute(): void
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.duration">duration</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList">NotificationPolicyDelayActionDurationList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.delayOptionInput">delayOptionInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.durationInput">durationInput</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration">NotificationPolicyDelayActionDuration</a>[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.untilHourInput">untilHourInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.untilMinuteInput">untilMinuteInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.delayOption">delayOption</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.untilHour">untilHour</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.untilMinute">untilMinute</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction">NotificationPolicyDelayAction</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `duration`<sup>Required</sup> <a name="duration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.duration"></a>

```typescript
public readonly duration: NotificationPolicyDelayActionDurationList;
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList">NotificationPolicyDelayActionDurationList</a>

---

##### `delayOptionInput`<sup>Optional</sup> <a name="delayOptionInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.delayOptionInput"></a>

```typescript
public readonly delayOptionInput: string;
```

- *Type:* string

---

##### `durationInput`<sup>Optional</sup> <a name="durationInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.durationInput"></a>

```typescript
public readonly durationInput: IResolvable | NotificationPolicyDelayActionDuration[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration">NotificationPolicyDelayActionDuration</a>[]

---

##### `untilHourInput`<sup>Optional</sup> <a name="untilHourInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.untilHourInput"></a>

```typescript
public readonly untilHourInput: number;
```

- *Type:* number

---

##### `untilMinuteInput`<sup>Optional</sup> <a name="untilMinuteInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.untilMinuteInput"></a>

```typescript
public readonly untilMinuteInput: number;
```

- *Type:* number

---

##### `delayOption`<sup>Required</sup> <a name="delayOption" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.delayOption"></a>

```typescript
public readonly delayOption: string;
```

- *Type:* string

---

##### `untilHour`<sup>Required</sup> <a name="untilHour" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.untilHour"></a>

```typescript
public readonly untilHour: number;
```

- *Type:* number

---

##### `untilMinute`<sup>Required</sup> <a name="untilMinute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.untilMinute"></a>

```typescript
public readonly untilMinute: number;
```

- *Type:* number

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | NotificationPolicyDelayAction;
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction">NotificationPolicyDelayAction</a>

---


### NotificationPolicyFilterConditionsList <a name="NotificationPolicyFilterConditionsList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new notificationPolicy.NotificationPolicyFilterConditionsList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.get"></a>

```typescript
public get(index: number): NotificationPolicyFilterConditionsOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions">NotificationPolicyFilterConditions</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | NotificationPolicyFilterConditions[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions">NotificationPolicyFilterConditions</a>[]

---


### NotificationPolicyFilterConditionsOutputReference <a name="NotificationPolicyFilterConditionsOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new notificationPolicy.NotificationPolicyFilterConditionsOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.resetExpectedValue">resetExpectedValue</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.resetKey">resetKey</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.resetNot">resetNot</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.resetOrder">resetOrder</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetExpectedValue` <a name="resetExpectedValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.resetExpectedValue"></a>

```typescript
public resetExpectedValue(): void
```

##### `resetKey` <a name="resetKey" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.resetKey"></a>

```typescript
public resetKey(): void
```

##### `resetNot` <a name="resetNot" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.resetNot"></a>

```typescript
public resetNot(): void
```

##### `resetOrder` <a name="resetOrder" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.resetOrder"></a>

```typescript
public resetOrder(): void
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.expectedValueInput">expectedValueInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.fieldInput">fieldInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.keyInput">keyInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.notInput">notInput</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.operationInput">operationInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.orderInput">orderInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.expectedValue">expectedValue</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.field">field</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.key">key</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.not">not</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.operation">operation</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.order">order</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions">NotificationPolicyFilterConditions</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `expectedValueInput`<sup>Optional</sup> <a name="expectedValueInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.expectedValueInput"></a>

```typescript
public readonly expectedValueInput: string;
```

- *Type:* string

---

##### `fieldInput`<sup>Optional</sup> <a name="fieldInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.fieldInput"></a>

```typescript
public readonly fieldInput: string;
```

- *Type:* string

---

##### `keyInput`<sup>Optional</sup> <a name="keyInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.keyInput"></a>

```typescript
public readonly keyInput: string;
```

- *Type:* string

---

##### `notInput`<sup>Optional</sup> <a name="notInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.notInput"></a>

```typescript
public readonly notInput: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `operationInput`<sup>Optional</sup> <a name="operationInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.operationInput"></a>

```typescript
public readonly operationInput: string;
```

- *Type:* string

---

##### `orderInput`<sup>Optional</sup> <a name="orderInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.orderInput"></a>

```typescript
public readonly orderInput: number;
```

- *Type:* number

---

##### `expectedValue`<sup>Required</sup> <a name="expectedValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.expectedValue"></a>

```typescript
public readonly expectedValue: string;
```

- *Type:* string

---

##### `field`<sup>Required</sup> <a name="field" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.field"></a>

```typescript
public readonly field: string;
```

- *Type:* string

---

##### `key`<sup>Required</sup> <a name="key" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.key"></a>

```typescript
public readonly key: string;
```

- *Type:* string

---

##### `not`<sup>Required</sup> <a name="not" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.not"></a>

```typescript
public readonly not: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `operation`<sup>Required</sup> <a name="operation" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.operation"></a>

```typescript
public readonly operation: string;
```

- *Type:* string

---

##### `order`<sup>Required</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.order"></a>

```typescript
public readonly order: number;
```

- *Type:* number

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | NotificationPolicyFilterConditions;
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions">NotificationPolicyFilterConditions</a>

---


### NotificationPolicyFilterList <a name="NotificationPolicyFilterList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new notificationPolicy.NotificationPolicyFilterList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.get"></a>

```typescript
public get(index: number): NotificationPolicyFilterOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter">NotificationPolicyFilter</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | NotificationPolicyFilter[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter">NotificationPolicyFilter</a>[]

---


### NotificationPolicyFilterOutputReference <a name="NotificationPolicyFilterOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new notificationPolicy.NotificationPolicyFilterOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.putConditions">putConditions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.resetConditions">resetConditions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.resetType">resetType</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `putConditions` <a name="putConditions" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.putConditions"></a>

```typescript
public putConditions(value: IResolvable | NotificationPolicyFilterConditions[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.putConditions.parameter.value"></a>

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions">NotificationPolicyFilterConditions</a>[]

---

##### `resetConditions` <a name="resetConditions" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.resetConditions"></a>

```typescript
public resetConditions(): void
```

##### `resetType` <a name="resetType" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.resetType"></a>

```typescript
public resetType(): void
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.conditions">conditions</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList">NotificationPolicyFilterConditionsList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.conditionsInput">conditionsInput</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions">NotificationPolicyFilterConditions</a>[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.typeInput">typeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.type">type</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter">NotificationPolicyFilter</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `conditions`<sup>Required</sup> <a name="conditions" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.conditions"></a>

```typescript
public readonly conditions: NotificationPolicyFilterConditionsList;
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList">NotificationPolicyFilterConditionsList</a>

---

##### `conditionsInput`<sup>Optional</sup> <a name="conditionsInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.conditionsInput"></a>

```typescript
public readonly conditionsInput: IResolvable | NotificationPolicyFilterConditions[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions">NotificationPolicyFilterConditions</a>[]

---

##### `typeInput`<sup>Optional</sup> <a name="typeInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.typeInput"></a>

```typescript
public readonly typeInput: string;
```

- *Type:* string

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.type"></a>

```typescript
public readonly type: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | NotificationPolicyFilter;
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter">NotificationPolicyFilter</a>

---


### NotificationPolicyTimeRestrictionList <a name="NotificationPolicyTimeRestrictionList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new notificationPolicy.NotificationPolicyTimeRestrictionList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.get"></a>

```typescript
public get(index: number): NotificationPolicyTimeRestrictionOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction">NotificationPolicyTimeRestriction</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | NotificationPolicyTimeRestriction[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction">NotificationPolicyTimeRestriction</a>[]

---


### NotificationPolicyTimeRestrictionOutputReference <a name="NotificationPolicyTimeRestrictionOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new notificationPolicy.NotificationPolicyTimeRestrictionOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.putRestriction">putRestriction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.putRestrictions">putRestrictions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.resetRestriction">resetRestriction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.resetRestrictions">resetRestrictions</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `putRestriction` <a name="putRestriction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.putRestriction"></a>

```typescript
public putRestriction(value: IResolvable | NotificationPolicyTimeRestrictionRestriction[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.putRestriction.parameter.value"></a>

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction">NotificationPolicyTimeRestrictionRestriction</a>[]

---

##### `putRestrictions` <a name="putRestrictions" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.putRestrictions"></a>

```typescript
public putRestrictions(value: IResolvable | NotificationPolicyTimeRestrictionRestrictions[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.putRestrictions.parameter.value"></a>

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions">NotificationPolicyTimeRestrictionRestrictions</a>[]

---

##### `resetRestriction` <a name="resetRestriction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.resetRestriction"></a>

```typescript
public resetRestriction(): void
```

##### `resetRestrictions` <a name="resetRestrictions" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.resetRestrictions"></a>

```typescript
public resetRestrictions(): void
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.restriction">restriction</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList">NotificationPolicyTimeRestrictionRestrictionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.restrictions">restrictions</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList">NotificationPolicyTimeRestrictionRestrictionsList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.restrictionInput">restrictionInput</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction">NotificationPolicyTimeRestrictionRestriction</a>[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.restrictionsInput">restrictionsInput</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions">NotificationPolicyTimeRestrictionRestrictions</a>[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.typeInput">typeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.type">type</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction">NotificationPolicyTimeRestriction</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `restriction`<sup>Required</sup> <a name="restriction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.restriction"></a>

```typescript
public readonly restriction: NotificationPolicyTimeRestrictionRestrictionList;
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList">NotificationPolicyTimeRestrictionRestrictionList</a>

---

##### `restrictions`<sup>Required</sup> <a name="restrictions" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.restrictions"></a>

```typescript
public readonly restrictions: NotificationPolicyTimeRestrictionRestrictionsList;
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList">NotificationPolicyTimeRestrictionRestrictionsList</a>

---

##### `restrictionInput`<sup>Optional</sup> <a name="restrictionInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.restrictionInput"></a>

```typescript
public readonly restrictionInput: IResolvable | NotificationPolicyTimeRestrictionRestriction[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction">NotificationPolicyTimeRestrictionRestriction</a>[]

---

##### `restrictionsInput`<sup>Optional</sup> <a name="restrictionsInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.restrictionsInput"></a>

```typescript
public readonly restrictionsInput: IResolvable | NotificationPolicyTimeRestrictionRestrictions[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions">NotificationPolicyTimeRestrictionRestrictions</a>[]

---

##### `typeInput`<sup>Optional</sup> <a name="typeInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.typeInput"></a>

```typescript
public readonly typeInput: string;
```

- *Type:* string

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.type"></a>

```typescript
public readonly type: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | NotificationPolicyTimeRestriction;
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction">NotificationPolicyTimeRestriction</a>

---


### NotificationPolicyTimeRestrictionRestrictionList <a name="NotificationPolicyTimeRestrictionRestrictionList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.get"></a>

```typescript
public get(index: number): NotificationPolicyTimeRestrictionRestrictionOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction">NotificationPolicyTimeRestrictionRestriction</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | NotificationPolicyTimeRestrictionRestriction[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction">NotificationPolicyTimeRestrictionRestriction</a>[]

---


### NotificationPolicyTimeRestrictionRestrictionOutputReference <a name="NotificationPolicyTimeRestrictionRestrictionOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.endHourInput">endHourInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.endMinInput">endMinInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.startHourInput">startHourInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.startMinInput">startMinInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.endHour">endHour</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.endMin">endMin</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.startHour">startHour</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.startMin">startMin</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction">NotificationPolicyTimeRestrictionRestriction</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `endHourInput`<sup>Optional</sup> <a name="endHourInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.endHourInput"></a>

```typescript
public readonly endHourInput: number;
```

- *Type:* number

---

##### `endMinInput`<sup>Optional</sup> <a name="endMinInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.endMinInput"></a>

```typescript
public readonly endMinInput: number;
```

- *Type:* number

---

##### `startHourInput`<sup>Optional</sup> <a name="startHourInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.startHourInput"></a>

```typescript
public readonly startHourInput: number;
```

- *Type:* number

---

##### `startMinInput`<sup>Optional</sup> <a name="startMinInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.startMinInput"></a>

```typescript
public readonly startMinInput: number;
```

- *Type:* number

---

##### `endHour`<sup>Required</sup> <a name="endHour" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.endHour"></a>

```typescript
public readonly endHour: number;
```

- *Type:* number

---

##### `endMin`<sup>Required</sup> <a name="endMin" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.endMin"></a>

```typescript
public readonly endMin: number;
```

- *Type:* number

---

##### `startHour`<sup>Required</sup> <a name="startHour" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.startHour"></a>

```typescript
public readonly startHour: number;
```

- *Type:* number

---

##### `startMin`<sup>Required</sup> <a name="startMin" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.startMin"></a>

```typescript
public readonly startMin: number;
```

- *Type:* number

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | NotificationPolicyTimeRestrictionRestriction;
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction">NotificationPolicyTimeRestrictionRestriction</a>

---


### NotificationPolicyTimeRestrictionRestrictionsList <a name="NotificationPolicyTimeRestrictionRestrictionsList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.get"></a>

```typescript
public get(index: number): NotificationPolicyTimeRestrictionRestrictionsOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions">NotificationPolicyTimeRestrictionRestrictions</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | NotificationPolicyTimeRestrictionRestrictions[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions">NotificationPolicyTimeRestrictionRestrictions</a>[]

---


### NotificationPolicyTimeRestrictionRestrictionsOutputReference <a name="NotificationPolicyTimeRestrictionRestrictionsOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.Initializer"></a>

```typescript
import { notificationPolicy } from 'rhizo-co-terraform-provider-opsgenie'

new notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.endDayInput">endDayInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.endHourInput">endHourInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.endMinInput">endMinInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.startDayInput">startDayInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.startHourInput">startHourInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.startMinInput">startMinInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.endDay">endDay</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.endHour">endHour</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.endMin">endMin</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.startDay">startDay</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.startHour">startHour</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.startMin">startMin</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions">NotificationPolicyTimeRestrictionRestrictions</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `endDayInput`<sup>Optional</sup> <a name="endDayInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.endDayInput"></a>

```typescript
public readonly endDayInput: string;
```

- *Type:* string

---

##### `endHourInput`<sup>Optional</sup> <a name="endHourInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.endHourInput"></a>

```typescript
public readonly endHourInput: number;
```

- *Type:* number

---

##### `endMinInput`<sup>Optional</sup> <a name="endMinInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.endMinInput"></a>

```typescript
public readonly endMinInput: number;
```

- *Type:* number

---

##### `startDayInput`<sup>Optional</sup> <a name="startDayInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.startDayInput"></a>

```typescript
public readonly startDayInput: string;
```

- *Type:* string

---

##### `startHourInput`<sup>Optional</sup> <a name="startHourInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.startHourInput"></a>

```typescript
public readonly startHourInput: number;
```

- *Type:* number

---

##### `startMinInput`<sup>Optional</sup> <a name="startMinInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.startMinInput"></a>

```typescript
public readonly startMinInput: number;
```

- *Type:* number

---

##### `endDay`<sup>Required</sup> <a name="endDay" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.endDay"></a>

```typescript
public readonly endDay: string;
```

- *Type:* string

---

##### `endHour`<sup>Required</sup> <a name="endHour" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.endHour"></a>

```typescript
public readonly endHour: number;
```

- *Type:* number

---

##### `endMin`<sup>Required</sup> <a name="endMin" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.endMin"></a>

```typescript
public readonly endMin: number;
```

- *Type:* number

---

##### `startDay`<sup>Required</sup> <a name="startDay" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.startDay"></a>

```typescript
public readonly startDay: string;
```

- *Type:* string

---

##### `startHour`<sup>Required</sup> <a name="startHour" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.startHour"></a>

```typescript
public readonly startHour: number;
```

- *Type:* number

---

##### `startMin`<sup>Required</sup> <a name="startMin" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.startMin"></a>

```typescript
public readonly startMin: number;
```

- *Type:* number

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | NotificationPolicyTimeRestrictionRestrictions;
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions">NotificationPolicyTimeRestrictionRestrictions</a>

---



