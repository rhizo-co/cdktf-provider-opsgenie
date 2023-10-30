# `opsgenie_team_routing_rule`

Refer to the Terraform Registory for docs: [`opsgenie_team_routing_rule`](https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule).

# `teamRoutingRule` Submodule <a name="`teamRoutingRule` Submodule" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### TeamRoutingRule <a name="TeamRoutingRule" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule"></a>

Represents a {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule opsgenie_team_routing_rule}.

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.team_routing_rule.TeamRoutingRule;

TeamRoutingRule.Builder.create(Construct scope, java.lang.String id)
//  .connection(SSHProvisionerConnection)
//  .connection(WinrmProvisionerConnection)
//  .count(java.lang.Number)
//  .count(TerraformCount)
//  .dependsOn(java.util.List<ITerraformDependable>)
//  .forEach(ITerraformIterator)
//  .lifecycle(TerraformResourceLifecycle)
//  .provider(TerraformProvider)
//  .provisioners(java.util.List<FileProvisioner)
//  .provisioners(LocalExecProvisioner)
//  .provisioners(RemoteExecProvisioner>)
    .notify(IResolvable)
    .notify(java.util.List<TeamRoutingRuleNotify>)
    .teamId(java.lang.String)
//  .criteria(IResolvable)
//  .criteria(java.util.List<TeamRoutingRuleCriteria>)
//  .id(java.lang.String)
//  .isDefault(java.lang.Boolean)
//  .isDefault(IResolvable)
//  .name(java.lang.String)
//  .order(java.lang.Number)
//  .timeRestriction(IResolvable)
//  .timeRestriction(java.util.List<TeamRoutingRuleTimeRestriction>)
//  .timezone(java.lang.String)
    .build();
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.scope">scope</a></code> | <code>software.constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.id">id</a></code> | <code>java.lang.String</code> | The scoped construct ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.connection">connection</a></code> | <code>com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.count">count</a></code> | <code>java.lang.Number OR com.hashicorp.cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.dependsOn">dependsOn</a></code> | <code>java.util.List<com.hashicorp.cdktf.ITerraformDependable></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.forEach">forEach</a></code> | <code>com.hashicorp.cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.lifecycle">lifecycle</a></code> | <code>com.hashicorp.cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.provider">provider</a></code> | <code>com.hashicorp.cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.provisioners">provisioners</a></code> | <code>java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.notify">notify</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify">TeamRoutingRuleNotify</a>></code> | notify block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.teamId">teamId</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#team_id TeamRoutingRule#team_id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.criteria">criteria</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria">TeamRoutingRuleCriteria</a>></code> | criteria block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.id">id</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#id TeamRoutingRule#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.isDefault">isDefault</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#is_default TeamRoutingRule#is_default}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.name">name</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#name TeamRoutingRule#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.order">order</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#order TeamRoutingRule#order}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.timeRestriction">timeRestriction</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction">TeamRoutingRuleTimeRestriction</a>></code> | time_restriction block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.timezone">timezone</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#timezone TeamRoutingRule#timezone}. |

---

##### `scope`<sup>Required</sup> <a name="scope" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.scope"></a>

- *Type:* software.constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.id"></a>

- *Type:* java.lang.String

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.connection"></a>

- *Type:* com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.count"></a>

- *Type:* java.lang.Number OR com.hashicorp.cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.dependsOn"></a>

- *Type:* java.util.List<com.hashicorp.cdktf.ITerraformDependable>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.forEach"></a>

- *Type:* com.hashicorp.cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.lifecycle"></a>

- *Type:* com.hashicorp.cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.provider"></a>

- *Type:* com.hashicorp.cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.provisioners"></a>

- *Type:* java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner>

---

##### `notify`<sup>Required</sup> <a name="notify" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.notify"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify">TeamRoutingRuleNotify</a>>

notify block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#notify TeamRoutingRule#notify}

---

##### `teamId`<sup>Required</sup> <a name="teamId" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.teamId"></a>

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#team_id TeamRoutingRule#team_id}.

---

##### `criteria`<sup>Optional</sup> <a name="criteria" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.criteria"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria">TeamRoutingRuleCriteria</a>>

criteria block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#criteria TeamRoutingRule#criteria}

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.id"></a>

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#id TeamRoutingRule#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `isDefault`<sup>Optional</sup> <a name="isDefault" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.isDefault"></a>

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#is_default TeamRoutingRule#is_default}.

---

##### `name`<sup>Optional</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.name"></a>

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#name TeamRoutingRule#name}.

---

##### `order`<sup>Optional</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.order"></a>

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#order TeamRoutingRule#order}.

---

##### `timeRestriction`<sup>Optional</sup> <a name="timeRestriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.timeRestriction"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction">TeamRoutingRuleTimeRestriction</a>>

time_restriction block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#time_restriction TeamRoutingRule#time_restriction}

---

##### `timezone`<sup>Optional</sup> <a name="timezone" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.Initializer.parameter.timezone"></a>

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#timezone TeamRoutingRule#timezone}.

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

```java
public java.lang.String toString()
```

Returns a string representation of this construct.

##### `addOverride` <a name="addOverride" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.addOverride"></a>

```java
public void addOverride(java.lang.String path, java.lang.Object value)
```

###### `path`<sup>Required</sup> <a name="path" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.addOverride.parameter.path"></a>

- *Type:* java.lang.String

---

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.addOverride.parameter.value"></a>

- *Type:* java.lang.Object

---

##### `overrideLogicalId` <a name="overrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.overrideLogicalId"></a>

```java
public void overrideLogicalId(java.lang.String newLogicalId)
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* java.lang.String

The new logical ID to use for this stack element.

---

##### `resetOverrideLogicalId` <a name="resetOverrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetOverrideLogicalId"></a>

```java
public void resetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `toMetadata` <a name="toMetadata" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.toMetadata"></a>

