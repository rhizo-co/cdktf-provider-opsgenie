# `opsgenie_service_incident_rule`

Refer to the Terraform Registory for docs: [`opsgenie_service_incident_rule`](https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule).

# `serviceIncidentRule` Submodule <a name="`serviceIncidentRule` Submodule" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### ServiceIncidentRule <a name="ServiceIncidentRule" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule"></a>

Represents a {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule opsgenie_service_incident_rule}.

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer"></a>

```typescript
import { serviceIncidentRule } from 'rhizo-co-terraform-provider-opsgenie'

new serviceIncidentRule.ServiceIncidentRule(scope: Construct, id: string, config: ServiceIncidentRuleConfig)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.id">id</a></code> | <code>string</code> | The scoped construct ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.config">config</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig">ServiceIncidentRuleConfig</a></code> | *No description.* |

---

##### `scope`<sup>Required</sup> <a name="scope" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.id"></a>

- *Type:* string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Required</sup> <a name="config" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.config"></a>

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig">ServiceIncidentRuleConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.toString">toString</a></code> | Returns a string representation of this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.addOverride">addOverride</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.overrideLogicalId">overrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.resetOverrideLogicalId">resetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.toMetadata">toMetadata</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.toTerraform">toTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.putIncidentRule">putIncidentRule</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.resetId">resetId</a></code> | *No description.* |

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.toString"></a>

```typescript
public toString(): string
```

Returns a string representation of this construct.

##### `addOverride` <a name="addOverride" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.addOverride"></a>

```typescript
public addOverride(path: string, value: any): void
```

###### `path`<sup>Required</sup> <a name="path" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.addOverride.parameter.path"></a>

- *Type:* string

---

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.addOverride.parameter.value"></a>

- *Type:* any

---

##### `overrideLogicalId` <a name="overrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.overrideLogicalId"></a>

```typescript
public overrideLogicalId(newLogicalId: string): void
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* string

The new logical ID to use for this stack element.

---

##### `resetOverrideLogicalId` <a name="resetOverrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.resetOverrideLogicalId"></a>

