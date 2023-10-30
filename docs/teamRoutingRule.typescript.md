# `opsgenie_team_routing_rule`

Refer to the Terraform Registory for docs: [`opsgenie_team_routing_rule`](https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule).

# `teamRoutingRule` Submodule <a name="`teamRoutingRule` Submodule" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### TeamRoutingRule <a name="TeamRoutingRule" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule"></a>

Represents a {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule opsgenie_team_routing_rule}.

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer"></a>

```typescript
import { teamRoutingRule } from 'rhizo-co-terraform-provider-opsgenie'

new teamRoutingRule.TeamRoutingRule(scope: Construct, id: string, config: TeamRoutingRuleConfig)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.id">id</a></code> | <code>string</code> | The scoped construct ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.config">config</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig">TeamRoutingRuleConfig</a></code> | *No description.* |

---

##### `scope`<sup>Required</sup> <a name="scope" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.id"></a>

- *Type:* string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Required</sup> <a name="config" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.config"></a>

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig">TeamRoutingRuleConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.toString">toString</a></code> | Returns a string representation of this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.addOverride">addOverride</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.overrideLogicalId">overrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetOverrideLogicalId">resetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.toMetadata">toMetadata</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.toTerraform">toTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putCriteria">putCriteria</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putNotify">putNotify</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putTimeRestriction">putTimeRestriction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetCriteria">resetCriteria</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetId">resetId</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetIsDefault">resetIsDefault</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetName">resetName</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetOrder">resetOrder</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetTimeRestriction">resetTimeRestriction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetTimezone">resetTimezone</a></code> | *No description.* |

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.toString"></a>

```typescript
public toString(): string
```

Returns a string representation of this construct.

##### `addOverride` <a name="addOverride" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.addOverride"></a>

```typescript
public addOverride(path: string, value: any): void
```

###### `path`<sup>Required</sup> <a name="path" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.addOverride.parameter.path"></a>

- *Type:* string

---

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.addOverride.parameter.value"></a>

- *Type:* any

---

##### `overrideLogicalId` <a name="overrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.overrideLogicalId"></a>

```typescript
public overrideLogicalId(newLogicalId: string): void
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* string

The new logical ID to use for this stack element.

---

##### `resetOverrideLogicalId` <a name="resetOverrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetOverrideLogicalId"></a>