```java
public java.lang.Object toMetadata()
```

##### `toTerraform` <a name="toTerraform" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.toTerraform"></a>

```java
public java.lang.Object toTerraform()
```

Adds this resource to the terraform JSON output.

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `putCriteria` <a name="putCriteria" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putCriteria"></a>

```java
public void putCriteria(IResolvable OR java.util.List<TeamRoutingRuleCriteria> value)
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putCriteria.parameter.value"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria">TeamRoutingRuleCriteria</a>>

---

##### `putNotify` <a name="putNotify" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putNotify"></a>

```java
public void putNotify(IResolvable OR java.util.List<TeamRoutingRuleNotify> value)
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putNotify.parameter.value"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify">TeamRoutingRuleNotify</a>>

---

##### `putTimeRestriction` <a name="putTimeRestriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putTimeRestriction"></a>

```java
public void putTimeRestriction(IResolvable OR java.util.List<TeamRoutingRuleTimeRestriction> value)
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.putTimeRestriction.parameter.value"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction">TeamRoutingRuleTimeRestriction</a>>

---

##### `resetCriteria` <a name="resetCriteria" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetCriteria"></a>

```java
public void resetCriteria()
```

##### `resetId` <a name="resetId" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetId"></a>

```java
public void resetId()
```

##### `resetIsDefault` <a name="resetIsDefault" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetIsDefault"></a>

```java
public void resetIsDefault()
```

##### `resetName` <a name="resetName" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetName"></a>

```java
public void resetName()
```

##### `resetOrder` <a name="resetOrder" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetOrder"></a>

```java
public void resetOrder()
```

##### `resetTimeRestriction` <a name="resetTimeRestriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetTimeRestriction"></a>

```java
public void resetTimeRestriction()
```

##### `resetTimezone` <a name="resetTimezone" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.resetTimezone"></a>

```java
public void resetTimezone()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isConstruct">isConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isTerraformElement">isTerraformElement</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isTerraformResource">isTerraformResource</a></code> | *No description.* |

---

##### `isConstruct` <a name="isConstruct" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isConstruct"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.team_routing_rule.TeamRoutingRule;

TeamRoutingRule.isConstruct(java.lang.Object x)
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

- *Type:* java.lang.Object

Any object.

---

##### `isTerraformElement` <a name="isTerraformElement" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isTerraformElement"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.team_routing_rule.TeamRoutingRule;

TeamRoutingRule.isTerraformElement(java.lang.Object x)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isTerraformElement.parameter.x"></a>

- *Type:* java.lang.Object

---

##### `isTerraformResource` <a name="isTerraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isTerraformResource"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.team_routing_rule.TeamRoutingRule;

TeamRoutingRule.isTerraformResource(java.lang.Object x)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.isTerraformResource.parameter.x"></a>

- *Type:* java.lang.Object

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.node">node</a></code> | <code>software.constructs.Node</code> | The tree node. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.cdktfStack">cdktfStack</a></code> | <code>com.hashicorp.cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.friendlyUniqueId">friendlyUniqueId</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.terraformMetaArguments">terraformMetaArguments</a></code> | <code>java.util.Map<java.lang.String, java.lang.Object></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.terraformResourceType">terraformResourceType</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.terraformGeneratorMetadata">terraformGeneratorMetadata</a></code> | <code>com.hashicorp.cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.connection">connection</a></code> | <code>com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.count">count</a></code> | <code>java.lang.Number OR com.hashicorp.cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.dependsOn">dependsOn</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.forEach">forEach</a></code> | <code>com.hashicorp.cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.lifecycle">lifecycle</a></code> | <code>com.hashicorp.cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.provider">provider</a></code> | <code>com.hashicorp.cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.provisioners">provisioners</a></code> | <code>java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.criteria">criteria</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList">TeamRoutingRuleCriteriaList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.notify">notify</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList">TeamRoutingRuleNotifyList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timeRestriction">timeRestriction</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList">TeamRoutingRuleTimeRestrictionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.criteriaInput">criteriaInput</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria">TeamRoutingRuleCriteria</a>></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.idInput">idInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.isDefaultInput">isDefaultInput</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.nameInput">nameInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.notifyInput">notifyInput</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify">TeamRoutingRuleNotify</a>></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.orderInput">orderInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.teamIdInput">teamIdInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timeRestrictionInput">timeRestrictionInput</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction">TeamRoutingRuleTimeRestriction</a>></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timezoneInput">timezoneInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.id">id</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.isDefault">isDefault</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.name">name</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.order">order</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.teamId">teamId</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timezone">timezone</a></code> | <code>java.lang.String</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.node"></a>

```java
public Node getNode();
```

- *Type:* software.constructs.Node

The tree node.

---

##### `cdktfStack`<sup>Required</sup> <a name="cdktfStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.cdktfStack"></a>

```java
public TerraformStack getCdktfStack();
```

- *Type:* com.hashicorp.cdktf.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `friendlyUniqueId`<sup>Required</sup> <a name="friendlyUniqueId" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.friendlyUniqueId"></a>

```java
public java.lang.String getFriendlyUniqueId();
```

- *Type:* java.lang.String

---