```typescript
public resetOverrideLogicalId(): void
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `toMetadata` <a name="toMetadata" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.toMetadata"></a>

```typescript
public toMetadata(): any
```

##### `toTerraform` <a name="toTerraform" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.toTerraform"></a>

```typescript
public toTerraform(): any
```

Adds this resource to the terraform JSON output.

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `putIncidentRule` <a name="putIncidentRule" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.putIncidentRule"></a>

```typescript
public putIncidentRule(value: IResolvable | ServiceIncidentRuleIncidentRule[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.putIncidentRule.parameter.value"></a>

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule">ServiceIncidentRuleIncidentRule</a>[]

---

##### `resetId` <a name="resetId" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.resetId"></a>

```typescript
public resetId(): void
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isConstruct">isConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isTerraformElement">isTerraformElement</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isTerraformResource">isTerraformResource</a></code> | *No description.* |

---

##### `isConstruct` <a name="isConstruct" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isConstruct"></a>

```typescript
import { serviceIncidentRule } from 'rhizo-co-terraform-provider-opsgenie'

serviceIncidentRule.ServiceIncidentRule.isConstruct(x: any)
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

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isConstruct.parameter.x"></a>

- *Type:* any

Any object.

---

##### `isTerraformElement` <a name="isTerraformElement" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isTerraformElement"></a>

```typescript
import { serviceIncidentRule } from 'rhizo-co-terraform-provider-opsgenie'

serviceIncidentRule.ServiceIncidentRule.isTerraformElement(x: any)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isTerraformElement.parameter.x"></a>

- *Type:* any

---

##### `isTerraformResource` <a name="isTerraformResource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isTerraformResource"></a>

```typescript
import { serviceIncidentRule } from 'rhizo-co-terraform-provider-opsgenie'

serviceIncidentRule.ServiceIncidentRule.isTerraformResource(x: any)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isTerraformResource.parameter.x"></a>

- *Type:* any

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.node">node</a></code> | <code>constructs.Node</code> | The tree node. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.cdktfStack">cdktfStack</a></code> | <code>cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.friendlyUniqueId">friendlyUniqueId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.terraformMetaArguments">terraformMetaArguments</a></code> | <code>{[ key: string ]: any}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.terraformResourceType">terraformResourceType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.terraformGeneratorMetadata">terraformGeneratorMetadata</a></code> | <code>cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.connection">connection</a></code> | <code>cdktf.SSHProvisionerConnection \| cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.count">count</a></code> | <code>number \| cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.dependsOn">dependsOn</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.forEach">forEach</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.provisioners">provisioners</a></code> | <code>cdktf.FileProvisioner \| cdktf.LocalExecProvisioner \| cdktf.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.incidentRule">incidentRule</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList">ServiceIncidentRuleIncidentRuleList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.idInput">idInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.incidentRuleInput">incidentRuleInput</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule">ServiceIncidentRuleIncidentRule</a>[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.serviceIdInput">serviceIdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.id">id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.serviceId">serviceId</a></code> | <code>string</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.node"></a>

```typescript
public readonly node: Node;
```

- *Type:* constructs.Node

The tree node.

---

##### `cdktfStack`<sup>Required</sup> <a name="cdktfStack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.cdktfStack"></a>

```typescript
public readonly cdktfStack: TerraformStack;
```

- *Type:* cdktf.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `friendlyUniqueId`<sup>Required</sup> <a name="friendlyUniqueId" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.friendlyUniqueId"></a>

```typescript
public readonly friendlyUniqueId: string;
```

- *Type:* string

---

##### `terraformMetaArguments`<sup>Required</sup> <a name="terraformMetaArguments" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.terraformMetaArguments"></a>

```typescript
public readonly terraformMetaArguments: {[ key: string ]: any};
```

- *Type:* {[ key: string ]: any}

---

##### `terraformResourceType`<sup>Required</sup> <a name="terraformResourceType" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.terraformResourceType"></a>

```typescript
public readonly terraformResourceType: string;
```

- *Type:* string

---

##### `terraformGeneratorMetadata`<sup>Optional</sup> <a name="terraformGeneratorMetadata" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.terraformGeneratorMetadata"></a>

```typescript
public readonly terraformGeneratorMetadata: TerraformProviderGeneratorMetadata;
```

- *Type:* cdktf.TerraformProviderGeneratorMetadata

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.connection"></a>

```typescript
public readonly connection: SSHProvisionerConnection | WinrmProvisionerConnection;
```

- *Type:* cdktf.SSHProvisionerConnection | cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.count"></a>

```typescript
public readonly count: number | TerraformCount;
```

- *Type:* number | cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.dependsOn"></a>

```typescript
public readonly dependsOn: string[];
```

- *Type:* string[]

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.forEach"></a>

```typescript
public readonly forEach: ITerraformIterator;
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.provisioners"></a>

```typescript
public readonly provisioners: FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner[];
```

- *Type:* cdktf.FileProvisioner | cdktf.LocalExecProvisioner | cdktf.RemoteExecProvisioner[]

---

##### `incidentRule`<sup>Required</sup> <a name="incidentRule" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.incidentRule"></a>

```typescript
public readonly incidentRule: ServiceIncidentRuleIncidentRuleList;
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList">ServiceIncidentRuleIncidentRuleList</a>

---

##### `idInput`<sup>Optional</sup> <a name="idInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.idInput"></a>

```typescript
public readonly idInput: string;
```

- *Type:* string

---

##### `incidentRuleInput`<sup>Optional</sup> <a name="incidentRuleInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.incidentRuleInput"></a>

```typescript
public readonly incidentRuleInput: IResolvable | ServiceIncidentRuleIncidentRule[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule">ServiceIncidentRuleIncidentRule</a>[]

---

##### `serviceIdInput`<sup>Optional</sup> <a name="serviceIdInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.serviceIdInput"></a>

```typescript
public readonly serviceIdInput: string;
```

- *Type:* string

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

---

##### `serviceId`<sup>Required</sup> <a name="serviceId" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.serviceId"></a>

```typescript
public readonly serviceId: string;
```

- *Type:* string

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.tfResourceType">tfResourceType</a></code> | <code>string</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.tfResourceType"></a>

```typescript
public readonly tfResourceType: string;
```

- *Type:* string

---

## Structs <a name="Structs" id="Structs"></a>

### ServiceIncidentRuleConfig <a name="ServiceIncidentRuleConfig" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.Initializer"></a>

```typescript
import { serviceIncidentRule } from 'rhizo-co-terraform-provider-opsgenie'

const serviceIncidentRuleConfig: serviceIncidentRule.ServiceIncidentRuleConfig = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.connection">connection</a></code> | <code>cdktf.SSHProvisionerConnection \| cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.count">count</a></code> | <code>number \| cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.dependsOn">dependsOn</a></code> | <code>cdktf.ITerraformDependable[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.forEach">forEach</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.provisioners">provisioners</a></code> | <code>cdktf.FileProvisioner \| cdktf.LocalExecProvisioner \| cdktf.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.incidentRule">incidentRule</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule">ServiceIncidentRuleIncidentRule</a>[]</code> | incident_rule block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.serviceId">serviceId</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#service_id ServiceIncidentRule#service_id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.id">id</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#id ServiceIncidentRule#id}. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.connection"></a>

```typescript
public readonly connection: SSHProvisionerConnection | WinrmProvisionerConnection;
```

- *Type:* cdktf.SSHProvisionerConnection | cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.count"></a>

```typescript
public readonly count: number | TerraformCount;
```

- *Type:* number | cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.dependsOn"></a>

```typescript
public readonly dependsOn: ITerraformDependable[];
```

- *Type:* cdktf.ITerraformDependable[]

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.forEach"></a>

```typescript
public readonly forEach: ITerraformIterator;
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.provisioners"></a>

```typescript
public readonly provisioners: FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner[];
```

- *Type:* cdktf.FileProvisioner | cdktf.LocalExecProvisioner | cdktf.RemoteExecProvisioner[]

---

##### `incidentRule`<sup>Required</sup> <a name="incidentRule" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.incidentRule"></a>

```typescript
public readonly incidentRule: IResolvable | ServiceIncidentRuleIncidentRule[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule">ServiceIncidentRuleIncidentRule</a>[]

incident_rule block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#incident_rule ServiceIncidentRule#incident_rule}

---

##### `serviceId`<sup>Required</sup> <a name="serviceId" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.serviceId"></a>

```typescript
public readonly serviceId: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#service_id ServiceIncidentRule#service_id}.

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#id ServiceIncidentRule#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

### ServiceIncidentRuleIncidentRule <a name="ServiceIncidentRuleIncidentRule" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule.Initializer"></a>

```typescript
import { serviceIncidentRule } from 'rhizo-co-terraform-provider-opsgenie'

const serviceIncidentRuleIncidentRule: serviceIncidentRule.ServiceIncidentRuleIncidentRule = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule.property.incidentProperties">incidentProperties</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties">ServiceIncidentRuleIncidentRuleIncidentProperties</a>[]</code> | incident_properties block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule.property.conditionMatchType">conditionMatchType</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#condition_match_type ServiceIncidentRule#condition_match_type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule.property.conditions">conditions</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions">ServiceIncidentRuleIncidentRuleConditions</a>[]</code> | conditions block. |

---

##### `incidentProperties`<sup>Required</sup> <a name="incidentProperties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule.property.incidentProperties"></a>

```typescript
public readonly incidentProperties: IResolvable | ServiceIncidentRuleIncidentRuleIncidentProperties[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties">ServiceIncidentRuleIncidentRuleIncidentProperties</a>[]

incident_properties block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#incident_properties ServiceIncidentRule#incident_properties}

---

##### `conditionMatchType`<sup>Optional</sup> <a name="conditionMatchType" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule.property.conditionMatchType"></a>

```typescript
public readonly conditionMatchType: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#condition_match_type ServiceIncidentRule#condition_match_type}.

---

##### `conditions`<sup>Optional</sup> <a name="conditions" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule.property.conditions"></a>

```typescript
public readonly conditions: IResolvable | ServiceIncidentRuleIncidentRuleConditions[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions">ServiceIncidentRuleIncidentRuleConditions</a>[]

conditions block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#conditions ServiceIncidentRule#conditions}

---

### ServiceIncidentRuleIncidentRuleConditions <a name="ServiceIncidentRuleIncidentRuleConditions" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.Initializer"></a>

```typescript
import { serviceIncidentRule } from 'rhizo-co-terraform-provider-opsgenie'

const serviceIncidentRuleIncidentRuleConditions: serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.field">field</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#field ServiceIncidentRule#field}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.operation">operation</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#operation ServiceIncidentRule#operation}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.expectedValue">expectedValue</a></code> | <code>string</code> | User defined value that will be compared with alert field according to the operation. Default value is empty string. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.key">key</a></code> | <code>string</code> | If 'field' is set as 'extra-properties', key could be used for key-value pair. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.not">not</a></code> | <code>boolean \| cdktf.IResolvable</code> | Indicates behaviour of the given operation. Default value is false. |

---

##### `field`<sup>Required</sup> <a name="field" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.field"></a>

```typescript
public readonly field: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#field ServiceIncidentRule#field}.

---

##### `operation`<sup>Required</sup> <a name="operation" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.operation"></a>

```typescript
public readonly operation: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#operation ServiceIncidentRule#operation}.

---

##### `expectedValue`<sup>Optional</sup> <a name="expectedValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.expectedValue"></a>

```typescript
public readonly expectedValue: string;
```

- *Type:* string

User defined value that will be compared with alert field according to the operation. Default value is empty string.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#expected_value ServiceIncidentRule#expected_value}

---

##### `key`<sup>Optional</sup> <a name="key" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.key"></a>

```typescript
public readonly key: string;
```

- *Type:* string

If 'field' is set as 'extra-properties', key could be used for key-value pair.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#key ServiceIncidentRule#key}

---

##### `not`<sup>Optional</sup> <a name="not" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.not"></a>

```typescript
public readonly not: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

Indicates behaviour of the given operation. Default value is false.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#not ServiceIncidentRule#not}

---

### ServiceIncidentRuleIncidentRuleIncidentProperties <a name="ServiceIncidentRuleIncidentRuleIncidentProperties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.Initializer"></a>

```typescript
import { serviceIncidentRule } from 'rhizo-co-terraform-provider-opsgenie'

const serviceIncidentRuleIncidentRuleIncidentProperties: serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.message">message</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#message ServiceIncidentRule#message}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.priority">priority</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#priority ServiceIncidentRule#priority}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.stakeholderProperties">stakeholderProperties</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties">ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties</a>[]</code> | stakeholder_properties block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.description">description</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#description ServiceIncidentRule#description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.details">details</a></code> | <code>{[ key: string ]: string}</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#details ServiceIncidentRule#details}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.tags">tags</a></code> | <code>string[]</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#tags ServiceIncidentRule#tags}. |

---

##### `message`<sup>Required</sup> <a name="message" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.message"></a>

```typescript
public readonly message: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#message ServiceIncidentRule#message}.

---

##### `priority`<sup>Required</sup> <a name="priority" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.priority"></a>

```typescript
public readonly priority: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#priority ServiceIncidentRule#priority}.

---

##### `stakeholderProperties`<sup>Required</sup> <a name="stakeholderProperties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.stakeholderProperties"></a>

```typescript
public readonly stakeholderProperties: IResolvable | ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties">ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties</a>[]

stakeholder_properties block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#stakeholder_properties ServiceIncidentRule#stakeholder_properties}

---

##### `description`<sup>Optional</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.description"></a>

```typescript
public readonly description: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#description ServiceIncidentRule#description}.

---

##### `details`<sup>Optional</sup> <a name="details" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.details"></a>

```typescript
public readonly details: {[ key: string ]: string};
```

- *Type:* {[ key: string ]: string}

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#details ServiceIncidentRule#details}.

---

##### `tags`<sup>Optional</sup> <a name="tags" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.tags"></a>

```typescript
public readonly tags: string[];
```

- *Type:* string[]

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#tags ServiceIncidentRule#tags}.

---

### ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties <a name="ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties.Initializer"></a>

```typescript
import { serviceIncidentRule } from 'rhizo-co-terraform-provider-opsgenie'

const serviceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties: serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties.property.message">message</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#message ServiceIncidentRule#message}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties.property.description">description</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#description ServiceIncidentRule#description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties.property.enable">enable</a></code> | <code>boolean \| cdktf.IResolvable</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#enable ServiceIncidentRule#enable}. |

---

##### `message`<sup>Required</sup> <a name="message" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties.property.message"></a>

```typescript
public readonly message: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#message ServiceIncidentRule#message}.

---

##### `description`<sup>Optional</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties.property.description"></a>

```typescript
public readonly description: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#description ServiceIncidentRule#description}.

---

##### `enable`<sup>Optional</sup> <a name="enable" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties.property.enable"></a>

```typescript
public readonly enable: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#enable ServiceIncidentRule#enable}.

---

## Classes <a name="Classes" id="Classes"></a>

### ServiceIncidentRuleIncidentRuleConditionsList <a name="ServiceIncidentRuleIncidentRuleConditionsList" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.Initializer"></a>

```typescript
import { serviceIncidentRule } from 'rhizo-co-terraform-provider-opsgenie'

new serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.get"></a>

```typescript
public get(index: number): ServiceIncidentRuleIncidentRuleConditionsOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions">ServiceIncidentRuleIncidentRuleConditions</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | ServiceIncidentRuleIncidentRuleConditions[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions">ServiceIncidentRuleIncidentRuleConditions</a>[]

---


### ServiceIncidentRuleIncidentRuleConditionsOutputReference <a name="ServiceIncidentRuleIncidentRuleConditionsOutputReference" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer"></a>

```typescript
import { serviceIncidentRule } from 'rhizo-co-terraform-provider-opsgenie'

new serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.resetExpectedValue">resetExpectedValue</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.resetKey">resetKey</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.resetNot">resetNot</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetExpectedValue` <a name="resetExpectedValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.resetExpectedValue"></a>

```typescript
public resetExpectedValue(): void
```

##### `resetKey` <a name="resetKey" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.resetKey"></a>

```typescript
public resetKey(): void
```

##### `resetNot` <a name="resetNot" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.resetNot"></a>

```typescript
public resetNot(): void
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.expectedValueInput">expectedValueInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.fieldInput">fieldInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.keyInput">keyInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.notInput">notInput</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.operationInput">operationInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.expectedValue">expectedValue</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.field">field</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.key">key</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.not">not</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.operation">operation</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions">ServiceIncidentRuleIncidentRuleConditions</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `expectedValueInput`<sup>Optional</sup> <a name="expectedValueInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.expectedValueInput"></a>

```typescript
public readonly expectedValueInput: string;
```

- *Type:* string

---

##### `fieldInput`<sup>Optional</sup> <a name="fieldInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.fieldInput"></a>

```typescript
public readonly fieldInput: string;
```

- *Type:* string

---

##### `keyInput`<sup>Optional</sup> <a name="keyInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.keyInput"></a>

```typescript
public readonly keyInput: string;
```

- *Type:* string

---

##### `notInput`<sup>Optional</sup> <a name="notInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.notInput"></a>

```typescript
public readonly notInput: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `operationInput`<sup>Optional</sup> <a name="operationInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.operationInput"></a>

```typescript
public readonly operationInput: string;
```

- *Type:* string

---

##### `expectedValue`<sup>Required</sup> <a name="expectedValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.expectedValue"></a>

```typescript
public readonly expectedValue: string;
```

- *Type:* string

---

##### `field`<sup>Required</sup> <a name="field" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.field"></a>

```typescript
public readonly field: string;
```

- *Type:* string

---

##### `key`<sup>Required</sup> <a name="key" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.key"></a>

```typescript
public readonly key: string;
```

- *Type:* string

---

##### `not`<sup>Required</sup> <a name="not" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.not"></a>

```typescript
public readonly not: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `operation`<sup>Required</sup> <a name="operation" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.operation"></a>

```typescript
public readonly operation: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | ServiceIncidentRuleIncidentRuleConditions;
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions">ServiceIncidentRuleIncidentRuleConditions</a>

---


### ServiceIncidentRuleIncidentRuleIncidentPropertiesList <a name="ServiceIncidentRuleIncidentRuleIncidentPropertiesList" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.Initializer"></a>

```typescript
import { serviceIncidentRule } from 'rhizo-co-terraform-provider-opsgenie'

new serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.get"></a>

```typescript
public get(index: number): ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties">ServiceIncidentRuleIncidentRuleIncidentProperties</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | ServiceIncidentRuleIncidentRuleIncidentProperties[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties">ServiceIncidentRuleIncidentRuleIncidentProperties</a>[]

---


### ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference <a name="ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer"></a>

```typescript
import { serviceIncidentRule } from 'rhizo-co-terraform-provider-opsgenie'

new serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.putStakeholderProperties">putStakeholderProperties</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.resetDescription">resetDescription</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.resetDetails">resetDetails</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.resetTags">resetTags</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `putStakeholderProperties` <a name="putStakeholderProperties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.putStakeholderProperties"></a>

```typescript
public putStakeholderProperties(value: IResolvable | ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.putStakeholderProperties.parameter.value"></a>

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties">ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties</a>[]

---

##### `resetDescription` <a name="resetDescription" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.resetDescription"></a>

```typescript
public resetDescription(): void
```

##### `resetDetails` <a name="resetDetails" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.resetDetails"></a>

```typescript
public resetDetails(): void
```

##### `resetTags` <a name="resetTags" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.resetTags"></a>

```typescript
public resetTags(): void
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.stakeholderProperties">stakeholderProperties</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList">ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.descriptionInput">descriptionInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.detailsInput">detailsInput</a></code> | <code>{[ key: string ]: string}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.messageInput">messageInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.priorityInput">priorityInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.stakeholderPropertiesInput">stakeholderPropertiesInput</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties">ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties</a>[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.tagsInput">tagsInput</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.description">description</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.details">details</a></code> | <code>{[ key: string ]: string}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.message">message</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.priority">priority</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.tags">tags</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties">ServiceIncidentRuleIncidentRuleIncidentProperties</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `stakeholderProperties`<sup>Required</sup> <a name="stakeholderProperties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.stakeholderProperties"></a>

```typescript
public readonly stakeholderProperties: ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList;
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList">ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList</a>

---

##### `descriptionInput`<sup>Optional</sup> <a name="descriptionInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.descriptionInput"></a>

```typescript
public readonly descriptionInput: string;
```

- *Type:* string

---

##### `detailsInput`<sup>Optional</sup> <a name="detailsInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.detailsInput"></a>

```typescript
public readonly detailsInput: {[ key: string ]: string};
```

- *Type:* {[ key: string ]: string}

---

##### `messageInput`<sup>Optional</sup> <a name="messageInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.messageInput"></a>

```typescript
public readonly messageInput: string;
```

- *Type:* string

---

##### `priorityInput`<sup>Optional</sup> <a name="priorityInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.priorityInput"></a>

```typescript
public readonly priorityInput: string;
```

- *Type:* string

---

##### `stakeholderPropertiesInput`<sup>Optional</sup> <a name="stakeholderPropertiesInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.stakeholderPropertiesInput"></a>

```typescript
public readonly stakeholderPropertiesInput: IResolvable | ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties">ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties</a>[]

---

##### `tagsInput`<sup>Optional</sup> <a name="tagsInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.tagsInput"></a>

```typescript
public readonly tagsInput: string[];
```

- *Type:* string[]

---

##### `description`<sup>Required</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.description"></a>

```typescript
public readonly description: string;
```

- *Type:* string

---

##### `details`<sup>Required</sup> <a name="details" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.details"></a>

```typescript
public readonly details: {[ key: string ]: string};
```

- *Type:* {[ key: string ]: string}

---

##### `message`<sup>Required</sup> <a name="message" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.message"></a>

```typescript
public readonly message: string;
```

- *Type:* string

---

##### `priority`<sup>Required</sup> <a name="priority" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.priority"></a>

```typescript
public readonly priority: string;
```

- *Type:* string

---

##### `tags`<sup>Required</sup> <a name="tags" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.tags"></a>

```typescript
public readonly tags: string[];
```

- *Type:* string[]

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | ServiceIncidentRuleIncidentRuleIncidentProperties;
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties">ServiceIncidentRuleIncidentRuleIncidentProperties</a>

---


### ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList <a name="ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.Initializer"></a>

```typescript
import { serviceIncidentRule } from 'rhizo-co-terraform-provider-opsgenie'

new serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.get"></a>

```typescript
public get(index: number): ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties">ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties">ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties</a>[]

---


### ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference <a name="ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer"></a>

```typescript
import { serviceIncidentRule } from 'rhizo-co-terraform-provider-opsgenie'

new serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.resetDescription">resetDescription</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.resetEnable">resetEnable</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetDescription` <a name="resetDescription" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.resetDescription"></a>

```typescript
public resetDescription(): void
```

##### `resetEnable` <a name="resetEnable" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.resetEnable"></a>

```typescript
public resetEnable(): void
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.descriptionInput">descriptionInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.enableInput">enableInput</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.messageInput">messageInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.description">description</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.enable">enable</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.message">message</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties">ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `descriptionInput`<sup>Optional</sup> <a name="descriptionInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.descriptionInput"></a>

```typescript
public readonly descriptionInput: string;
```

- *Type:* string

---

##### `enableInput`<sup>Optional</sup> <a name="enableInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.enableInput"></a>

```typescript
public readonly enableInput: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `messageInput`<sup>Optional</sup> <a name="messageInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.messageInput"></a>

```typescript
public readonly messageInput: string;
```

- *Type:* string

---

##### `description`<sup>Required</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.description"></a>

```typescript
public readonly description: string;
```

- *Type:* string

---

##### `enable`<sup>Required</sup> <a name="enable" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.enable"></a>

```typescript
public readonly enable: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `message`<sup>Required</sup> <a name="message" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.message"></a>

```typescript
public readonly message: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties;
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties">ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties</a>

---


### ServiceIncidentRuleIncidentRuleList <a name="ServiceIncidentRuleIncidentRuleList" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.Initializer"></a>

```typescript
import { serviceIncidentRule } from 'rhizo-co-terraform-provider-opsgenie'

new serviceIncidentRule.ServiceIncidentRuleIncidentRuleList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.get"></a>

```typescript
public get(index: number): ServiceIncidentRuleIncidentRuleOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule">ServiceIncidentRuleIncidentRule</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | ServiceIncidentRuleIncidentRule[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule">ServiceIncidentRuleIncidentRule</a>[]

---


### ServiceIncidentRuleIncidentRuleOutputReference <a name="ServiceIncidentRuleIncidentRuleOutputReference" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer"></a>

```typescript
import { serviceIncidentRule } from 'rhizo-co-terraform-provider-opsgenie'

new serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.putConditions">putConditions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.putIncidentProperties">putIncidentProperties</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.resetConditionMatchType">resetConditionMatchType</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.resetConditions">resetConditions</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `putConditions` <a name="putConditions" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.putConditions"></a>

```typescript
public putConditions(value: IResolvable | ServiceIncidentRuleIncidentRuleConditions[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.putConditions.parameter.value"></a>

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions">ServiceIncidentRuleIncidentRuleConditions</a>[]

---

##### `putIncidentProperties` <a name="putIncidentProperties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.putIncidentProperties"></a>

```typescript
public putIncidentProperties(value: IResolvable | ServiceIncidentRuleIncidentRuleIncidentProperties[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.putIncidentProperties.parameter.value"></a>

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties">ServiceIncidentRuleIncidentRuleIncidentProperties</a>[]

---

##### `resetConditionMatchType` <a name="resetConditionMatchType" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.resetConditionMatchType"></a>

```typescript
public resetConditionMatchType(): void
```

##### `resetConditions` <a name="resetConditions" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.resetConditions"></a>

```typescript
public resetConditions(): void
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditions">conditions</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList">ServiceIncidentRuleIncidentRuleConditionsList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.incidentProperties">incidentProperties</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList">ServiceIncidentRuleIncidentRuleIncidentPropertiesList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditionMatchTypeInput">conditionMatchTypeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditionsInput">conditionsInput</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions">ServiceIncidentRuleIncidentRuleConditions</a>[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.incidentPropertiesInput">incidentPropertiesInput</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties">ServiceIncidentRuleIncidentRuleIncidentProperties</a>[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditionMatchType">conditionMatchType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule">ServiceIncidentRuleIncidentRule</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `conditions`<sup>Required</sup> <a name="conditions" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditions"></a>

```typescript
public readonly conditions: ServiceIncidentRuleIncidentRuleConditionsList;
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList">ServiceIncidentRuleIncidentRuleConditionsList</a>

---

##### `incidentProperties`<sup>Required</sup> <a name="incidentProperties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.incidentProperties"></a>

```typescript
public readonly incidentProperties: ServiceIncidentRuleIncidentRuleIncidentPropertiesList;
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList">ServiceIncidentRuleIncidentRuleIncidentPropertiesList</a>

---

##### `conditionMatchTypeInput`<sup>Optional</sup> <a name="conditionMatchTypeInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditionMatchTypeInput"></a>

```typescript
public readonly conditionMatchTypeInput: string;
```

- *Type:* string

---

##### `conditionsInput`<sup>Optional</sup> <a name="conditionsInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditionsInput"></a>

```typescript
public readonly conditionsInput: IResolvable | ServiceIncidentRuleIncidentRuleConditions[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions">ServiceIncidentRuleIncidentRuleConditions</a>[]

---

##### `incidentPropertiesInput`<sup>Optional</sup> <a name="incidentPropertiesInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.incidentPropertiesInput"></a>

```typescript
public readonly incidentPropertiesInput: IResolvable | ServiceIncidentRuleIncidentRuleIncidentProperties[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties">ServiceIncidentRuleIncidentRuleIncidentProperties</a>[]

---

##### `conditionMatchType`<sup>Required</sup> <a name="conditionMatchType" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditionMatchType"></a>

```typescript
public readonly conditionMatchType: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | ServiceIncidentRuleIncidentRule;
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule">ServiceIncidentRuleIncidentRule</a>

---