```typescript
public resetOverrideLogicalId(): void
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `toMetadata` <a name="toMetadata" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.toMetadata"></a>

```typescript
public toMetadata(): any
```

##### `toTerraform` <a name="toTerraform" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.toTerraform"></a>

```typescript
public toTerraform(): any
```

Adds this resource to the terraform JSON output.

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `putCriteria` <a name="putCriteria" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putCriteria"></a>

```typescript
public putCriteria(value: IResolvable | TeamRoutingRuleCriteria[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putCriteria.parameter.value"></a>

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria">TeamRoutingRuleCriteria</a>[]

---

##### `putNotify` <a name="putNotify" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putNotify"></a>

```typescript
public putNotify(value: IResolvable | TeamRoutingRuleNotify[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putNotify.parameter.value"></a>

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify">TeamRoutingRuleNotify</a>[]

---

##### `putTimeRestriction` <a name="putTimeRestriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putTimeRestriction"></a>

```typescript
public putTimeRestriction(value: IResolvable | TeamRoutingRuleTimeRestriction[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putTimeRestriction.parameter.value"></a>

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction">TeamRoutingRuleTimeRestriction</a>[]

---

##### `resetCriteria` <a name="resetCriteria" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetCriteria"></a>

```typescript
public resetCriteria(): void
```

##### `resetId` <a name="resetId" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetId"></a>

```typescript
public resetId(): void
```

##### `resetIsDefault` <a name="resetIsDefault" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetIsDefault"></a>

```typescript
public resetIsDefault(): void
```

##### `resetName` <a name="resetName" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetName"></a>

```typescript
public resetName(): void
```

##### `resetOrder` <a name="resetOrder" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetOrder"></a>

```typescript
public resetOrder(): void
```

##### `resetTimeRestriction` <a name="resetTimeRestriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetTimeRestriction"></a>

```typescript
public resetTimeRestriction(): void
```

##### `resetTimezone` <a name="resetTimezone" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetTimezone"></a>

```typescript
public resetTimezone(): void
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isConstruct">isConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isTerraformElement">isTerraformElement</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isTerraformResource">isTerraformResource</a></code> | *No description.* |

---

##### `isConstruct` <a name="isConstruct" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isConstruct"></a>

```typescript
import { teamRoutingRule } from 'rhizo-co-terraform-provider-opsgenie'

teamRoutingRule.TeamRoutingRule.isConstruct(x: any)
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

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isConstruct.parameter.x"></a>

- *Type:* any

Any object.

---

##### `isTerraformElement` <a name="isTerraformElement" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isTerraformElement"></a>

```typescript
import { teamRoutingRule } from 'rhizo-co-terraform-provider-opsgenie'

teamRoutingRule.TeamRoutingRule.isTerraformElement(x: any)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isTerraformElement.parameter.x"></a>

- *Type:* any

---

##### `isTerraformResource` <a name="isTerraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isTerraformResource"></a>

```typescript
import { teamRoutingRule } from 'rhizo-co-terraform-provider-opsgenie'

teamRoutingRule.TeamRoutingRule.isTerraformResource(x: any)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isTerraformResource.parameter.x"></a>

- *Type:* any

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.node">node</a></code> | <code>constructs.Node</code> | The tree node. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.cdktfStack">cdktfStack</a></code> | <code>cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.friendlyUniqueId">friendlyUniqueId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.terraformMetaArguments">terraformMetaArguments</a></code> | <code>{[ key: string ]: any}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.terraformResourceType">terraformResourceType</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.terraformGeneratorMetadata">terraformGeneratorMetadata</a></code> | <code>cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.connection">connection</a></code> | <code>cdktf.SSHProvisionerConnection \| cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.count">count</a></code> | <code>number \| cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.dependsOn">dependsOn</a></code> | <code>string[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.forEach">forEach</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.provisioners">provisioners</a></code> | <code>cdktf.FileProvisioner \| cdktf.LocalExecProvisioner \| cdktf.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.criteria">criteria</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList">TeamRoutingRuleCriteriaList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.notify">notify</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList">TeamRoutingRuleNotifyList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timeRestriction">timeRestriction</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList">TeamRoutingRuleTimeRestrictionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.criteriaInput">criteriaInput</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria">TeamRoutingRuleCriteria</a>[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.idInput">idInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.isDefaultInput">isDefaultInput</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.nameInput">nameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.notifyInput">notifyInput</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify">TeamRoutingRuleNotify</a>[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.orderInput">orderInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.teamIdInput">teamIdInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timeRestrictionInput">timeRestrictionInput</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction">TeamRoutingRuleTimeRestriction</a>[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timezoneInput">timezoneInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.id">id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.isDefault">isDefault</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.name">name</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.order">order</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.teamId">teamId</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timezone">timezone</a></code> | <code>string</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.node"></a>

```typescript
public readonly node: Node;
```

- *Type:* constructs.Node

The tree node.

---

##### `cdktfStack`<sup>Required</sup> <a name="cdktfStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.cdktfStack"></a>

```typescript
public readonly cdktfStack: TerraformStack;
```

- *Type:* cdktf.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `friendlyUniqueId`<sup>Required</sup> <a name="friendlyUniqueId" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.friendlyUniqueId"></a>

```typescript
public readonly friendlyUniqueId: string;
```

- *Type:* string

---

##### `terraformMetaArguments`<sup>Required</sup> <a name="terraformMetaArguments" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.terraformMetaArguments"></a>

```typescript
public readonly terraformMetaArguments: {[ key: string ]: any};
```

- *Type:* {[ key: string ]: any}

---

##### `terraformResourceType`<sup>Required</sup> <a name="terraformResourceType" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.terraformResourceType"></a>

```typescript
public readonly terraformResourceType: string;
```

- *Type:* string

---

##### `terraformGeneratorMetadata`<sup>Optional</sup> <a name="terraformGeneratorMetadata" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.terraformGeneratorMetadata"></a>

```typescript
public readonly terraformGeneratorMetadata: TerraformProviderGeneratorMetadata;
```

- *Type:* cdktf.TerraformProviderGeneratorMetadata

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.connection"></a>

```typescript
public readonly connection: SSHProvisionerConnection | WinrmProvisionerConnection;
```

- *Type:* cdktf.SSHProvisionerConnection | cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.count"></a>

```typescript
public readonly count: number | TerraformCount;
```

- *Type:* number | cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.dependsOn"></a>

```typescript
public readonly dependsOn: string[];
```

- *Type:* string[]

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.forEach"></a>

```typescript
public readonly forEach: ITerraformIterator;
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.provisioners"></a>

```typescript
public readonly provisioners: FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner[];
```

- *Type:* cdktf.FileProvisioner | cdktf.LocalExecProvisioner | cdktf.RemoteExecProvisioner[]

---

##### `criteria`<sup>Required</sup> <a name="criteria" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.criteria"></a>

```typescript
public readonly criteria: TeamRoutingRuleCriteriaList;
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList">TeamRoutingRuleCriteriaList</a>

---

##### `notify`<sup>Required</sup> <a name="notify" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.notify"></a>

```typescript
public readonly notify: TeamRoutingRuleNotifyList;
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList">TeamRoutingRuleNotifyList</a>

---

##### `timeRestriction`<sup>Required</sup> <a name="timeRestriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timeRestriction"></a>

```typescript
public readonly timeRestriction: TeamRoutingRuleTimeRestrictionList;
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList">TeamRoutingRuleTimeRestrictionList</a>

---

##### `criteriaInput`<sup>Optional</sup> <a name="criteriaInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.criteriaInput"></a>

```typescript
public readonly criteriaInput: IResolvable | TeamRoutingRuleCriteria[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria">TeamRoutingRuleCriteria</a>[]

---

##### `idInput`<sup>Optional</sup> <a name="idInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.idInput"></a>

```typescript
public readonly idInput: string;
```

- *Type:* string

---

##### `isDefaultInput`<sup>Optional</sup> <a name="isDefaultInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.isDefaultInput"></a>

```typescript
public readonly isDefaultInput: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `nameInput`<sup>Optional</sup> <a name="nameInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.nameInput"></a>

```typescript
public readonly nameInput: string;
```

- *Type:* string

---

##### `notifyInput`<sup>Optional</sup> <a name="notifyInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.notifyInput"></a>

```typescript
public readonly notifyInput: IResolvable | TeamRoutingRuleNotify[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify">TeamRoutingRuleNotify</a>[]

---

##### `orderInput`<sup>Optional</sup> <a name="orderInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.orderInput"></a>

```typescript
public readonly orderInput: number;
```

- *Type:* number

---

##### `teamIdInput`<sup>Optional</sup> <a name="teamIdInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.teamIdInput"></a>

```typescript
public readonly teamIdInput: string;
```

- *Type:* string

---

##### `timeRestrictionInput`<sup>Optional</sup> <a name="timeRestrictionInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timeRestrictionInput"></a>

```typescript
public readonly timeRestrictionInput: IResolvable | TeamRoutingRuleTimeRestriction[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction">TeamRoutingRuleTimeRestriction</a>[]

---

##### `timezoneInput`<sup>Optional</sup> <a name="timezoneInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timezoneInput"></a>

```typescript
public readonly timezoneInput: string;
```

- *Type:* string

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

---

##### `isDefault`<sup>Required</sup> <a name="isDefault" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.isDefault"></a>

```typescript
public readonly isDefault: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.name"></a>

```typescript
public readonly name: string;
```

- *Type:* string

---

##### `order`<sup>Required</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.order"></a>

```typescript
public readonly order: number;
```

- *Type:* number

---

##### `teamId`<sup>Required</sup> <a name="teamId" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.teamId"></a>

```typescript
public readonly teamId: string;
```

- *Type:* string

---

##### `timezone`<sup>Required</sup> <a name="timezone" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timezone"></a>

```typescript
public readonly timezone: string;
```

- *Type:* string

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.tfResourceType">tfResourceType</a></code> | <code>string</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.tfResourceType"></a>

```typescript
public readonly tfResourceType: string;
```

- *Type:* string

---

## Structs <a name="Structs" id="Structs"></a>

### TeamRoutingRuleConfig <a name="TeamRoutingRuleConfig" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.Initializer"></a>

```typescript
import { teamRoutingRule } from 'rhizo-co-terraform-provider-opsgenie'

const teamRoutingRuleConfig: teamRoutingRule.TeamRoutingRuleConfig = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.connection">connection</a></code> | <code>cdktf.SSHProvisionerConnection \| cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.count">count</a></code> | <code>number \| cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.dependsOn">dependsOn</a></code> | <code>cdktf.ITerraformDependable[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.forEach">forEach</a></code> | <code>cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.lifecycle">lifecycle</a></code> | <code>cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.provider">provider</a></code> | <code>cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.provisioners">provisioners</a></code> | <code>cdktf.FileProvisioner \| cdktf.LocalExecProvisioner \| cdktf.RemoteExecProvisioner[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.notify">notify</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify">TeamRoutingRuleNotify</a>[]</code> | notify block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.teamId">teamId</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#team_id TeamRoutingRule#team_id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.criteria">criteria</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria">TeamRoutingRuleCriteria</a>[]</code> | criteria block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.id">id</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#id TeamRoutingRule#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.isDefault">isDefault</a></code> | <code>boolean \| cdktf.IResolvable</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#is_default TeamRoutingRule#is_default}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.name">name</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#name TeamRoutingRule#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.order">order</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#order TeamRoutingRule#order}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.timeRestriction">timeRestriction</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction">TeamRoutingRuleTimeRestriction</a>[]</code> | time_restriction block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.timezone">timezone</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#timezone TeamRoutingRule#timezone}. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.connection"></a>

```typescript
public readonly connection: SSHProvisionerConnection | WinrmProvisionerConnection;
```

- *Type:* cdktf.SSHProvisionerConnection | cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.count"></a>

```typescript
public readonly count: number | TerraformCount;
```

- *Type:* number | cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.dependsOn"></a>

```typescript
public readonly dependsOn: ITerraformDependable[];
```

- *Type:* cdktf.ITerraformDependable[]

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.forEach"></a>

```typescript
public readonly forEach: ITerraformIterator;
```

- *Type:* cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.provisioners"></a>

```typescript
public readonly provisioners: FileProvisioner | LocalExecProvisioner | RemoteExecProvisioner[];
```

- *Type:* cdktf.FileProvisioner | cdktf.LocalExecProvisioner | cdktf.RemoteExecProvisioner[]

---

##### `notify`<sup>Required</sup> <a name="notify" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.notify"></a>

```typescript
public readonly notify: IResolvable | TeamRoutingRuleNotify[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify">TeamRoutingRuleNotify</a>[]

notify block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#notify TeamRoutingRule#notify}

---

##### `teamId`<sup>Required</sup> <a name="teamId" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.teamId"></a>

```typescript
public readonly teamId: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#team_id TeamRoutingRule#team_id}.

---

##### `criteria`<sup>Optional</sup> <a name="criteria" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.criteria"></a>

```typescript
public readonly criteria: IResolvable | TeamRoutingRuleCriteria[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria">TeamRoutingRuleCriteria</a>[]

criteria block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#criteria TeamRoutingRule#criteria}

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#id TeamRoutingRule#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `isDefault`<sup>Optional</sup> <a name="isDefault" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.isDefault"></a>

```typescript
public readonly isDefault: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#is_default TeamRoutingRule#is_default}.

---

##### `name`<sup>Optional</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.name"></a>

```typescript
public readonly name: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#name TeamRoutingRule#name}.

---

##### `order`<sup>Optional</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.order"></a>

```typescript
public readonly order: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#order TeamRoutingRule#order}.

---

##### `timeRestriction`<sup>Optional</sup> <a name="timeRestriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.timeRestriction"></a>

```typescript
public readonly timeRestriction: IResolvable | TeamRoutingRuleTimeRestriction[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction">TeamRoutingRuleTimeRestriction</a>[]

time_restriction block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#time_restriction TeamRoutingRule#time_restriction}

---

##### `timezone`<sup>Optional</sup> <a name="timezone" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.timezone"></a>

```typescript
public readonly timezone: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#timezone TeamRoutingRule#timezone}.

---

### TeamRoutingRuleCriteria <a name="TeamRoutingRuleCriteria" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria.Initializer"></a>

```typescript
import { teamRoutingRule } from 'rhizo-co-terraform-provider-opsgenie'

const teamRoutingRuleCriteria: teamRoutingRule.TeamRoutingRuleCriteria = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria.property.type">type</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#type TeamRoutingRule#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria.property.conditions">conditions</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions">TeamRoutingRuleCriteriaConditions</a>[]</code> | conditions block. |

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria.property.type"></a>

```typescript
public readonly type: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#type TeamRoutingRule#type}.

---

##### `conditions`<sup>Optional</sup> <a name="conditions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria.property.conditions"></a>

```typescript
public readonly conditions: IResolvable | TeamRoutingRuleCriteriaConditions[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions">TeamRoutingRuleCriteriaConditions</a>[]

conditions block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#conditions TeamRoutingRule#conditions}

---

### TeamRoutingRuleCriteriaConditions <a name="TeamRoutingRuleCriteriaConditions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.Initializer"></a>

```typescript
import { teamRoutingRule } from 'rhizo-co-terraform-provider-opsgenie'

const teamRoutingRuleCriteriaConditions: teamRoutingRule.TeamRoutingRuleCriteriaConditions = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.field">field</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#field TeamRoutingRule#field}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.operation">operation</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#operation TeamRoutingRule#operation}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.expectedValue">expectedValue</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#expected_value TeamRoutingRule#expected_value}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.key">key</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#key TeamRoutingRule#key}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.not">not</a></code> | <code>boolean \| cdktf.IResolvable</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#not TeamRoutingRule#not}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.order">order</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#order TeamRoutingRule#order}. |

---

##### `field`<sup>Required</sup> <a name="field" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.field"></a>

```typescript
public readonly field: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#field TeamRoutingRule#field}.

---

##### `operation`<sup>Required</sup> <a name="operation" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.operation"></a>

```typescript
public readonly operation: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#operation TeamRoutingRule#operation}.

---

##### `expectedValue`<sup>Optional</sup> <a name="expectedValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.expectedValue"></a>

```typescript
public readonly expectedValue: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#expected_value TeamRoutingRule#expected_value}.

---

##### `key`<sup>Optional</sup> <a name="key" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.key"></a>

```typescript
public readonly key: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#key TeamRoutingRule#key}.

---

##### `not`<sup>Optional</sup> <a name="not" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.not"></a>

```typescript
public readonly not: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#not TeamRoutingRule#not}.

---

##### `order`<sup>Optional</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.order"></a>

```typescript
public readonly order: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#order TeamRoutingRule#order}.

---

### TeamRoutingRuleNotify <a name="TeamRoutingRuleNotify" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify.Initializer"></a>

```typescript
import { teamRoutingRule } from 'rhizo-co-terraform-provider-opsgenie'

const teamRoutingRuleNotify: teamRoutingRule.TeamRoutingRuleNotify = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify.property.type">type</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#type TeamRoutingRule#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify.property.id">id</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#id TeamRoutingRule#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify.property.name">name</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#name TeamRoutingRule#name}. |

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify.property.type"></a>

```typescript
public readonly type: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#type TeamRoutingRule#type}.

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#id TeamRoutingRule#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `name`<sup>Optional</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify.property.name"></a>

```typescript
public readonly name: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#name TeamRoutingRule#name}.

---

### TeamRoutingRuleTimeRestriction <a name="TeamRoutingRuleTimeRestriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction.Initializer"></a>

```typescript
import { teamRoutingRule } from 'rhizo-co-terraform-provider-opsgenie'

const teamRoutingRuleTimeRestriction: teamRoutingRule.TeamRoutingRuleTimeRestriction = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction.property.type">type</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#type TeamRoutingRule#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction.property.restriction">restriction</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction">TeamRoutingRuleTimeRestrictionRestriction</a>[]</code> | restriction block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction.property.restrictions">restrictions</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions">TeamRoutingRuleTimeRestrictionRestrictions</a>[]</code> | restrictions block. |

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction.property.type"></a>

```typescript
public readonly type: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#type TeamRoutingRule#type}.

---

##### `restriction`<sup>Optional</sup> <a name="restriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction.property.restriction"></a>

```typescript
public readonly restriction: IResolvable | TeamRoutingRuleTimeRestrictionRestriction[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction">TeamRoutingRuleTimeRestrictionRestriction</a>[]

restriction block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#restriction TeamRoutingRule#restriction}

---

##### `restrictions`<sup>Optional</sup> <a name="restrictions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction.property.restrictions"></a>

```typescript
public readonly restrictions: IResolvable | TeamRoutingRuleTimeRestrictionRestrictions[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions">TeamRoutingRuleTimeRestrictionRestrictions</a>[]

restrictions block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#restrictions TeamRoutingRule#restrictions}

---

### TeamRoutingRuleTimeRestrictionRestriction <a name="TeamRoutingRuleTimeRestrictionRestriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.Initializer"></a>

```typescript
import { teamRoutingRule } from 'rhizo-co-terraform-provider-opsgenie'

const teamRoutingRuleTimeRestrictionRestriction: teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.endHour">endHour</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_hour TeamRoutingRule#end_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.endMin">endMin</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_min TeamRoutingRule#end_min}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.startHour">startHour</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_hour TeamRoutingRule#start_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.startMin">startMin</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_min TeamRoutingRule#start_min}. |

---

##### `endHour`<sup>Required</sup> <a name="endHour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.endHour"></a>

```typescript
public readonly endHour: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_hour TeamRoutingRule#end_hour}.

---

##### `endMin`<sup>Required</sup> <a name="endMin" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.endMin"></a>

```typescript
public readonly endMin: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_min TeamRoutingRule#end_min}.

---

##### `startHour`<sup>Required</sup> <a name="startHour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.startHour"></a>

```typescript
public readonly startHour: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_hour TeamRoutingRule#start_hour}.

---

##### `startMin`<sup>Required</sup> <a name="startMin" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.startMin"></a>

```typescript
public readonly startMin: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_min TeamRoutingRule#start_min}.

---

### TeamRoutingRuleTimeRestrictionRestrictions <a name="TeamRoutingRuleTimeRestrictionRestrictions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.Initializer"></a>

```typescript
import { teamRoutingRule } from 'rhizo-co-terraform-provider-opsgenie'

const teamRoutingRuleTimeRestrictionRestrictions: teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions = { ... }
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.endDay">endDay</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_day TeamRoutingRule#end_day}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.endHour">endHour</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_hour TeamRoutingRule#end_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.endMin">endMin</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_min TeamRoutingRule#end_min}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.startDay">startDay</a></code> | <code>string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_day TeamRoutingRule#start_day}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.startHour">startHour</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_hour TeamRoutingRule#start_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.startMin">startMin</a></code> | <code>number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_min TeamRoutingRule#start_min}. |

---

##### `endDay`<sup>Required</sup> <a name="endDay" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.endDay"></a>

```typescript
public readonly endDay: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_day TeamRoutingRule#end_day}.

---

##### `endHour`<sup>Required</sup> <a name="endHour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.endHour"></a>

```typescript
public readonly endHour: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_hour TeamRoutingRule#end_hour}.

---

##### `endMin`<sup>Required</sup> <a name="endMin" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.endMin"></a>

```typescript
public readonly endMin: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_min TeamRoutingRule#end_min}.

---

##### `startDay`<sup>Required</sup> <a name="startDay" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.startDay"></a>

```typescript
public readonly startDay: string;
```

- *Type:* string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_day TeamRoutingRule#start_day}.

---

##### `startHour`<sup>Required</sup> <a name="startHour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.startHour"></a>

```typescript
public readonly startHour: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_hour TeamRoutingRule#start_hour}.

---

##### `startMin`<sup>Required</sup> <a name="startMin" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.startMin"></a>

```typescript
public readonly startMin: number;
```

- *Type:* number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_min TeamRoutingRule#start_min}.

---

## Classes <a name="Classes" id="Classes"></a>

### TeamRoutingRuleCriteriaConditionsList <a name="TeamRoutingRuleCriteriaConditionsList" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.Initializer"></a>

```typescript
import { teamRoutingRule } from 'rhizo-co-terraform-provider-opsgenie'

new teamRoutingRule.TeamRoutingRuleCriteriaConditionsList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.get"></a>

```typescript
public get(index: number): TeamRoutingRuleCriteriaConditionsOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions">TeamRoutingRuleCriteriaConditions</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | TeamRoutingRuleCriteriaConditions[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions">TeamRoutingRuleCriteriaConditions</a>[]

---


### TeamRoutingRuleCriteriaConditionsOutputReference <a name="TeamRoutingRuleCriteriaConditionsOutputReference" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer"></a>

```typescript
import { teamRoutingRule } from 'rhizo-co-terraform-provider-opsgenie'

new teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resetExpectedValue">resetExpectedValue</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resetKey">resetKey</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resetNot">resetNot</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resetOrder">resetOrder</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetExpectedValue` <a name="resetExpectedValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resetExpectedValue"></a>

```typescript
public resetExpectedValue(): void
```

##### `resetKey` <a name="resetKey" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resetKey"></a>

```typescript
public resetKey(): void
```

##### `resetNot` <a name="resetNot" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resetNot"></a>

```typescript
public resetNot(): void
```

##### `resetOrder` <a name="resetOrder" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resetOrder"></a>

```typescript
public resetOrder(): void
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.expectedValueInput">expectedValueInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.fieldInput">fieldInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.keyInput">keyInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.notInput">notInput</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.operationInput">operationInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.orderInput">orderInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.expectedValue">expectedValue</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.field">field</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.key">key</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.not">not</a></code> | <code>boolean \| cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.operation">operation</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.order">order</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions">TeamRoutingRuleCriteriaConditions</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `expectedValueInput`<sup>Optional</sup> <a name="expectedValueInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.expectedValueInput"></a>

```typescript
public readonly expectedValueInput: string;
```

- *Type:* string

---

##### `fieldInput`<sup>Optional</sup> <a name="fieldInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.fieldInput"></a>

```typescript
public readonly fieldInput: string;
```

- *Type:* string

---

##### `keyInput`<sup>Optional</sup> <a name="keyInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.keyInput"></a>

```typescript
public readonly keyInput: string;
```

- *Type:* string

---

##### `notInput`<sup>Optional</sup> <a name="notInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.notInput"></a>

```typescript
public readonly notInput: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `operationInput`<sup>Optional</sup> <a name="operationInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.operationInput"></a>

```typescript
public readonly operationInput: string;
```

- *Type:* string

---

##### `orderInput`<sup>Optional</sup> <a name="orderInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.orderInput"></a>

```typescript
public readonly orderInput: number;
```

- *Type:* number

---

##### `expectedValue`<sup>Required</sup> <a name="expectedValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.expectedValue"></a>

```typescript
public readonly expectedValue: string;
```

- *Type:* string

---

##### `field`<sup>Required</sup> <a name="field" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.field"></a>

```typescript
public readonly field: string;
```

- *Type:* string

---

##### `key`<sup>Required</sup> <a name="key" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.key"></a>

```typescript
public readonly key: string;
```

- *Type:* string

---

##### `not`<sup>Required</sup> <a name="not" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.not"></a>

```typescript
public readonly not: boolean | IResolvable;
```

- *Type:* boolean | cdktf.IResolvable

---

##### `operation`<sup>Required</sup> <a name="operation" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.operation"></a>

```typescript
public readonly operation: string;
```

- *Type:* string

---

##### `order`<sup>Required</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.order"></a>

```typescript
public readonly order: number;
```

- *Type:* number

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | TeamRoutingRuleCriteriaConditions;
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions">TeamRoutingRuleCriteriaConditions</a>

---


### TeamRoutingRuleCriteriaList <a name="TeamRoutingRuleCriteriaList" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.Initializer"></a>

```typescript
import { teamRoutingRule } from 'rhizo-co-terraform-provider-opsgenie'

new teamRoutingRule.TeamRoutingRuleCriteriaList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.get"></a>

```typescript
public get(index: number): TeamRoutingRuleCriteriaOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria">TeamRoutingRuleCriteria</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | TeamRoutingRuleCriteria[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria">TeamRoutingRuleCriteria</a>[]

---


### TeamRoutingRuleCriteriaOutputReference <a name="TeamRoutingRuleCriteriaOutputReference" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer"></a>

```typescript
import { teamRoutingRule } from 'rhizo-co-terraform-provider-opsgenie'

new teamRoutingRule.TeamRoutingRuleCriteriaOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.putConditions">putConditions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.resetConditions">resetConditions</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `putConditions` <a name="putConditions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.putConditions"></a>

```typescript
public putConditions(value: IResolvable | TeamRoutingRuleCriteriaConditions[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.putConditions.parameter.value"></a>

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions">TeamRoutingRuleCriteriaConditions</a>[]

---

##### `resetConditions` <a name="resetConditions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.resetConditions"></a>

```typescript
public resetConditions(): void
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.conditions">conditions</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList">TeamRoutingRuleCriteriaConditionsList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.conditionsInput">conditionsInput</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions">TeamRoutingRuleCriteriaConditions</a>[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.typeInput">typeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.type">type</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria">TeamRoutingRuleCriteria</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `conditions`<sup>Required</sup> <a name="conditions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.conditions"></a>

```typescript
public readonly conditions: TeamRoutingRuleCriteriaConditionsList;
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList">TeamRoutingRuleCriteriaConditionsList</a>

---

##### `conditionsInput`<sup>Optional</sup> <a name="conditionsInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.conditionsInput"></a>

```typescript
public readonly conditionsInput: IResolvable | TeamRoutingRuleCriteriaConditions[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions">TeamRoutingRuleCriteriaConditions</a>[]

---

##### `typeInput`<sup>Optional</sup> <a name="typeInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.typeInput"></a>

```typescript
public readonly typeInput: string;
```

- *Type:* string

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.type"></a>

```typescript
public readonly type: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | TeamRoutingRuleCriteria;
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria">TeamRoutingRuleCriteria</a>

---


### TeamRoutingRuleNotifyList <a name="TeamRoutingRuleNotifyList" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.Initializer"></a>

```typescript
import { teamRoutingRule } from 'rhizo-co-terraform-provider-opsgenie'

new teamRoutingRule.TeamRoutingRuleNotifyList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.get"></a>

```typescript
public get(index: number): TeamRoutingRuleNotifyOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify">TeamRoutingRuleNotify</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | TeamRoutingRuleNotify[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify">TeamRoutingRuleNotify</a>[]

---


### TeamRoutingRuleNotifyOutputReference <a name="TeamRoutingRuleNotifyOutputReference" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer"></a>

```typescript
import { teamRoutingRule } from 'rhizo-co-terraform-provider-opsgenie'

new teamRoutingRule.TeamRoutingRuleNotifyOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.resetId">resetId</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.resetName">resetName</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetId` <a name="resetId" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.resetId"></a>

```typescript
public resetId(): void
```

##### `resetName` <a name="resetName" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.resetName"></a>

```typescript
public resetName(): void
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.idInput">idInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.nameInput">nameInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.typeInput">typeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.id">id</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.name">name</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.type">type</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify">TeamRoutingRuleNotify</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `idInput`<sup>Optional</sup> <a name="idInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.idInput"></a>

```typescript
public readonly idInput: string;
```

- *Type:* string

---

##### `nameInput`<sup>Optional</sup> <a name="nameInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.nameInput"></a>

```typescript
public readonly nameInput: string;
```

- *Type:* string

---

##### `typeInput`<sup>Optional</sup> <a name="typeInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.typeInput"></a>

```typescript
public readonly typeInput: string;
```

- *Type:* string

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* string

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.name"></a>

```typescript
public readonly name: string;
```

- *Type:* string

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.type"></a>

```typescript
public readonly type: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | TeamRoutingRuleNotify;
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify">TeamRoutingRuleNotify</a>

---


### TeamRoutingRuleTimeRestrictionList <a name="TeamRoutingRuleTimeRestrictionList" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.Initializer"></a>

```typescript
import { teamRoutingRule } from 'rhizo-co-terraform-provider-opsgenie'

new teamRoutingRule.TeamRoutingRuleTimeRestrictionList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.get"></a>

```typescript
public get(index: number): TeamRoutingRuleTimeRestrictionOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction">TeamRoutingRuleTimeRestriction</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | TeamRoutingRuleTimeRestriction[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction">TeamRoutingRuleTimeRestriction</a>[]

---


### TeamRoutingRuleTimeRestrictionOutputReference <a name="TeamRoutingRuleTimeRestrictionOutputReference" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer"></a>

```typescript
import { teamRoutingRule } from 'rhizo-co-terraform-provider-opsgenie'

new teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.putRestriction">putRestriction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.putRestrictions">putRestrictions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.resetRestriction">resetRestriction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.resetRestrictions">resetRestrictions</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `putRestriction` <a name="putRestriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.putRestriction"></a>

```typescript
public putRestriction(value: IResolvable | TeamRoutingRuleTimeRestrictionRestriction[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.putRestriction.parameter.value"></a>

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction">TeamRoutingRuleTimeRestrictionRestriction</a>[]

---

##### `putRestrictions` <a name="putRestrictions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.putRestrictions"></a>

```typescript
public putRestrictions(value: IResolvable | TeamRoutingRuleTimeRestrictionRestrictions[]): void
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.putRestrictions.parameter.value"></a>

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions">TeamRoutingRuleTimeRestrictionRestrictions</a>[]

---

##### `resetRestriction` <a name="resetRestriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.resetRestriction"></a>

```typescript
public resetRestriction(): void
```

##### `resetRestrictions` <a name="resetRestrictions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.resetRestrictions"></a>

```typescript
public resetRestrictions(): void
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restriction">restriction</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList">TeamRoutingRuleTimeRestrictionRestrictionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restrictions">restrictions</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList">TeamRoutingRuleTimeRestrictionRestrictionsList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restrictionInput">restrictionInput</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction">TeamRoutingRuleTimeRestrictionRestriction</a>[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restrictionsInput">restrictionsInput</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions">TeamRoutingRuleTimeRestrictionRestrictions</a>[]</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.typeInput">typeInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.type">type</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction">TeamRoutingRuleTimeRestriction</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `restriction`<sup>Required</sup> <a name="restriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restriction"></a>

```typescript
public readonly restriction: TeamRoutingRuleTimeRestrictionRestrictionList;
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList">TeamRoutingRuleTimeRestrictionRestrictionList</a>

---

##### `restrictions`<sup>Required</sup> <a name="restrictions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restrictions"></a>

```typescript
public readonly restrictions: TeamRoutingRuleTimeRestrictionRestrictionsList;
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList">TeamRoutingRuleTimeRestrictionRestrictionsList</a>

---

##### `restrictionInput`<sup>Optional</sup> <a name="restrictionInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restrictionInput"></a>

```typescript
public readonly restrictionInput: IResolvable | TeamRoutingRuleTimeRestrictionRestriction[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction">TeamRoutingRuleTimeRestrictionRestriction</a>[]

---

##### `restrictionsInput`<sup>Optional</sup> <a name="restrictionsInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restrictionsInput"></a>

```typescript
public readonly restrictionsInput: IResolvable | TeamRoutingRuleTimeRestrictionRestrictions[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions">TeamRoutingRuleTimeRestrictionRestrictions</a>[]

---

##### `typeInput`<sup>Optional</sup> <a name="typeInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.typeInput"></a>

```typescript
public readonly typeInput: string;
```

- *Type:* string

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.type"></a>

```typescript
public readonly type: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | TeamRoutingRuleTimeRestriction;
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction">TeamRoutingRuleTimeRestriction</a>

---


### TeamRoutingRuleTimeRestrictionRestrictionList <a name="TeamRoutingRuleTimeRestrictionRestrictionList" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.Initializer"></a>

```typescript
import { teamRoutingRule } from 'rhizo-co-terraform-provider-opsgenie'

new teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.get"></a>

```typescript
public get(index: number): TeamRoutingRuleTimeRestrictionRestrictionOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction">TeamRoutingRuleTimeRestrictionRestriction</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | TeamRoutingRuleTimeRestrictionRestriction[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction">TeamRoutingRuleTimeRestrictionRestriction</a>[]

---


### TeamRoutingRuleTimeRestrictionRestrictionOutputReference <a name="TeamRoutingRuleTimeRestrictionRestrictionOutputReference" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer"></a>

```typescript
import { teamRoutingRule } from 'rhizo-co-terraform-provider-opsgenie'

new teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endHourInput">endHourInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endMinInput">endMinInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startHourInput">startHourInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startMinInput">startMinInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endHour">endHour</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endMin">endMin</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startHour">startHour</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startMin">startMin</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction">TeamRoutingRuleTimeRestrictionRestriction</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `endHourInput`<sup>Optional</sup> <a name="endHourInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endHourInput"></a>

```typescript
public readonly endHourInput: number;
```

- *Type:* number

---

##### `endMinInput`<sup>Optional</sup> <a name="endMinInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endMinInput"></a>

```typescript
public readonly endMinInput: number;
```

- *Type:* number

---

##### `startHourInput`<sup>Optional</sup> <a name="startHourInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startHourInput"></a>

```typescript
public readonly startHourInput: number;
```

- *Type:* number

---

##### `startMinInput`<sup>Optional</sup> <a name="startMinInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startMinInput"></a>

```typescript
public readonly startMinInput: number;
```

- *Type:* number

---

##### `endHour`<sup>Required</sup> <a name="endHour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endHour"></a>

```typescript
public readonly endHour: number;
```

- *Type:* number

---

##### `endMin`<sup>Required</sup> <a name="endMin" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endMin"></a>

```typescript
public readonly endMin: number;
```

- *Type:* number

---

##### `startHour`<sup>Required</sup> <a name="startHour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startHour"></a>

```typescript
public readonly startHour: number;
```

- *Type:* number

---

##### `startMin`<sup>Required</sup> <a name="startMin" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startMin"></a>

```typescript
public readonly startMin: number;
```

- *Type:* number

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | TeamRoutingRuleTimeRestrictionRestriction;
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction">TeamRoutingRuleTimeRestrictionRestriction</a>

---


### TeamRoutingRuleTimeRestrictionRestrictionsList <a name="TeamRoutingRuleTimeRestrictionRestrictionsList" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.Initializer"></a>

```typescript
import { teamRoutingRule } from 'rhizo-co-terraform-provider-opsgenie'

new teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList(terraformResource: IInterpolatingParent, terraformAttribute: string, wrapsSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.Initializer.parameter.wrapsSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.get"></a>

```typescript
public get(index: number): TeamRoutingRuleTimeRestrictionRestrictionsOutputReference
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.get.parameter.index"></a>

- *Type:* number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions">TeamRoutingRuleTimeRestrictionRestrictions</a>[]</code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | TeamRoutingRuleTimeRestrictionRestrictions[];
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions">TeamRoutingRuleTimeRestrictionRestrictions</a>[]

---


### TeamRoutingRuleTimeRestrictionRestrictionsOutputReference <a name="TeamRoutingRuleTimeRestrictionRestrictionsOutputReference" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer"></a>

```typescript
import { teamRoutingRule } from 'rhizo-co-terraform-provider-opsgenie'

new teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference(terraformResource: IInterpolatingParent, terraformAttribute: string, complexObjectIndex: number, complexObjectIsFromSet: boolean)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>string</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* string

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.computeFqn"></a>

```typescript
public computeFqn(): string
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute"></a>

```typescript
public getAnyMapAttribute(terraformAttribute: string): {[ key: string ]: any}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getBooleanAttribute"></a>

```typescript
public getBooleanAttribute(terraformAttribute: string): IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute"></a>

```typescript
public getBooleanMapAttribute(terraformAttribute: string): {[ key: string ]: boolean}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getListAttribute"></a>

```typescript
public getListAttribute(terraformAttribute: string): string[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberAttribute"></a>

```typescript
public getNumberAttribute(terraformAttribute: string): number
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberListAttribute"></a>

```typescript
public getNumberListAttribute(terraformAttribute: string): number[]
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute"></a>

```typescript
public getNumberMapAttribute(terraformAttribute: string): {[ key: string ]: number}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getStringAttribute"></a>

```typescript
public getStringAttribute(terraformAttribute: string): string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getStringMapAttribute"></a>

```typescript
public getStringMapAttribute(terraformAttribute: string): {[ key: string ]: string}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* string

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.interpolationForAttribute"></a>

```typescript
public interpolationForAttribute(property: string): IResolvable
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* string

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.resolve"></a>

```typescript
public resolve(_context: IResolveContext): any
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.resolve.parameter._context"></a>

- *Type:* cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.toString"></a>

```typescript
public toString(): string
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.creationStack">creationStack</a></code> | <code>string[]</code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.fqn">fqn</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endDayInput">endDayInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endHourInput">endHourInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endMinInput">endMinInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startDayInput">startDayInput</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startHourInput">startHourInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startMinInput">startMinInput</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endDay">endDay</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endHour">endHour</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endMin">endMin</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startDay">startDay</a></code> | <code>string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startHour">startHour</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startMin">startMin</a></code> | <code>number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.internalValue">internalValue</a></code> | <code>cdktf.IResolvable \| <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions">TeamRoutingRuleTimeRestrictionRestrictions</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.creationStack"></a>

```typescript
public readonly creationStack: string[];
```

- *Type:* string[]

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.fqn"></a>

```typescript
public readonly fqn: string;
```

- *Type:* string

---

##### `endDayInput`<sup>Optional</sup> <a name="endDayInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endDayInput"></a>

```typescript
public readonly endDayInput: string;
```

- *Type:* string

---

##### `endHourInput`<sup>Optional</sup> <a name="endHourInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endHourInput"></a>

```typescript
public readonly endHourInput: number;
```

- *Type:* number

---

##### `endMinInput`<sup>Optional</sup> <a name="endMinInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endMinInput"></a>

```typescript
public readonly endMinInput: number;
```

- *Type:* number

---

##### `startDayInput`<sup>Optional</sup> <a name="startDayInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startDayInput"></a>

```typescript
public readonly startDayInput: string;
```

- *Type:* string

---

##### `startHourInput`<sup>Optional</sup> <a name="startHourInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startHourInput"></a>

```typescript
public readonly startHourInput: number;
```

- *Type:* number

---

##### `startMinInput`<sup>Optional</sup> <a name="startMinInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startMinInput"></a>

```typescript
public readonly startMinInput: number;
```

- *Type:* number

---

##### `endDay`<sup>Required</sup> <a name="endDay" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endDay"></a>

```typescript
public readonly endDay: string;
```

- *Type:* string

---

##### `endHour`<sup>Required</sup> <a name="endHour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endHour"></a>

```typescript
public readonly endHour: number;
```

- *Type:* number

---

##### `endMin`<sup>Required</sup> <a name="endMin" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endMin"></a>

```typescript
public readonly endMin: number;
```

- *Type:* number

---

##### `startDay`<sup>Required</sup> <a name="startDay" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startDay"></a>

```typescript
public readonly startDay: string;
```

- *Type:* string

---

##### `startHour`<sup>Required</sup> <a name="startHour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startHour"></a>

```typescript
public readonly startHour: number;
```

- *Type:* number

---

##### `startMin`<sup>Required</sup> <a name="startMin" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startMin"></a>

```typescript
public readonly startMin: number;
```

- *Type:* number

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.internalValue"></a>

```typescript
public readonly internalValue: IResolvable | TeamRoutingRuleTimeRestrictionRestrictions;
```

- *Type:* cdktf.IResolvable | <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions">TeamRoutingRuleTimeRestrictionRestrictions</a>

---