##### `terraformMetaArguments`<sup>Required</sup> <a name="terraformMetaArguments" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.terraformMetaArguments"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getTerraformMetaArguments();
```

- *Type:* java.util.Map<java.lang.String, java.lang.Object>

---

##### `terraformResourceType`<sup>Required</sup> <a name="terraformResourceType" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.terraformResourceType"></a>

```java
public java.lang.String getTerraformResourceType();
```

- *Type:* java.lang.String

---

##### `terraformGeneratorMetadata`<sup>Optional</sup> <a name="terraformGeneratorMetadata" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.terraformGeneratorMetadata"></a>

```java
public TerraformProviderGeneratorMetadata getTerraformGeneratorMetadata();
```

- *Type:* com.hashicorp.cdktf.TerraformProviderGeneratorMetadata

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.connection"></a>

```java
public java.lang.Object getConnection();
```

- *Type:* com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.count"></a>

```java
public java.lang.Object getCount();
```

- *Type:* java.lang.Number OR com.hashicorp.cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.dependsOn"></a>

```java
public java.util.List<java.lang.String> getDependsOn();
```

- *Type:* java.util.List<java.lang.String>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.forEach"></a>

```java
public ITerraformIterator getForEach();
```

- *Type:* com.hashicorp.cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.lifecycle"></a>

```java
public TerraformResourceLifecycle getLifecycle();
```

- *Type:* com.hashicorp.cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.provider"></a>

```java
public TerraformProvider getProvider();
```

- *Type:* com.hashicorp.cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.provisioners"></a>

```java
public java.lang.Object getProvisioners();
```

- *Type:* java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner>

---

##### `criteria`<sup>Required</sup> <a name="criteria" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.criteria"></a>

```java
public TeamRoutingRuleCriteriaList getCriteria();
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList">TeamRoutingRuleCriteriaList</a>

---

##### `notify`<sup>Required</sup> <a name="notify" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.notify"></a>

```java
public TeamRoutingRuleNotifyList getNotify();
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList">TeamRoutingRuleNotifyList</a>

---

##### `timeRestriction`<sup>Required</sup> <a name="timeRestriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timeRestriction"></a>

```java
public TeamRoutingRuleTimeRestrictionList getTimeRestriction();
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList">TeamRoutingRuleTimeRestrictionList</a>

---

##### `criteriaInput`<sup>Optional</sup> <a name="criteriaInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.criteriaInput"></a>

```java
public java.lang.Object getCriteriaInput();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria">TeamRoutingRuleCriteria</a>>

---

##### `idInput`<sup>Optional</sup> <a name="idInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.idInput"></a>

```java
public java.lang.String getIdInput();
```

- *Type:* java.lang.String

---

##### `isDefaultInput`<sup>Optional</sup> <a name="isDefaultInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.isDefaultInput"></a>

```java
public java.lang.Object getIsDefaultInput();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

---

##### `nameInput`<sup>Optional</sup> <a name="nameInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.nameInput"></a>

```java
public java.lang.String getNameInput();
```

- *Type:* java.lang.String

---

##### `notifyInput`<sup>Optional</sup> <a name="notifyInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.notifyInput"></a>

```java
public java.lang.Object getNotifyInput();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify">TeamRoutingRuleNotify</a>>

---

##### `orderInput`<sup>Optional</sup> <a name="orderInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.orderInput"></a>

```java
public java.lang.Number getOrderInput();
```

- *Type:* java.lang.Number

---

##### `teamIdInput`<sup>Optional</sup> <a name="teamIdInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.teamIdInput"></a>

```java
public java.lang.String getTeamIdInput();
```

- *Type:* java.lang.String

---

##### `timeRestrictionInput`<sup>Optional</sup> <a name="timeRestrictionInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timeRestrictionInput"></a>

```java
public java.lang.Object getTimeRestrictionInput();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction">TeamRoutingRuleTimeRestriction</a>>

---

##### `timezoneInput`<sup>Optional</sup> <a name="timezoneInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timezoneInput"></a>

```java
public java.lang.String getTimezoneInput();
```

- *Type:* java.lang.String

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.id"></a>

```java
public java.lang.String getId();
```

- *Type:* java.lang.String

---

##### `isDefault`<sup>Required</sup> <a name="isDefault" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.isDefault"></a>

```java
public java.lang.Object getIsDefault();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.name"></a>

```java
public java.lang.String getName();
```

- *Type:* java.lang.String

---

##### `order`<sup>Required</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.order"></a>

```java
public java.lang.Number getOrder();
```

- *Type:* java.lang.Number

---

##### `teamId`<sup>Required</sup> <a name="teamId" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.teamId"></a>

```java
public java.lang.String getTeamId();
```

- *Type:* java.lang.String

---

##### `timezone`<sup>Required</sup> <a name="timezone" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.timezone"></a>

```java
public java.lang.String getTimezone();
```

- *Type:* java.lang.String

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.tfResourceType">tfResourceType</a></code> | <code>java.lang.String</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRule.property.tfResourceType"></a>

```java
public java.lang.String getTfResourceType();
```

- *Type:* java.lang.String

---

## Structs <a name="Structs" id="Structs"></a>

### TeamRoutingRuleConfig <a name="TeamRoutingRuleConfig" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.team_routing_rule.TeamRoutingRuleConfig;

TeamRoutingRuleConfig.builder()
//  .connection(SSHProvisionerConnection)
//  .connection(WinrmProvisionerConnection)
//  .count(java.lang.Number)
//  .count(TerraformCount)
//  .dependsOn(java.util.List<ITerraformDependable>)
//  .forEach(ITerraformIterator)
//  .lifecycle(TerraformResourceLifecycle)
//  .provider(TerraformProvider)
//  .provisioners(java.util.List<FileProvisioner)
//  .provisioners(LocalExecProvisioner)
//  .provisioners(RemoteExecProvisioner>)
    .notify(IResolvable)
    .notify(java.util.List<TeamRoutingRuleNotify>)
    .teamId(java.lang.String)
//  .criteria(IResolvable)
//  .criteria(java.util.List<TeamRoutingRuleCriteria>)
//  .id(java.lang.String)
//  .isDefault(java.lang.Boolean)
//  .isDefault(IResolvable)
//  .name(java.lang.String)
//  .order(java.lang.Number)
//  .timeRestriction(IResolvable)
//  .timeRestriction(java.util.List<TeamRoutingRuleTimeRestriction>)
//  .timezone(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.connection">connection</a></code> | <code>com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.count">count</a></code> | <code>java.lang.Number OR com.hashicorp.cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.dependsOn">dependsOn</a></code> | <code>java.util.List<com.hashicorp.cdktf.ITerraformDependable></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.forEach">forEach</a></code> | <code>com.hashicorp.cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.lifecycle">lifecycle</a></code> | <code>com.hashicorp.cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.provider">provider</a></code> | <code>com.hashicorp.cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.provisioners">provisioners</a></code> | <code>java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.notify">notify</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify">TeamRoutingRuleNotify</a>></code> | notify block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.teamId">teamId</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#team_id TeamRoutingRule#team_id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.criteria">criteria</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria">TeamRoutingRuleCriteria</a>></code> | criteria block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.id">id</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#id TeamRoutingRule#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.isDefault">isDefault</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#is_default TeamRoutingRule#is_default}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.name">name</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#name TeamRoutingRule#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.order">order</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#order TeamRoutingRule#order}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.timeRestriction">timeRestriction</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction">TeamRoutingRuleTimeRestriction</a>></code> | time_restriction block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.timezone">timezone</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#timezone TeamRoutingRule#timezone}. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.connection"></a>

```java
public java.lang.Object getConnection();
```

- *Type:* com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.count"></a>

```java
public java.lang.Object getCount();
```

- *Type:* java.lang.Number OR com.hashicorp.cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.dependsOn"></a>

```java
public java.util.List<ITerraformDependable> getDependsOn();
```

- *Type:* java.util.List<com.hashicorp.cdktf.ITerraformDependable>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.forEach"></a>

```java
public ITerraformIterator getForEach();
```

- *Type:* com.hashicorp.cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.lifecycle"></a>

```java
public TerraformResourceLifecycle getLifecycle();
```

- *Type:* com.hashicorp.cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.provider"></a>

```java
public TerraformProvider getProvider();
```

- *Type:* com.hashicorp.cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.provisioners"></a>

```java
public java.lang.Object getProvisioners();
```

- *Type:* java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner>

---

##### `notify`<sup>Required</sup> <a name="notify" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.notify"></a>

```java
public java.lang.Object getNotify();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify">TeamRoutingRuleNotify</a>>

notify block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#notify TeamRoutingRule#notify}

---

##### `teamId`<sup>Required</sup> <a name="teamId" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.teamId"></a>

```java
public java.lang.String getTeamId();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#team_id TeamRoutingRule#team_id}.

---

##### `criteria`<sup>Optional</sup> <a name="criteria" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.criteria"></a>

```java
public java.lang.Object getCriteria();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria">TeamRoutingRuleCriteria</a>>

criteria block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#criteria TeamRoutingRule#criteria}

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.id"></a>

```java
public java.lang.String getId();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#id TeamRoutingRule#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `isDefault`<sup>Optional</sup> <a name="isDefault" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.isDefault"></a>

```java
public java.lang.Object getIsDefault();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#is_default TeamRoutingRule#is_default}.

---

##### `name`<sup>Optional</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.name"></a>

```java
public java.lang.String getName();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#name TeamRoutingRule#name}.

---

##### `order`<sup>Optional</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.order"></a>

```java
public java.lang.Number getOrder();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#order TeamRoutingRule#order}.

---

##### `timeRestriction`<sup>Optional</sup> <a name="timeRestriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.timeRestriction"></a>

```java
public java.lang.Object getTimeRestriction();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction">TeamRoutingRuleTimeRestriction</a>>

time_restriction block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#time_restriction TeamRoutingRule#time_restriction}

---

##### `timezone`<sup>Optional</sup> <a name="timezone" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleConfig.property.timezone"></a>

```java
public java.lang.String getTimezone();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#timezone TeamRoutingRule#timezone}.

---

### TeamRoutingRuleCriteria <a name="TeamRoutingRuleCriteria" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.team_routing_rule.TeamRoutingRuleCriteria;

TeamRoutingRuleCriteria.builder()
    .type(java.lang.String)
//  .conditions(IResolvable)
//  .conditions(java.util.List<TeamRoutingRuleCriteriaConditions>)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria.property.type">type</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#type TeamRoutingRule#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria.property.conditions">conditions</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions">TeamRoutingRuleCriteriaConditions</a>></code> | conditions block. |

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria.property.type"></a>

```java
public java.lang.String getType();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#type TeamRoutingRule#type}.

---

##### `conditions`<sup>Optional</sup> <a name="conditions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria.property.conditions"></a>

```java
public java.lang.Object getConditions();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions">TeamRoutingRuleCriteriaConditions</a>>

conditions block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#conditions TeamRoutingRule#conditions}

---

### TeamRoutingRuleCriteriaConditions <a name="TeamRoutingRuleCriteriaConditions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.team_routing_rule.TeamRoutingRuleCriteriaConditions;

TeamRoutingRuleCriteriaConditions.builder()
    .field(java.lang.String)
    .operation(java.lang.String)
//  .expectedValue(java.lang.String)
//  .key(java.lang.String)
//  .not(java.lang.Boolean)
//  .not(IResolvable)
//  .order(java.lang.Number)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.field">field</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#field TeamRoutingRule#field}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.operation">operation</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#operation TeamRoutingRule#operation}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.expectedValue">expectedValue</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#expected_value TeamRoutingRule#expected_value}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.key">key</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#key TeamRoutingRule#key}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.not">not</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#not TeamRoutingRule#not}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.order">order</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#order TeamRoutingRule#order}. |

---

##### `field`<sup>Required</sup> <a name="field" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.field"></a>

```java
public java.lang.String getField();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#field TeamRoutingRule#field}.

---

##### `operation`<sup>Required</sup> <a name="operation" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.operation"></a>

```java
public java.lang.String getOperation();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#operation TeamRoutingRule#operation}.

---

##### `expectedValue`<sup>Optional</sup> <a name="expectedValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.expectedValue"></a>

```java
public java.lang.String getExpectedValue();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#expected_value TeamRoutingRule#expected_value}.

---

##### `key`<sup>Optional</sup> <a name="key" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.key"></a>

```java
public java.lang.String getKey();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#key TeamRoutingRule#key}.

---

##### `not`<sup>Optional</sup> <a name="not" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.not"></a>

```java
public java.lang.Object getNot();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#not TeamRoutingRule#not}.

---

##### `order`<sup>Optional</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions.property.order"></a>

```java
public java.lang.Number getOrder();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#order TeamRoutingRule#order}.

---

### TeamRoutingRuleNotify <a name="TeamRoutingRuleNotify" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.team_routing_rule.TeamRoutingRuleNotify;

TeamRoutingRuleNotify.builder()
    .type(java.lang.String)
//  .id(java.lang.String)
//  .name(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify.property.type">type</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#type TeamRoutingRule#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify.property.id">id</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#id TeamRoutingRule#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify.property.name">name</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#name TeamRoutingRule#name}. |

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify.property.type"></a>

```java
public java.lang.String getType();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#type TeamRoutingRule#type}.

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify.property.id"></a>

```java
public java.lang.String getId();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#id TeamRoutingRule#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `name`<sup>Optional</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify.property.name"></a>

```java
public java.lang.String getName();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#name TeamRoutingRule#name}.

---

### TeamRoutingRuleTimeRestriction <a name="TeamRoutingRuleTimeRestriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.team_routing_rule.TeamRoutingRuleTimeRestriction;

TeamRoutingRuleTimeRestriction.builder()
    .type(java.lang.String)
//  .restriction(IResolvable)
//  .restriction(java.util.List<TeamRoutingRuleTimeRestrictionRestriction>)
//  .restrictions(IResolvable)
//  .restrictions(java.util.List<TeamRoutingRuleTimeRestrictionRestrictions>)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction.property.type">type</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#type TeamRoutingRule#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction.property.restriction">restriction</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction">TeamRoutingRuleTimeRestrictionRestriction</a>></code> | restriction block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction.property.restrictions">restrictions</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions">TeamRoutingRuleTimeRestrictionRestrictions</a>></code> | restrictions block. |

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction.property.type"></a>

```java
public java.lang.String getType();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#type TeamRoutingRule#type}.

---

##### `restriction`<sup>Optional</sup> <a name="restriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction.property.restriction"></a>

```java
public java.lang.Object getRestriction();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction">TeamRoutingRuleTimeRestrictionRestriction</a>>

restriction block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#restriction TeamRoutingRule#restriction}

---

##### `restrictions`<sup>Optional</sup> <a name="restrictions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction.property.restrictions"></a>

```java
public java.lang.Object getRestrictions();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions">TeamRoutingRuleTimeRestrictionRestrictions</a>>

restrictions block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#restrictions TeamRoutingRule#restrictions}

---

### TeamRoutingRuleTimeRestrictionRestriction <a name="TeamRoutingRuleTimeRestrictionRestriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.team_routing_rule.TeamRoutingRuleTimeRestrictionRestriction;

TeamRoutingRuleTimeRestrictionRestriction.builder()
    .endHour(java.lang.Number)
    .endMin(java.lang.Number)
    .startHour(java.lang.Number)
    .startMin(java.lang.Number)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.endHour">endHour</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_hour TeamRoutingRule#end_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.endMin">endMin</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_min TeamRoutingRule#end_min}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.startHour">startHour</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_hour TeamRoutingRule#start_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.startMin">startMin</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_min TeamRoutingRule#start_min}. |

---

##### `endHour`<sup>Required</sup> <a name="endHour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.endHour"></a>

```java
public java.lang.Number getEndHour();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_hour TeamRoutingRule#end_hour}.

---

##### `endMin`<sup>Required</sup> <a name="endMin" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.endMin"></a>

```java
public java.lang.Number getEndMin();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_min TeamRoutingRule#end_min}.

---

##### `startHour`<sup>Required</sup> <a name="startHour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.startHour"></a>

```java
public java.lang.Number getStartHour();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_hour TeamRoutingRule#start_hour}.

---

##### `startMin`<sup>Required</sup> <a name="startMin" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction.property.startMin"></a>

```java
public java.lang.Number getStartMin();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_min TeamRoutingRule#start_min}.

---

### TeamRoutingRuleTimeRestrictionRestrictions <a name="TeamRoutingRuleTimeRestrictionRestrictions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.team_routing_rule.TeamRoutingRuleTimeRestrictionRestrictions;

TeamRoutingRuleTimeRestrictionRestrictions.builder()
    .endDay(java.lang.String)
    .endHour(java.lang.Number)
    .endMin(java.lang.Number)
    .startDay(java.lang.String)
    .startHour(java.lang.Number)
    .startMin(java.lang.Number)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.endDay">endDay</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_day TeamRoutingRule#end_day}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.endHour">endHour</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_hour TeamRoutingRule#end_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.endMin">endMin</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_min TeamRoutingRule#end_min}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.startDay">startDay</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_day TeamRoutingRule#start_day}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.startHour">startHour</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_hour TeamRoutingRule#start_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.startMin">startMin</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_min TeamRoutingRule#start_min}. |

---

##### `endDay`<sup>Required</sup> <a name="endDay" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.endDay"></a>

```java
public java.lang.String getEndDay();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_day TeamRoutingRule#end_day}.

---

##### `endHour`<sup>Required</sup> <a name="endHour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.endHour"></a>

```java
public java.lang.Number getEndHour();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_hour TeamRoutingRule#end_hour}.

---

##### `endMin`<sup>Required</sup> <a name="endMin" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.endMin"></a>

```java
public java.lang.Number getEndMin();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#end_min TeamRoutingRule#end_min}.

---

##### `startDay`<sup>Required</sup> <a name="startDay" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.startDay"></a>

```java
public java.lang.String getStartDay();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_day TeamRoutingRule#start_day}.

---

##### `startHour`<sup>Required</sup> <a name="startHour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.startHour"></a>

```java
public java.lang.Number getStartHour();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_hour TeamRoutingRule#start_hour}.

---

##### `startMin`<sup>Required</sup> <a name="startMin" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions.property.startMin"></a>

```java
public java.lang.Number getStartMin();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/team_routing_rule#start_min TeamRoutingRule#start_min}.

---

## Classes <a name="Classes" id="Classes"></a>

### TeamRoutingRuleCriteriaConditionsList <a name="TeamRoutingRuleCriteriaConditionsList" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.team_routing_rule.TeamRoutingRuleCriteriaConditionsList;

new TeamRoutingRuleCriteriaConditionsList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.get"></a>

```java
public TeamRoutingRuleCriteriaConditionsOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions">TeamRoutingRuleCriteriaConditions</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions">TeamRoutingRuleCriteriaConditions</a>>

---


### TeamRoutingRuleCriteriaConditionsOutputReference <a name="TeamRoutingRuleCriteriaConditionsOutputReference" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.team_routing_rule.TeamRoutingRuleCriteriaConditionsOutputReference;

new TeamRoutingRuleCriteriaConditionsOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetExpectedValue` <a name="resetExpectedValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resetExpectedValue"></a>

```java
public void resetExpectedValue()
```

##### `resetKey` <a name="resetKey" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resetKey"></a>

```java
public void resetKey()
```

##### `resetNot` <a name="resetNot" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resetNot"></a>

```java
public void resetNot()
```

##### `resetOrder` <a name="resetOrder" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.resetOrder"></a>

```java
public void resetOrder()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.expectedValueInput">expectedValueInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.fieldInput">fieldInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.keyInput">keyInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.notInput">notInput</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.operationInput">operationInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.orderInput">orderInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.expectedValue">expectedValue</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.field">field</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.key">key</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.not">not</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.operation">operation</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.order">order</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions">TeamRoutingRuleCriteriaConditions</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `expectedValueInput`<sup>Optional</sup> <a name="expectedValueInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.expectedValueInput"></a>

```java
public java.lang.String getExpectedValueInput();
```

- *Type:* java.lang.String

---

##### `fieldInput`<sup>Optional</sup> <a name="fieldInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.fieldInput"></a>

```java
public java.lang.String getFieldInput();
```

- *Type:* java.lang.String

---

##### `keyInput`<sup>Optional</sup> <a name="keyInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.keyInput"></a>

```java
public java.lang.String getKeyInput();
```

- *Type:* java.lang.String

---

##### `notInput`<sup>Optional</sup> <a name="notInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.notInput"></a>

```java
public java.lang.Object getNotInput();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

---

##### `operationInput`<sup>Optional</sup> <a name="operationInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.operationInput"></a>

```java
public java.lang.String getOperationInput();
```

- *Type:* java.lang.String

---

##### `orderInput`<sup>Optional</sup> <a name="orderInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.orderInput"></a>

```java
public java.lang.Number getOrderInput();
```

- *Type:* java.lang.Number

---

##### `expectedValue`<sup>Required</sup> <a name="expectedValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.expectedValue"></a>

```java
public java.lang.String getExpectedValue();
```

- *Type:* java.lang.String

---

##### `field`<sup>Required</sup> <a name="field" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.field"></a>

```java
public java.lang.String getField();
```

- *Type:* java.lang.String

---

##### `key`<sup>Required</sup> <a name="key" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.key"></a>

```java
public java.lang.String getKey();
```

- *Type:* java.lang.String

---

##### `not`<sup>Required</sup> <a name="not" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.not"></a>

```java
public java.lang.Object getNot();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

---

##### `operation`<sup>Required</sup> <a name="operation" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.operation"></a>

```java
public java.lang.String getOperation();
```

- *Type:* java.lang.String

---

##### `order`<sup>Required</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.order"></a>

```java
public java.lang.Number getOrder();
```

- *Type:* java.lang.Number

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsOutputReference.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions">TeamRoutingRuleCriteriaConditions</a>

---


### TeamRoutingRuleCriteriaList <a name="TeamRoutingRuleCriteriaList" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.team_routing_rule.TeamRoutingRuleCriteriaList;

new TeamRoutingRuleCriteriaList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.get"></a>

```java
public TeamRoutingRuleCriteriaOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria">TeamRoutingRuleCriteria</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaList.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria">TeamRoutingRuleCriteria</a>>

---


### TeamRoutingRuleCriteriaOutputReference <a name="TeamRoutingRuleCriteriaOutputReference" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.team_routing_rule.TeamRoutingRuleCriteriaOutputReference;

new TeamRoutingRuleCriteriaOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `putConditions` <a name="putConditions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.putConditions"></a>

```java
public void putConditions(IResolvable OR java.util.List<TeamRoutingRuleCriteriaConditions> value)
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.putConditions.parameter.value"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions">TeamRoutingRuleCriteriaConditions</a>>

---

##### `resetConditions` <a name="resetConditions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.resetConditions"></a>

```java
public void resetConditions()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.conditions">conditions</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList">TeamRoutingRuleCriteriaConditionsList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.conditionsInput">conditionsInput</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions">TeamRoutingRuleCriteriaConditions</a>></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.typeInput">typeInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.type">type</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria">TeamRoutingRuleCriteria</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `conditions`<sup>Required</sup> <a name="conditions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.conditions"></a>

```java
public TeamRoutingRuleCriteriaConditionsList getConditions();
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditionsList">TeamRoutingRuleCriteriaConditionsList</a>

---

##### `conditionsInput`<sup>Optional</sup> <a name="conditionsInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.conditionsInput"></a>

```java
public java.lang.Object getConditionsInput();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaConditions">TeamRoutingRuleCriteriaConditions</a>>

---

##### `typeInput`<sup>Optional</sup> <a name="typeInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.typeInput"></a>

```java
public java.lang.String getTypeInput();
```

- *Type:* java.lang.String

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.type"></a>

```java
public java.lang.String getType();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteriaOutputReference.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleCriteria">TeamRoutingRuleCriteria</a>

---


### TeamRoutingRuleNotifyList <a name="TeamRoutingRuleNotifyList" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.team_routing_rule.TeamRoutingRuleNotifyList;

new TeamRoutingRuleNotifyList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.get"></a>

```java
public TeamRoutingRuleNotifyOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify">TeamRoutingRuleNotify</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyList.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify">TeamRoutingRuleNotify</a>>

---


### TeamRoutingRuleNotifyOutputReference <a name="TeamRoutingRuleNotifyOutputReference" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.team_routing_rule.TeamRoutingRuleNotifyOutputReference;

new TeamRoutingRuleNotifyOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetId` <a name="resetId" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.resetId"></a>

```java
public void resetId()
```

##### `resetName` <a name="resetName" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.resetName"></a>

```java
public void resetName()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.idInput">idInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.nameInput">nameInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.typeInput">typeInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.id">id</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.name">name</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.type">type</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify">TeamRoutingRuleNotify</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `idInput`<sup>Optional</sup> <a name="idInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.idInput"></a>

```java
public java.lang.String getIdInput();
```

- *Type:* java.lang.String

---

##### `nameInput`<sup>Optional</sup> <a name="nameInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.nameInput"></a>

```java
public java.lang.String getNameInput();
```

- *Type:* java.lang.String

---

##### `typeInput`<sup>Optional</sup> <a name="typeInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.typeInput"></a>

```java
public java.lang.String getTypeInput();
```

- *Type:* java.lang.String

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.id"></a>

```java
public java.lang.String getId();
```

- *Type:* java.lang.String

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.name"></a>

```java
public java.lang.String getName();
```

- *Type:* java.lang.String

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.type"></a>

```java
public java.lang.String getType();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotifyOutputReference.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleNotify">TeamRoutingRuleNotify</a>

---


### TeamRoutingRuleTimeRestrictionList <a name="TeamRoutingRuleTimeRestrictionList" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.team_routing_rule.TeamRoutingRuleTimeRestrictionList;

new TeamRoutingRuleTimeRestrictionList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.get"></a>

```java
public TeamRoutingRuleTimeRestrictionOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction">TeamRoutingRuleTimeRestriction</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionList.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction">TeamRoutingRuleTimeRestriction</a>>

---


### TeamRoutingRuleTimeRestrictionOutputReference <a name="TeamRoutingRuleTimeRestrictionOutputReference" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.team_routing_rule.TeamRoutingRuleTimeRestrictionOutputReference;

new TeamRoutingRuleTimeRestrictionOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `putRestriction` <a name="putRestriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.putRestriction"></a>

```java
public void putRestriction(IResolvable OR java.util.List<TeamRoutingRuleTimeRestrictionRestriction> value)
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.putRestriction.parameter.value"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction">TeamRoutingRuleTimeRestrictionRestriction</a>>

---

##### `putRestrictions` <a name="putRestrictions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.putRestrictions"></a>

```java
public void putRestrictions(IResolvable OR java.util.List<TeamRoutingRuleTimeRestrictionRestrictions> value)
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.putRestrictions.parameter.value"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions">TeamRoutingRuleTimeRestrictionRestrictions</a>>

---

##### `resetRestriction` <a name="resetRestriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.resetRestriction"></a>

```java
public void resetRestriction()
```

##### `resetRestrictions` <a name="resetRestrictions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.resetRestrictions"></a>

```java
public void resetRestrictions()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restriction">restriction</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList">TeamRoutingRuleTimeRestrictionRestrictionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restrictions">restrictions</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList">TeamRoutingRuleTimeRestrictionRestrictionsList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restrictionInput">restrictionInput</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction">TeamRoutingRuleTimeRestrictionRestriction</a>></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restrictionsInput">restrictionsInput</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions">TeamRoutingRuleTimeRestrictionRestrictions</a>></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.typeInput">typeInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.type">type</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction">TeamRoutingRuleTimeRestriction</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `restriction`<sup>Required</sup> <a name="restriction" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restriction"></a>

```java
public TeamRoutingRuleTimeRestrictionRestrictionList getRestriction();
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList">TeamRoutingRuleTimeRestrictionRestrictionList</a>

---

##### `restrictions`<sup>Required</sup> <a name="restrictions" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restrictions"></a>

```java
public TeamRoutingRuleTimeRestrictionRestrictionsList getRestrictions();
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList">TeamRoutingRuleTimeRestrictionRestrictionsList</a>

---

##### `restrictionInput`<sup>Optional</sup> <a name="restrictionInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restrictionInput"></a>

```java
public java.lang.Object getRestrictionInput();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction">TeamRoutingRuleTimeRestrictionRestriction</a>>

---

##### `restrictionsInput`<sup>Optional</sup> <a name="restrictionsInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.restrictionsInput"></a>

```java
public java.lang.Object getRestrictionsInput();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions">TeamRoutingRuleTimeRestrictionRestrictions</a>>

---

##### `typeInput`<sup>Optional</sup> <a name="typeInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.typeInput"></a>

```java
public java.lang.String getTypeInput();
```

- *Type:* java.lang.String

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.type"></a>

```java
public java.lang.String getType();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionOutputReference.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestriction">TeamRoutingRuleTimeRestriction</a>

---


### TeamRoutingRuleTimeRestrictionRestrictionList <a name="TeamRoutingRuleTimeRestrictionRestrictionList" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.team_routing_rule.TeamRoutingRuleTimeRestrictionRestrictionList;

new TeamRoutingRuleTimeRestrictionRestrictionList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.get"></a>

```java
public TeamRoutingRuleTimeRestrictionRestrictionOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction">TeamRoutingRuleTimeRestrictionRestriction</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionList.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction">TeamRoutingRuleTimeRestrictionRestriction</a>>

---


### TeamRoutingRuleTimeRestrictionRestrictionOutputReference <a name="TeamRoutingRuleTimeRestrictionRestrictionOutputReference" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.team_routing_rule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference;

new TeamRoutingRuleTimeRestrictionRestrictionOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endHourInput">endHourInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endMinInput">endMinInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startHourInput">startHourInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startMinInput">startMinInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endHour">endHour</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endMin">endMin</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startHour">startHour</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startMin">startMin</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction">TeamRoutingRuleTimeRestrictionRestriction</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `endHourInput`<sup>Optional</sup> <a name="endHourInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endHourInput"></a>

```java
public java.lang.Number getEndHourInput();
```

- *Type:* java.lang.Number

---

##### `endMinInput`<sup>Optional</sup> <a name="endMinInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endMinInput"></a>

```java
public java.lang.Number getEndMinInput();
```

- *Type:* java.lang.Number

---

##### `startHourInput`<sup>Optional</sup> <a name="startHourInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startHourInput"></a>

```java
public java.lang.Number getStartHourInput();
```

- *Type:* java.lang.Number

---

##### `startMinInput`<sup>Optional</sup> <a name="startMinInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startMinInput"></a>

```java
public java.lang.Number getStartMinInput();
```

- *Type:* java.lang.Number

---

##### `endHour`<sup>Required</sup> <a name="endHour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endHour"></a>

```java
public java.lang.Number getEndHour();
```

- *Type:* java.lang.Number

---

##### `endMin`<sup>Required</sup> <a name="endMin" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.endMin"></a>

```java
public java.lang.Number getEndMin();
```

- *Type:* java.lang.Number

---

##### `startHour`<sup>Required</sup> <a name="startHour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startHour"></a>

```java
public java.lang.Number getStartHour();
```

- *Type:* java.lang.Number

---

##### `startMin`<sup>Required</sup> <a name="startMin" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.startMin"></a>

```java
public java.lang.Number getStartMin();
```

- *Type:* java.lang.Number

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionOutputReference.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestriction">TeamRoutingRuleTimeRestrictionRestriction</a>

---


### TeamRoutingRuleTimeRestrictionRestrictionsList <a name="TeamRoutingRuleTimeRestrictionRestrictionsList" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.team_routing_rule.TeamRoutingRuleTimeRestrictionRestrictionsList;

new TeamRoutingRuleTimeRestrictionRestrictionsList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.get"></a>

```java
public TeamRoutingRuleTimeRestrictionRestrictionsOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions">TeamRoutingRuleTimeRestrictionRestrictions</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsList.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions">TeamRoutingRuleTimeRestrictionRestrictions</a>>

---


### TeamRoutingRuleTimeRestrictionRestrictionsOutputReference <a name="TeamRoutingRuleTimeRestrictionRestrictionsOutputReference" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.team_routing_rule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference;

new TeamRoutingRuleTimeRestrictionRestrictionsOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endDayInput">endDayInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endHourInput">endHourInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endMinInput">endMinInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startDayInput">startDayInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startHourInput">startHourInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startMinInput">startMinInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endDay">endDay</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endHour">endHour</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endMin">endMin</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startDay">startDay</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startHour">startHour</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startMin">startMin</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions">TeamRoutingRuleTimeRestrictionRestrictions</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `endDayInput`<sup>Optional</sup> <a name="endDayInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endDayInput"></a>

```java
public java.lang.String getEndDayInput();
```

- *Type:* java.lang.String

---

##### `endHourInput`<sup>Optional</sup> <a name="endHourInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endHourInput"></a>

```java
public java.lang.Number getEndHourInput();
```

- *Type:* java.lang.Number

---

##### `endMinInput`<sup>Optional</sup> <a name="endMinInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endMinInput"></a>

```java
public java.lang.Number getEndMinInput();
```

- *Type:* java.lang.Number

---

##### `startDayInput`<sup>Optional</sup> <a name="startDayInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startDayInput"></a>

```java
public java.lang.String getStartDayInput();
```

- *Type:* java.lang.String

---

##### `startHourInput`<sup>Optional</sup> <a name="startHourInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startHourInput"></a>

```java
public java.lang.Number getStartHourInput();
```

- *Type:* java.lang.Number

---

##### `startMinInput`<sup>Optional</sup> <a name="startMinInput" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startMinInput"></a>

```java
public java.lang.Number getStartMinInput();
```

- *Type:* java.lang.Number

---

##### `endDay`<sup>Required</sup> <a name="endDay" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endDay"></a>

```java
public java.lang.String getEndDay();
```

- *Type:* java.lang.String

---

##### `endHour`<sup>Required</sup> <a name="endHour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endHour"></a>

```java
public java.lang.Number getEndHour();
```

- *Type:* java.lang.Number

---

##### `endMin`<sup>Required</sup> <a name="endMin" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.endMin"></a>

```java
public java.lang.Number getEndMin();
```

- *Type:* java.lang.Number

---

##### `startDay`<sup>Required</sup> <a name="startDay" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startDay"></a>

```java
public java.lang.String getStartDay();
```

- *Type:* java.lang.String

---

##### `startHour`<sup>Required</sup> <a name="startHour" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startHour"></a>

```java
public java.lang.Number getStartHour();
```

- *Type:* java.lang.Number

---

##### `startMin`<sup>Required</sup> <a name="startMin" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.startMin"></a>

```java
public java.lang.Number getStartMin();
```

- *Type:* java.lang.Number

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictionsOutputReference.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.teamRoutingRule.TeamRoutingRuleTimeRestrictionRestrictions">TeamRoutingRuleTimeRestrictionRestrictions</a>

---



