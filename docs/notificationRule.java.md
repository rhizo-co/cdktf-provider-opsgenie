# `opsgenie_notification_rule`

Refer to the Terraform Registory for docs: [`opsgenie_notification_rule`](https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule).

# `notificationRule` Submodule <a name="`notificationRule` Submodule" id="rhizo-co-terraform-provider-opsgenie.notificationRule"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### NotificationRule <a name="NotificationRule" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule"></a>

Represents a {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule opsgenie_notification_rule}.

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_rule.NotificationRule;

NotificationRule.Builder.create(Construct scope, java.lang.String id)
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
    .actionType(java.lang.String)
    .name(java.lang.String)
    .username(java.lang.String)
//  .criteria(IResolvable)
//  .criteria(java.util.List<NotificationRuleCriteria>)
//  .enabled(java.lang.Boolean)
//  .enabled(IResolvable)
//  .id(java.lang.String)
//  .notificationTime(java.util.List<java.lang.String>)
//  .order(java.lang.Number)
//  .repeat(IResolvable)
//  .repeat(java.util.List<NotificationRuleRepeat>)
//  .schedules(IResolvable)
//  .schedules(java.util.List<NotificationRuleSchedules>)
//  .steps(IResolvable)
//  .steps(java.util.List<NotificationRuleSteps>)
//  .timeRestriction(IResolvable)
//  .timeRestriction(java.util.List<NotificationRuleTimeRestriction>)
    .build();
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.scope">scope</a></code> | <code>software.constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.id">id</a></code> | <code>java.lang.String</code> | The scoped construct ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.connection">connection</a></code> | <code>com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.count">count</a></code> | <code>java.lang.Number OR com.hashicorp.cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.dependsOn">dependsOn</a></code> | <code>java.util.List<com.hashicorp.cdktf.ITerraformDependable></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.forEach">forEach</a></code> | <code>com.hashicorp.cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.lifecycle">lifecycle</a></code> | <code>com.hashicorp.cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.provider">provider</a></code> | <code>com.hashicorp.cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.provisioners">provisioners</a></code> | <code>java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.actionType">actionType</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#action_type NotificationRule#action_type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.name">name</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#name NotificationRule#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.username">username</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#username NotificationRule#username}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.criteria">criteria</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteria">NotificationRuleCriteria</a>></code> | criteria block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.enabled">enabled</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#enabled NotificationRule#enabled}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.id">id</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#id NotificationRule#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.notificationTime">notificationTime</a></code> | <code>java.util.List<java.lang.String></code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#notification_time NotificationRule#notification_time}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.order">order</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#order NotificationRule#order}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.repeat">repeat</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeat">NotificationRuleRepeat</a>></code> | repeat block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.schedules">schedules</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedules">NotificationRuleSchedules</a>></code> | schedules block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.steps">steps</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSteps">NotificationRuleSteps</a>></code> | steps block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.timeRestriction">timeRestriction</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestriction">NotificationRuleTimeRestriction</a>></code> | time_restriction block. |

---

##### `scope`<sup>Required</sup> <a name="scope" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.scope"></a>

- *Type:* software.constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.id"></a>

- *Type:* java.lang.String

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.connection"></a>

- *Type:* com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.count"></a>

- *Type:* java.lang.Number OR com.hashicorp.cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.dependsOn"></a>

- *Type:* java.util.List<com.hashicorp.cdktf.ITerraformDependable>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.forEach"></a>

- *Type:* com.hashicorp.cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.lifecycle"></a>

- *Type:* com.hashicorp.cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.provider"></a>

- *Type:* com.hashicorp.cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.provisioners"></a>

- *Type:* java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner>

---

##### `actionType`<sup>Required</sup> <a name="actionType" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.actionType"></a>

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#action_type NotificationRule#action_type}.

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.name"></a>

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#name NotificationRule#name}.

---

##### `username`<sup>Required</sup> <a name="username" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.username"></a>

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#username NotificationRule#username}.

---

##### `criteria`<sup>Optional</sup> <a name="criteria" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.criteria"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteria">NotificationRuleCriteria</a>>

criteria block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#criteria NotificationRule#criteria}

---

##### `enabled`<sup>Optional</sup> <a name="enabled" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.enabled"></a>

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#enabled NotificationRule#enabled}.

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.id"></a>

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#id NotificationRule#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `notificationTime`<sup>Optional</sup> <a name="notificationTime" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.notificationTime"></a>

- *Type:* java.util.List<java.lang.String>

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#notification_time NotificationRule#notification_time}.

---

##### `order`<sup>Optional</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.order"></a>

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#order NotificationRule#order}.

---

##### `repeat`<sup>Optional</sup> <a name="repeat" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.repeat"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeat">NotificationRuleRepeat</a>>

repeat block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#repeat NotificationRule#repeat}

---

##### `schedules`<sup>Optional</sup> <a name="schedules" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.schedules"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedules">NotificationRuleSchedules</a>>

schedules block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#schedules NotificationRule#schedules}

---

##### `steps`<sup>Optional</sup> <a name="steps" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.steps"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSteps">NotificationRuleSteps</a>>

steps block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#steps NotificationRule#steps}

---

##### `timeRestriction`<sup>Optional</sup> <a name="timeRestriction" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.Initializer.parameter.timeRestriction"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestriction">NotificationRuleTimeRestriction</a>>

time_restriction block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#time_restriction NotificationRule#time_restriction}

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.toString">toString</a></code> | Returns a string representation of this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.addOverride">addOverride</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.overrideLogicalId">overrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.resetOverrideLogicalId">resetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.toMetadata">toMetadata</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.toTerraform">toTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.putCriteria">putCriteria</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.putRepeat">putRepeat</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.putSchedules">putSchedules</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.putSteps">putSteps</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.putTimeRestriction">putTimeRestriction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.resetCriteria">resetCriteria</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.resetEnabled">resetEnabled</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.resetId">resetId</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.resetNotificationTime">resetNotificationTime</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.resetOrder">resetOrder</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.resetRepeat">resetRepeat</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.resetSchedules">resetSchedules</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.resetSteps">resetSteps</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.resetTimeRestriction">resetTimeRestriction</a></code> | *No description.* |

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.toString"></a>

```java
public java.lang.String toString()
```

Returns a string representation of this construct.

##### `addOverride` <a name="addOverride" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.addOverride"></a>

```java
public void addOverride(java.lang.String path, java.lang.Object value)
```

###### `path`<sup>Required</sup> <a name="path" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.addOverride.parameter.path"></a>

- *Type:* java.lang.String

---

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.addOverride.parameter.value"></a>

- *Type:* java.lang.Object

---

##### `overrideLogicalId` <a name="overrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.overrideLogicalId"></a>

```java
public void overrideLogicalId(java.lang.String newLogicalId)
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* java.lang.String

The new logical ID to use for this stack element.

---

##### `resetOverrideLogicalId` <a name="resetOverrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.resetOverrideLogicalId"></a>

```java
public void resetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `toMetadata` <a name="toMetadata" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.toMetadata"></a>

```java
public java.lang.Object toMetadata()
```

##### `toTerraform` <a name="toTerraform" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.toTerraform"></a>

```java
public java.lang.Object toTerraform()
```

Adds this resource to the terraform JSON output.

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `putCriteria` <a name="putCriteria" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.putCriteria"></a>

```java
public void putCriteria(IResolvable OR java.util.List<NotificationRuleCriteria> value)
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.putCriteria.parameter.value"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteria">NotificationRuleCriteria</a>>

---

##### `putRepeat` <a name="putRepeat" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.putRepeat"></a>

```java
public void putRepeat(IResolvable OR java.util.List<NotificationRuleRepeat> value)
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.putRepeat.parameter.value"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeat">NotificationRuleRepeat</a>>

---

##### `putSchedules` <a name="putSchedules" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.putSchedules"></a>

```java
public void putSchedules(IResolvable OR java.util.List<NotificationRuleSchedules> value)
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.putSchedules.parameter.value"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedules">NotificationRuleSchedules</a>>

---

##### `putSteps` <a name="putSteps" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.putSteps"></a>

```java
public void putSteps(IResolvable OR java.util.List<NotificationRuleSteps> value)
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.putSteps.parameter.value"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSteps">NotificationRuleSteps</a>>

---

##### `putTimeRestriction` <a name="putTimeRestriction" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.putTimeRestriction"></a>

```java
public void putTimeRestriction(IResolvable OR java.util.List<NotificationRuleTimeRestriction> value)
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.putTimeRestriction.parameter.value"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestriction">NotificationRuleTimeRestriction</a>>

---

##### `resetCriteria` <a name="resetCriteria" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.resetCriteria"></a>

```java
public void resetCriteria()
```

##### `resetEnabled` <a name="resetEnabled" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.resetEnabled"></a>

```java
public void resetEnabled()
```

##### `resetId` <a name="resetId" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.resetId"></a>

```java
public void resetId()
```

##### `resetNotificationTime` <a name="resetNotificationTime" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.resetNotificationTime"></a>

```java
public void resetNotificationTime()
```

##### `resetOrder` <a name="resetOrder" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.resetOrder"></a>

```java
public void resetOrder()
```

##### `resetRepeat` <a name="resetRepeat" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.resetRepeat"></a>

```java
public void resetRepeat()
```

##### `resetSchedules` <a name="resetSchedules" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.resetSchedules"></a>

```java
public void resetSchedules()
```

##### `resetSteps` <a name="resetSteps" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.resetSteps"></a>

```java
public void resetSteps()
```

##### `resetTimeRestriction` <a name="resetTimeRestriction" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.resetTimeRestriction"></a>

```java
public void resetTimeRestriction()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.isConstruct">isConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.isTerraformElement">isTerraformElement</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.isTerraformResource">isTerraformResource</a></code> | *No description.* |

---

##### `isConstruct` <a name="isConstruct" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.isConstruct"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_rule.NotificationRule;

NotificationRule.isConstruct(java.lang.Object x)
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

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.isConstruct.parameter.x"></a>

- *Type:* java.lang.Object

Any object.

---

##### `isTerraformElement` <a name="isTerraformElement" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.isTerraformElement"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_rule.NotificationRule;

NotificationRule.isTerraformElement(java.lang.Object x)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.isTerraformElement.parameter.x"></a>

- *Type:* java.lang.Object

---

##### `isTerraformResource` <a name="isTerraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.isTerraformResource"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_rule.NotificationRule;

NotificationRule.isTerraformResource(java.lang.Object x)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.isTerraformResource.parameter.x"></a>

- *Type:* java.lang.Object

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.node">node</a></code> | <code>software.constructs.Node</code> | The tree node. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.cdktfStack">cdktfStack</a></code> | <code>com.hashicorp.cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.friendlyUniqueId">friendlyUniqueId</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.terraformMetaArguments">terraformMetaArguments</a></code> | <code>java.util.Map<java.lang.String, java.lang.Object></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.terraformResourceType">terraformResourceType</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.terraformGeneratorMetadata">terraformGeneratorMetadata</a></code> | <code>com.hashicorp.cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.connection">connection</a></code> | <code>com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.count">count</a></code> | <code>java.lang.Number OR com.hashicorp.cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.dependsOn">dependsOn</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.forEach">forEach</a></code> | <code>com.hashicorp.cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.lifecycle">lifecycle</a></code> | <code>com.hashicorp.cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.provider">provider</a></code> | <code>com.hashicorp.cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.provisioners">provisioners</a></code> | <code>java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.criteria">criteria</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaList">NotificationRuleCriteriaList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.repeat">repeat</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatList">NotificationRuleRepeatList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.schedules">schedules</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesList">NotificationRuleSchedulesList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.steps">steps</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsList">NotificationRuleStepsList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.timeRestriction">timeRestriction</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionList">NotificationRuleTimeRestrictionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.actionTypeInput">actionTypeInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.criteriaInput">criteriaInput</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteria">NotificationRuleCriteria</a>></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.enabledInput">enabledInput</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.idInput">idInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.nameInput">nameInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.notificationTimeInput">notificationTimeInput</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.orderInput">orderInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.repeatInput">repeatInput</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeat">NotificationRuleRepeat</a>></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.schedulesInput">schedulesInput</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedules">NotificationRuleSchedules</a>></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.stepsInput">stepsInput</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSteps">NotificationRuleSteps</a>></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.timeRestrictionInput">timeRestrictionInput</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestriction">NotificationRuleTimeRestriction</a>></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.usernameInput">usernameInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.actionType">actionType</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.enabled">enabled</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.id">id</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.name">name</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.notificationTime">notificationTime</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.order">order</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.username">username</a></code> | <code>java.lang.String</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.node"></a>

```java
public Node getNode();
```

- *Type:* software.constructs.Node

The tree node.

---

##### `cdktfStack`<sup>Required</sup> <a name="cdktfStack" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.cdktfStack"></a>

```java
public TerraformStack getCdktfStack();
```

- *Type:* com.hashicorp.cdktf.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `friendlyUniqueId`<sup>Required</sup> <a name="friendlyUniqueId" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.friendlyUniqueId"></a>

```java
public java.lang.String getFriendlyUniqueId();
```

- *Type:* java.lang.String

---

##### `terraformMetaArguments`<sup>Required</sup> <a name="terraformMetaArguments" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.terraformMetaArguments"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getTerraformMetaArguments();
```

- *Type:* java.util.Map<java.lang.String, java.lang.Object>

---

##### `terraformResourceType`<sup>Required</sup> <a name="terraformResourceType" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.terraformResourceType"></a>

```java
public java.lang.String getTerraformResourceType();
```

- *Type:* java.lang.String

---

##### `terraformGeneratorMetadata`<sup>Optional</sup> <a name="terraformGeneratorMetadata" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.terraformGeneratorMetadata"></a>

```java
public TerraformProviderGeneratorMetadata getTerraformGeneratorMetadata();
```

- *Type:* com.hashicorp.cdktf.TerraformProviderGeneratorMetadata

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.connection"></a>

```java
public java.lang.Object getConnection();
```

- *Type:* com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.count"></a>

```java
public java.lang.Object getCount();
```

- *Type:* java.lang.Number OR com.hashicorp.cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.dependsOn"></a>

```java
public java.util.List<java.lang.String> getDependsOn();
```

- *Type:* java.util.List<java.lang.String>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.forEach"></a>

```java
public ITerraformIterator getForEach();
```

- *Type:* com.hashicorp.cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.lifecycle"></a>

```java
public TerraformResourceLifecycle getLifecycle();
```

- *Type:* com.hashicorp.cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.provider"></a>

```java
public TerraformProvider getProvider();
```

- *Type:* com.hashicorp.cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.provisioners"></a>

```java
public java.lang.Object getProvisioners();
```

- *Type:* java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner>

---

##### `criteria`<sup>Required</sup> <a name="criteria" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.criteria"></a>

```java
public NotificationRuleCriteriaList getCriteria();
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaList">NotificationRuleCriteriaList</a>

---

##### `repeat`<sup>Required</sup> <a name="repeat" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.repeat"></a>

```java
public NotificationRuleRepeatList getRepeat();
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatList">NotificationRuleRepeatList</a>

---

##### `schedules`<sup>Required</sup> <a name="schedules" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.schedules"></a>

```java
public NotificationRuleSchedulesList getSchedules();
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesList">NotificationRuleSchedulesList</a>

---

##### `steps`<sup>Required</sup> <a name="steps" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.steps"></a>

```java
public NotificationRuleStepsList getSteps();
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsList">NotificationRuleStepsList</a>

---

##### `timeRestriction`<sup>Required</sup> <a name="timeRestriction" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.timeRestriction"></a>

```java
public NotificationRuleTimeRestrictionList getTimeRestriction();
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionList">NotificationRuleTimeRestrictionList</a>

---

##### `actionTypeInput`<sup>Optional</sup> <a name="actionTypeInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.actionTypeInput"></a>

```java
public java.lang.String getActionTypeInput();
```

- *Type:* java.lang.String

---

##### `criteriaInput`<sup>Optional</sup> <a name="criteriaInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.criteriaInput"></a>

```java
public java.lang.Object getCriteriaInput();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteria">NotificationRuleCriteria</a>>

---

##### `enabledInput`<sup>Optional</sup> <a name="enabledInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.enabledInput"></a>

```java
public java.lang.Object getEnabledInput();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

---

##### `idInput`<sup>Optional</sup> <a name="idInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.idInput"></a>

```java
public java.lang.String getIdInput();
```

- *Type:* java.lang.String

---

##### `nameInput`<sup>Optional</sup> <a name="nameInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.nameInput"></a>

```java
public java.lang.String getNameInput();
```

- *Type:* java.lang.String

---

##### `notificationTimeInput`<sup>Optional</sup> <a name="notificationTimeInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.notificationTimeInput"></a>

```java
public java.util.List<java.lang.String> getNotificationTimeInput();
```

- *Type:* java.util.List<java.lang.String>

---

##### `orderInput`<sup>Optional</sup> <a name="orderInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.orderInput"></a>

```java
public java.lang.Number getOrderInput();
```

- *Type:* java.lang.Number

---

##### `repeatInput`<sup>Optional</sup> <a name="repeatInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.repeatInput"></a>

```java
public java.lang.Object getRepeatInput();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeat">NotificationRuleRepeat</a>>

---

##### `schedulesInput`<sup>Optional</sup> <a name="schedulesInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.schedulesInput"></a>

```java
public java.lang.Object getSchedulesInput();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedules">NotificationRuleSchedules</a>>

---

##### `stepsInput`<sup>Optional</sup> <a name="stepsInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.stepsInput"></a>

```java
public java.lang.Object getStepsInput();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSteps">NotificationRuleSteps</a>>

---

##### `timeRestrictionInput`<sup>Optional</sup> <a name="timeRestrictionInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.timeRestrictionInput"></a>

```java
public java.lang.Object getTimeRestrictionInput();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestriction">NotificationRuleTimeRestriction</a>>

---

##### `usernameInput`<sup>Optional</sup> <a name="usernameInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.usernameInput"></a>

```java
public java.lang.String getUsernameInput();
```

- *Type:* java.lang.String

---

##### `actionType`<sup>Required</sup> <a name="actionType" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.actionType"></a>

```java
public java.lang.String getActionType();
```

- *Type:* java.lang.String

---

##### `enabled`<sup>Required</sup> <a name="enabled" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.enabled"></a>

```java
public java.lang.Object getEnabled();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.id"></a>

```java
public java.lang.String getId();
```

- *Type:* java.lang.String

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.name"></a>

```java
public java.lang.String getName();
```

- *Type:* java.lang.String

---

##### `notificationTime`<sup>Required</sup> <a name="notificationTime" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.notificationTime"></a>

```java
public java.util.List<java.lang.String> getNotificationTime();
```

- *Type:* java.util.List<java.lang.String>

---

##### `order`<sup>Required</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.order"></a>

```java
public java.lang.Number getOrder();
```

- *Type:* java.lang.Number

---

##### `username`<sup>Required</sup> <a name="username" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.username"></a>

```java
public java.lang.String getUsername();
```

- *Type:* java.lang.String

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.tfResourceType">tfResourceType</a></code> | <code>java.lang.String</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRule.property.tfResourceType"></a>

```java
public java.lang.String getTfResourceType();
```

- *Type:* java.lang.String

---

## Structs <a name="Structs" id="Structs"></a>

### NotificationRuleConfig <a name="NotificationRuleConfig" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_rule.NotificationRuleConfig;

NotificationRuleConfig.builder()
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
    .actionType(java.lang.String)
    .name(java.lang.String)
    .username(java.lang.String)
//  .criteria(IResolvable)
//  .criteria(java.util.List<NotificationRuleCriteria>)
//  .enabled(java.lang.Boolean)
//  .enabled(IResolvable)
//  .id(java.lang.String)
//  .notificationTime(java.util.List<java.lang.String>)
//  .order(java.lang.Number)
//  .repeat(IResolvable)
//  .repeat(java.util.List<NotificationRuleRepeat>)
//  .schedules(IResolvable)
//  .schedules(java.util.List<NotificationRuleSchedules>)
//  .steps(IResolvable)
//  .steps(java.util.List<NotificationRuleSteps>)
//  .timeRestriction(IResolvable)
//  .timeRestriction(java.util.List<NotificationRuleTimeRestriction>)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.property.connection">connection</a></code> | <code>com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.property.count">count</a></code> | <code>java.lang.Number OR com.hashicorp.cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.property.dependsOn">dependsOn</a></code> | <code>java.util.List<com.hashicorp.cdktf.ITerraformDependable></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.property.forEach">forEach</a></code> | <code>com.hashicorp.cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.property.lifecycle">lifecycle</a></code> | <code>com.hashicorp.cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.property.provider">provider</a></code> | <code>com.hashicorp.cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.property.provisioners">provisioners</a></code> | <code>java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.property.actionType">actionType</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#action_type NotificationRule#action_type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.property.name">name</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#name NotificationRule#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.property.username">username</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#username NotificationRule#username}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.property.criteria">criteria</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteria">NotificationRuleCriteria</a>></code> | criteria block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.property.enabled">enabled</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#enabled NotificationRule#enabled}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.property.id">id</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#id NotificationRule#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.property.notificationTime">notificationTime</a></code> | <code>java.util.List<java.lang.String></code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#notification_time NotificationRule#notification_time}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.property.order">order</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#order NotificationRule#order}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.property.repeat">repeat</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeat">NotificationRuleRepeat</a>></code> | repeat block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.property.schedules">schedules</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedules">NotificationRuleSchedules</a>></code> | schedules block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.property.steps">steps</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSteps">NotificationRuleSteps</a>></code> | steps block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.property.timeRestriction">timeRestriction</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestriction">NotificationRuleTimeRestriction</a>></code> | time_restriction block. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.property.connection"></a>

```java
public java.lang.Object getConnection();
```

- *Type:* com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.property.count"></a>

```java
public java.lang.Object getCount();
```

- *Type:* java.lang.Number OR com.hashicorp.cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.property.dependsOn"></a>

```java
public java.util.List<ITerraformDependable> getDependsOn();
```

- *Type:* java.util.List<com.hashicorp.cdktf.ITerraformDependable>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.property.forEach"></a>

```java
public ITerraformIterator getForEach();
```

- *Type:* com.hashicorp.cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.property.lifecycle"></a>

```java
public TerraformResourceLifecycle getLifecycle();
```

- *Type:* com.hashicorp.cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.property.provider"></a>

```java
public TerraformProvider getProvider();
```

- *Type:* com.hashicorp.cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.property.provisioners"></a>

```java
public java.lang.Object getProvisioners();
```

- *Type:* java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner>

---

##### `actionType`<sup>Required</sup> <a name="actionType" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.property.actionType"></a>

```java
public java.lang.String getActionType();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#action_type NotificationRule#action_type}.

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.property.name"></a>

```java
public java.lang.String getName();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#name NotificationRule#name}.

---

##### `username`<sup>Required</sup> <a name="username" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.property.username"></a>

```java
public java.lang.String getUsername();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#username NotificationRule#username}.

---

##### `criteria`<sup>Optional</sup> <a name="criteria" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.property.criteria"></a>

```java
public java.lang.Object getCriteria();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteria">NotificationRuleCriteria</a>>

criteria block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#criteria NotificationRule#criteria}

---

##### `enabled`<sup>Optional</sup> <a name="enabled" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.property.enabled"></a>

```java
public java.lang.Object getEnabled();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#enabled NotificationRule#enabled}.

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.property.id"></a>

```java
public java.lang.String getId();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#id NotificationRule#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `notificationTime`<sup>Optional</sup> <a name="notificationTime" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.property.notificationTime"></a>

```java
public java.util.List<java.lang.String> getNotificationTime();
```

- *Type:* java.util.List<java.lang.String>

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#notification_time NotificationRule#notification_time}.

---

##### `order`<sup>Optional</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.property.order"></a>

```java
public java.lang.Number getOrder();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#order NotificationRule#order}.

---

##### `repeat`<sup>Optional</sup> <a name="repeat" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.property.repeat"></a>

```java
public java.lang.Object getRepeat();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeat">NotificationRuleRepeat</a>>

repeat block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#repeat NotificationRule#repeat}

---

##### `schedules`<sup>Optional</sup> <a name="schedules" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.property.schedules"></a>

```java
public java.lang.Object getSchedules();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedules">NotificationRuleSchedules</a>>

schedules block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#schedules NotificationRule#schedules}

---

##### `steps`<sup>Optional</sup> <a name="steps" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.property.steps"></a>

```java
public java.lang.Object getSteps();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSteps">NotificationRuleSteps</a>>

steps block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#steps NotificationRule#steps}

---

##### `timeRestriction`<sup>Optional</sup> <a name="timeRestriction" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleConfig.property.timeRestriction"></a>

```java
public java.lang.Object getTimeRestriction();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestriction">NotificationRuleTimeRestriction</a>>

time_restriction block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#time_restriction NotificationRule#time_restriction}

---

### NotificationRuleCriteria <a name="NotificationRuleCriteria" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteria"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteria.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_rule.NotificationRuleCriteria;

NotificationRuleCriteria.builder()
    .type(java.lang.String)
//  .conditions(IResolvable)
//  .conditions(java.util.List<NotificationRuleCriteriaConditions>)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteria.property.type">type</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#type NotificationRule#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteria.property.conditions">conditions</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditions">NotificationRuleCriteriaConditions</a>></code> | conditions block. |

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteria.property.type"></a>

```java
public java.lang.String getType();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#type NotificationRule#type}.

---

##### `conditions`<sup>Optional</sup> <a name="conditions" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteria.property.conditions"></a>

```java
public java.lang.Object getConditions();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditions">NotificationRuleCriteriaConditions</a>>

conditions block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#conditions NotificationRule#conditions}

---

### NotificationRuleCriteriaConditions <a name="NotificationRuleCriteriaConditions" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditions"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditions.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_rule.NotificationRuleCriteriaConditions;

NotificationRuleCriteriaConditions.builder()
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
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditions.property.field">field</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#field NotificationRule#field}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditions.property.operation">operation</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#operation NotificationRule#operation}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditions.property.expectedValue">expectedValue</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#expected_value NotificationRule#expected_value}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditions.property.key">key</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#key NotificationRule#key}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditions.property.not">not</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#not NotificationRule#not}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditions.property.order">order</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#order NotificationRule#order}. |

---

##### `field`<sup>Required</sup> <a name="field" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditions.property.field"></a>

```java
public java.lang.String getField();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#field NotificationRule#field}.

---

##### `operation`<sup>Required</sup> <a name="operation" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditions.property.operation"></a>

```java
public java.lang.String getOperation();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#operation NotificationRule#operation}.

---

##### `expectedValue`<sup>Optional</sup> <a name="expectedValue" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditions.property.expectedValue"></a>

```java
public java.lang.String getExpectedValue();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#expected_value NotificationRule#expected_value}.

---

##### `key`<sup>Optional</sup> <a name="key" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditions.property.key"></a>

```java
public java.lang.String getKey();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#key NotificationRule#key}.

---

##### `not`<sup>Optional</sup> <a name="not" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditions.property.not"></a>

```java
public java.lang.Object getNot();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#not NotificationRule#not}.

---

##### `order`<sup>Optional</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditions.property.order"></a>

```java
public java.lang.Number getOrder();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#order NotificationRule#order}.

---

### NotificationRuleRepeat <a name="NotificationRuleRepeat" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeat"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeat.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_rule.NotificationRuleRepeat;

NotificationRuleRepeat.builder()
    .loopAfter(java.lang.Number)
//  .enabled(java.lang.Boolean)
//  .enabled(IResolvable)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeat.property.loopAfter">loopAfter</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#loop_after NotificationRule#loop_after}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeat.property.enabled">enabled</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#enabled NotificationRule#enabled}. |

---

##### `loopAfter`<sup>Required</sup> <a name="loopAfter" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeat.property.loopAfter"></a>

```java
public java.lang.Number getLoopAfter();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#loop_after NotificationRule#loop_after}.

---

##### `enabled`<sup>Optional</sup> <a name="enabled" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeat.property.enabled"></a>

```java
public java.lang.Object getEnabled();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#enabled NotificationRule#enabled}.

---

### NotificationRuleSchedules <a name="NotificationRuleSchedules" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedules"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedules.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_rule.NotificationRuleSchedules;

NotificationRuleSchedules.builder()
    .name(java.lang.String)
    .type(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedules.property.name">name</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#name NotificationRule#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedules.property.type">type</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#type NotificationRule#type}. |

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedules.property.name"></a>

```java
public java.lang.String getName();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#name NotificationRule#name}.

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedules.property.type"></a>

```java
public java.lang.String getType();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#type NotificationRule#type}.

---

### NotificationRuleSteps <a name="NotificationRuleSteps" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSteps"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSteps.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_rule.NotificationRuleSteps;

NotificationRuleSteps.builder()
    .contact(IResolvable)
    .contact(java.util.List<NotificationRuleStepsContact>)
//  .enabled(java.lang.Boolean)
//  .enabled(IResolvable)
//  .sendAfter(java.lang.Number)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSteps.property.contact">contact</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContact">NotificationRuleStepsContact</a>></code> | contact block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSteps.property.enabled">enabled</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#enabled NotificationRule#enabled}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSteps.property.sendAfter">sendAfter</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#send_after NotificationRule#send_after}. |

---

##### `contact`<sup>Required</sup> <a name="contact" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSteps.property.contact"></a>

```java
public java.lang.Object getContact();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContact">NotificationRuleStepsContact</a>>

contact block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#contact NotificationRule#contact}

---

##### `enabled`<sup>Optional</sup> <a name="enabled" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSteps.property.enabled"></a>

```java
public java.lang.Object getEnabled();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#enabled NotificationRule#enabled}.

---

##### `sendAfter`<sup>Optional</sup> <a name="sendAfter" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSteps.property.sendAfter"></a>

```java
public java.lang.Number getSendAfter();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#send_after NotificationRule#send_after}.

---

### NotificationRuleStepsContact <a name="NotificationRuleStepsContact" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContact"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContact.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_rule.NotificationRuleStepsContact;

NotificationRuleStepsContact.builder()
    .method(java.lang.String)
    .to(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContact.property.method">method</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#method NotificationRule#method}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContact.property.to">to</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#to NotificationRule#to}. |

---

##### `method`<sup>Required</sup> <a name="method" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContact.property.method"></a>

```java
public java.lang.String getMethod();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#method NotificationRule#method}.

---

##### `to`<sup>Required</sup> <a name="to" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContact.property.to"></a>

```java
public java.lang.String getTo();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#to NotificationRule#to}.

---

### NotificationRuleTimeRestriction <a name="NotificationRuleTimeRestriction" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestriction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestriction.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_rule.NotificationRuleTimeRestriction;

NotificationRuleTimeRestriction.builder()
    .type(java.lang.String)
//  .restriction(IResolvable)
//  .restriction(java.util.List<NotificationRuleTimeRestrictionRestriction>)
//  .restrictions(IResolvable)
//  .restrictions(java.util.List<NotificationRuleTimeRestrictionRestrictions>)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestriction.property.type">type</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#type NotificationRule#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestriction.property.restriction">restriction</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestriction">NotificationRuleTimeRestrictionRestriction</a>></code> | restriction block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestriction.property.restrictions">restrictions</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictions">NotificationRuleTimeRestrictionRestrictions</a>></code> | restrictions block. |

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestriction.property.type"></a>

```java
public java.lang.String getType();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#type NotificationRule#type}.

---

##### `restriction`<sup>Optional</sup> <a name="restriction" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestriction.property.restriction"></a>

```java
public java.lang.Object getRestriction();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestriction">NotificationRuleTimeRestrictionRestriction</a>>

restriction block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#restriction NotificationRule#restriction}

---

##### `restrictions`<sup>Optional</sup> <a name="restrictions" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestriction.property.restrictions"></a>

```java
public java.lang.Object getRestrictions();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictions">NotificationRuleTimeRestrictionRestrictions</a>>

restrictions block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#restrictions NotificationRule#restrictions}

---

### NotificationRuleTimeRestrictionRestriction <a name="NotificationRuleTimeRestrictionRestriction" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestriction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestriction.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_rule.NotificationRuleTimeRestrictionRestriction;

NotificationRuleTimeRestrictionRestriction.builder()
    .endHour(java.lang.Number)
    .endMin(java.lang.Number)
    .startHour(java.lang.Number)
    .startMin(java.lang.Number)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestriction.property.endHour">endHour</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#end_hour NotificationRule#end_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestriction.property.endMin">endMin</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#end_min NotificationRule#end_min}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestriction.property.startHour">startHour</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#start_hour NotificationRule#start_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestriction.property.startMin">startMin</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#start_min NotificationRule#start_min}. |

---

##### `endHour`<sup>Required</sup> <a name="endHour" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestriction.property.endHour"></a>

```java
public java.lang.Number getEndHour();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#end_hour NotificationRule#end_hour}.

---

##### `endMin`<sup>Required</sup> <a name="endMin" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestriction.property.endMin"></a>

```java
public java.lang.Number getEndMin();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#end_min NotificationRule#end_min}.

---

##### `startHour`<sup>Required</sup> <a name="startHour" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestriction.property.startHour"></a>

```java
public java.lang.Number getStartHour();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#start_hour NotificationRule#start_hour}.

---

##### `startMin`<sup>Required</sup> <a name="startMin" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestriction.property.startMin"></a>

```java
public java.lang.Number getStartMin();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#start_min NotificationRule#start_min}.

---

### NotificationRuleTimeRestrictionRestrictions <a name="NotificationRuleTimeRestrictionRestrictions" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictions"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictions.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_rule.NotificationRuleTimeRestrictionRestrictions;

NotificationRuleTimeRestrictionRestrictions.builder()
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
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictions.property.endDay">endDay</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#end_day NotificationRule#end_day}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictions.property.endHour">endHour</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#end_hour NotificationRule#end_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictions.property.endMin">endMin</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#end_min NotificationRule#end_min}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictions.property.startDay">startDay</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#start_day NotificationRule#start_day}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictions.property.startHour">startHour</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#start_hour NotificationRule#start_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictions.property.startMin">startMin</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#start_min NotificationRule#start_min}. |

---

##### `endDay`<sup>Required</sup> <a name="endDay" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictions.property.endDay"></a>

```java
public java.lang.String getEndDay();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#end_day NotificationRule#end_day}.

---

##### `endHour`<sup>Required</sup> <a name="endHour" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictions.property.endHour"></a>

```java
public java.lang.Number getEndHour();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#end_hour NotificationRule#end_hour}.

---

##### `endMin`<sup>Required</sup> <a name="endMin" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictions.property.endMin"></a>

```java
public java.lang.Number getEndMin();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#end_min NotificationRule#end_min}.

---

##### `startDay`<sup>Required</sup> <a name="startDay" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictions.property.startDay"></a>

```java
public java.lang.String getStartDay();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#start_day NotificationRule#start_day}.

---

##### `startHour`<sup>Required</sup> <a name="startHour" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictions.property.startHour"></a>

```java
public java.lang.Number getStartHour();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#start_hour NotificationRule#start_hour}.

---

##### `startMin`<sup>Required</sup> <a name="startMin" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictions.property.startMin"></a>

```java
public java.lang.Number getStartMin();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_rule#start_min NotificationRule#start_min}.

---

## Classes <a name="Classes" id="Classes"></a>

### NotificationRuleCriteriaConditionsList <a name="NotificationRuleCriteriaConditionsList" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsList.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_rule.NotificationRuleCriteriaConditionsList;

new NotificationRuleCriteriaConditionsList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsList.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsList.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsList.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsList.get"></a>

```java
public NotificationRuleCriteriaConditionsOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsList.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditions">NotificationRuleCriteriaConditions</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsList.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditions">NotificationRuleCriteriaConditions</a>>

---


### NotificationRuleCriteriaConditionsOutputReference <a name="NotificationRuleCriteriaConditionsOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_rule.NotificationRuleCriteriaConditionsOutputReference;

new NotificationRuleCriteriaConditionsOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.resetExpectedValue">resetExpectedValue</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.resetKey">resetKey</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.resetNot">resetNot</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.resetOrder">resetOrder</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetExpectedValue` <a name="resetExpectedValue" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.resetExpectedValue"></a>

```java
public void resetExpectedValue()
```

##### `resetKey` <a name="resetKey" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.resetKey"></a>

```java
public void resetKey()
```

##### `resetNot` <a name="resetNot" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.resetNot"></a>

```java
public void resetNot()
```

##### `resetOrder` <a name="resetOrder" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.resetOrder"></a>

```java
public void resetOrder()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.property.expectedValueInput">expectedValueInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.property.fieldInput">fieldInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.property.keyInput">keyInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.property.notInput">notInput</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.property.operationInput">operationInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.property.orderInput">orderInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.property.expectedValue">expectedValue</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.property.field">field</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.property.key">key</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.property.not">not</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.property.operation">operation</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.property.order">order</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditions">NotificationRuleCriteriaConditions</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `expectedValueInput`<sup>Optional</sup> <a name="expectedValueInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.property.expectedValueInput"></a>

```java
public java.lang.String getExpectedValueInput();
```

- *Type:* java.lang.String

---

##### `fieldInput`<sup>Optional</sup> <a name="fieldInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.property.fieldInput"></a>

```java
public java.lang.String getFieldInput();
```

- *Type:* java.lang.String

---

##### `keyInput`<sup>Optional</sup> <a name="keyInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.property.keyInput"></a>

```java
public java.lang.String getKeyInput();
```

- *Type:* java.lang.String

---

##### `notInput`<sup>Optional</sup> <a name="notInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.property.notInput"></a>

```java
public java.lang.Object getNotInput();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

---

##### `operationInput`<sup>Optional</sup> <a name="operationInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.property.operationInput"></a>

```java
public java.lang.String getOperationInput();
```

- *Type:* java.lang.String

---

##### `orderInput`<sup>Optional</sup> <a name="orderInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.property.orderInput"></a>

```java
public java.lang.Number getOrderInput();
```

- *Type:* java.lang.Number

---

##### `expectedValue`<sup>Required</sup> <a name="expectedValue" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.property.expectedValue"></a>

```java
public java.lang.String getExpectedValue();
```

- *Type:* java.lang.String

---

##### `field`<sup>Required</sup> <a name="field" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.property.field"></a>

```java
public java.lang.String getField();
```

- *Type:* java.lang.String

---

##### `key`<sup>Required</sup> <a name="key" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.property.key"></a>

```java
public java.lang.String getKey();
```

- *Type:* java.lang.String

---

##### `not`<sup>Required</sup> <a name="not" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.property.not"></a>

```java
public java.lang.Object getNot();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

---

##### `operation`<sup>Required</sup> <a name="operation" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.property.operation"></a>

```java
public java.lang.String getOperation();
```

- *Type:* java.lang.String

---

##### `order`<sup>Required</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.property.order"></a>

```java
public java.lang.Number getOrder();
```

- *Type:* java.lang.Number

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsOutputReference.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditions">NotificationRuleCriteriaConditions</a>

---


### NotificationRuleCriteriaList <a name="NotificationRuleCriteriaList" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaList.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_rule.NotificationRuleCriteriaList;

new NotificationRuleCriteriaList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaList.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaList.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaList.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaList.get"></a>

```java
public NotificationRuleCriteriaOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaList.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteria">NotificationRuleCriteria</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaList.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteria">NotificationRuleCriteria</a>>

---


### NotificationRuleCriteriaOutputReference <a name="NotificationRuleCriteriaOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_rule.NotificationRuleCriteriaOutputReference;

new NotificationRuleCriteriaOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.putConditions">putConditions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.resetConditions">resetConditions</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `putConditions` <a name="putConditions" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.putConditions"></a>

```java
public void putConditions(IResolvable OR java.util.List<NotificationRuleCriteriaConditions> value)
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.putConditions.parameter.value"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditions">NotificationRuleCriteriaConditions</a>>

---

##### `resetConditions` <a name="resetConditions" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.resetConditions"></a>

```java
public void resetConditions()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.property.conditions">conditions</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsList">NotificationRuleCriteriaConditionsList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.property.conditionsInput">conditionsInput</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditions">NotificationRuleCriteriaConditions</a>></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.property.typeInput">typeInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.property.type">type</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteria">NotificationRuleCriteria</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `conditions`<sup>Required</sup> <a name="conditions" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.property.conditions"></a>

```java
public NotificationRuleCriteriaConditionsList getConditions();
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditionsList">NotificationRuleCriteriaConditionsList</a>

---

##### `conditionsInput`<sup>Optional</sup> <a name="conditionsInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.property.conditionsInput"></a>

```java
public java.lang.Object getConditionsInput();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaConditions">NotificationRuleCriteriaConditions</a>>

---

##### `typeInput`<sup>Optional</sup> <a name="typeInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.property.typeInput"></a>

```java
public java.lang.String getTypeInput();
```

- *Type:* java.lang.String

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.property.type"></a>

```java
public java.lang.String getType();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteriaOutputReference.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleCriteria">NotificationRuleCriteria</a>

---


### NotificationRuleRepeatList <a name="NotificationRuleRepeatList" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatList.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_rule.NotificationRuleRepeatList;

new NotificationRuleRepeatList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatList.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatList.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatList.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatList.get"></a>

```java
public NotificationRuleRepeatOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatList.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeat">NotificationRuleRepeat</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatList.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeat">NotificationRuleRepeat</a>>

---


### NotificationRuleRepeatOutputReference <a name="NotificationRuleRepeatOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_rule.NotificationRuleRepeatOutputReference;

new NotificationRuleRepeatOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.resetEnabled">resetEnabled</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetEnabled` <a name="resetEnabled" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.resetEnabled"></a>

```java
public void resetEnabled()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.property.enabledInput">enabledInput</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.property.loopAfterInput">loopAfterInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.property.enabled">enabled</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.property.loopAfter">loopAfter</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeat">NotificationRuleRepeat</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `enabledInput`<sup>Optional</sup> <a name="enabledInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.property.enabledInput"></a>

```java
public java.lang.Object getEnabledInput();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

---

##### `loopAfterInput`<sup>Optional</sup> <a name="loopAfterInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.property.loopAfterInput"></a>

```java
public java.lang.Number getLoopAfterInput();
```

- *Type:* java.lang.Number

---

##### `enabled`<sup>Required</sup> <a name="enabled" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.property.enabled"></a>

```java
public java.lang.Object getEnabled();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

---

##### `loopAfter`<sup>Required</sup> <a name="loopAfter" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.property.loopAfter"></a>

```java
public java.lang.Number getLoopAfter();
```

- *Type:* java.lang.Number

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeatOutputReference.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleRepeat">NotificationRuleRepeat</a>

---


### NotificationRuleSchedulesList <a name="NotificationRuleSchedulesList" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesList.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_rule.NotificationRuleSchedulesList;

new NotificationRuleSchedulesList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesList.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesList.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesList.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesList.get"></a>

```java
public NotificationRuleSchedulesOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesList.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedules">NotificationRuleSchedules</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesList.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedules">NotificationRuleSchedules</a>>

---


### NotificationRuleSchedulesOutputReference <a name="NotificationRuleSchedulesOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_rule.NotificationRuleSchedulesOutputReference;

new NotificationRuleSchedulesOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.property.nameInput">nameInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.property.typeInput">typeInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.property.name">name</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.property.type">type</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedules">NotificationRuleSchedules</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `nameInput`<sup>Optional</sup> <a name="nameInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.property.nameInput"></a>

```java
public java.lang.String getNameInput();
```

- *Type:* java.lang.String

---

##### `typeInput`<sup>Optional</sup> <a name="typeInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.property.typeInput"></a>

```java
public java.lang.String getTypeInput();
```

- *Type:* java.lang.String

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.property.name"></a>

```java
public java.lang.String getName();
```

- *Type:* java.lang.String

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.property.type"></a>

```java
public java.lang.String getType();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedulesOutputReference.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSchedules">NotificationRuleSchedules</a>

---


### NotificationRuleStepsContactList <a name="NotificationRuleStepsContactList" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactList.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_rule.NotificationRuleStepsContactList;

new NotificationRuleStepsContactList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactList.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactList.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactList.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactList.get"></a>

```java
public NotificationRuleStepsContactOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactList.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContact">NotificationRuleStepsContact</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactList.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContact">NotificationRuleStepsContact</a>>

---


### NotificationRuleStepsContactOutputReference <a name="NotificationRuleStepsContactOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_rule.NotificationRuleStepsContactOutputReference;

new NotificationRuleStepsContactOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.property.methodInput">methodInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.property.toInput">toInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.property.method">method</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.property.to">to</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContact">NotificationRuleStepsContact</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `methodInput`<sup>Optional</sup> <a name="methodInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.property.methodInput"></a>

```java
public java.lang.String getMethodInput();
```

- *Type:* java.lang.String

---

##### `toInput`<sup>Optional</sup> <a name="toInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.property.toInput"></a>

```java
public java.lang.String getToInput();
```

- *Type:* java.lang.String

---

##### `method`<sup>Required</sup> <a name="method" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.property.method"></a>

```java
public java.lang.String getMethod();
```

- *Type:* java.lang.String

---

##### `to`<sup>Required</sup> <a name="to" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.property.to"></a>

```java
public java.lang.String getTo();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactOutputReference.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContact">NotificationRuleStepsContact</a>

---


### NotificationRuleStepsList <a name="NotificationRuleStepsList" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsList.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_rule.NotificationRuleStepsList;

new NotificationRuleStepsList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsList.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsList.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsList.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsList.get"></a>

```java
public NotificationRuleStepsOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsList.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSteps">NotificationRuleSteps</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsList.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSteps">NotificationRuleSteps</a>>

---


### NotificationRuleStepsOutputReference <a name="NotificationRuleStepsOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_rule.NotificationRuleStepsOutputReference;

new NotificationRuleStepsOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.putContact">putContact</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.resetEnabled">resetEnabled</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.resetSendAfter">resetSendAfter</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `putContact` <a name="putContact" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.putContact"></a>

```java
public void putContact(IResolvable OR java.util.List<NotificationRuleStepsContact> value)
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.putContact.parameter.value"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContact">NotificationRuleStepsContact</a>>

---

##### `resetEnabled` <a name="resetEnabled" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.resetEnabled"></a>

```java
public void resetEnabled()
```

##### `resetSendAfter` <a name="resetSendAfter" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.resetSendAfter"></a>

```java
public void resetSendAfter()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.property.contact">contact</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactList">NotificationRuleStepsContactList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.property.contactInput">contactInput</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContact">NotificationRuleStepsContact</a>></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.property.enabledInput">enabledInput</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.property.sendAfterInput">sendAfterInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.property.enabled">enabled</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.property.sendAfter">sendAfter</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSteps">NotificationRuleSteps</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `contact`<sup>Required</sup> <a name="contact" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.property.contact"></a>

```java
public NotificationRuleStepsContactList getContact();
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContactList">NotificationRuleStepsContactList</a>

---

##### `contactInput`<sup>Optional</sup> <a name="contactInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.property.contactInput"></a>

```java
public java.lang.Object getContactInput();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsContact">NotificationRuleStepsContact</a>>

---

##### `enabledInput`<sup>Optional</sup> <a name="enabledInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.property.enabledInput"></a>

```java
public java.lang.Object getEnabledInput();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

---

##### `sendAfterInput`<sup>Optional</sup> <a name="sendAfterInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.property.sendAfterInput"></a>

```java
public java.lang.Number getSendAfterInput();
```

- *Type:* java.lang.Number

---

##### `enabled`<sup>Required</sup> <a name="enabled" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.property.enabled"></a>

```java
public java.lang.Object getEnabled();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

---

##### `sendAfter`<sup>Required</sup> <a name="sendAfter" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.property.sendAfter"></a>

```java
public java.lang.Number getSendAfter();
```

- *Type:* java.lang.Number

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleStepsOutputReference.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleSteps">NotificationRuleSteps</a>

---


### NotificationRuleTimeRestrictionList <a name="NotificationRuleTimeRestrictionList" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionList.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_rule.NotificationRuleTimeRestrictionList;

new NotificationRuleTimeRestrictionList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionList.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionList.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionList.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionList.get"></a>

```java
public NotificationRuleTimeRestrictionOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionList.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestriction">NotificationRuleTimeRestriction</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionList.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestriction">NotificationRuleTimeRestriction</a>>

---


### NotificationRuleTimeRestrictionOutputReference <a name="NotificationRuleTimeRestrictionOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_rule.NotificationRuleTimeRestrictionOutputReference;

new NotificationRuleTimeRestrictionOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.putRestriction">putRestriction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.putRestrictions">putRestrictions</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.resetRestriction">resetRestriction</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.resetRestrictions">resetRestrictions</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `putRestriction` <a name="putRestriction" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.putRestriction"></a>

```java
public void putRestriction(IResolvable OR java.util.List<NotificationRuleTimeRestrictionRestriction> value)
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.putRestriction.parameter.value"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestriction">NotificationRuleTimeRestrictionRestriction</a>>

---

##### `putRestrictions` <a name="putRestrictions" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.putRestrictions"></a>

```java
public void putRestrictions(IResolvable OR java.util.List<NotificationRuleTimeRestrictionRestrictions> value)
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.putRestrictions.parameter.value"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictions">NotificationRuleTimeRestrictionRestrictions</a>>

---

##### `resetRestriction` <a name="resetRestriction" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.resetRestriction"></a>

```java
public void resetRestriction()
```

##### `resetRestrictions` <a name="resetRestrictions" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.resetRestrictions"></a>

```java
public void resetRestrictions()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.property.restriction">restriction</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionList">NotificationRuleTimeRestrictionRestrictionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.property.restrictions">restrictions</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsList">NotificationRuleTimeRestrictionRestrictionsList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.property.restrictionInput">restrictionInput</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestriction">NotificationRuleTimeRestrictionRestriction</a>></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.property.restrictionsInput">restrictionsInput</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictions">NotificationRuleTimeRestrictionRestrictions</a>></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.property.typeInput">typeInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.property.type">type</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestriction">NotificationRuleTimeRestriction</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `restriction`<sup>Required</sup> <a name="restriction" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.property.restriction"></a>

```java
public NotificationRuleTimeRestrictionRestrictionList getRestriction();
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionList">NotificationRuleTimeRestrictionRestrictionList</a>

---

##### `restrictions`<sup>Required</sup> <a name="restrictions" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.property.restrictions"></a>

```java
public NotificationRuleTimeRestrictionRestrictionsList getRestrictions();
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsList">NotificationRuleTimeRestrictionRestrictionsList</a>

---

##### `restrictionInput`<sup>Optional</sup> <a name="restrictionInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.property.restrictionInput"></a>

```java
public java.lang.Object getRestrictionInput();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestriction">NotificationRuleTimeRestrictionRestriction</a>>

---

##### `restrictionsInput`<sup>Optional</sup> <a name="restrictionsInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.property.restrictionsInput"></a>

```java
public java.lang.Object getRestrictionsInput();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictions">NotificationRuleTimeRestrictionRestrictions</a>>

---

##### `typeInput`<sup>Optional</sup> <a name="typeInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.property.typeInput"></a>

```java
public java.lang.String getTypeInput();
```

- *Type:* java.lang.String

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.property.type"></a>

```java
public java.lang.String getType();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionOutputReference.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestriction">NotificationRuleTimeRestriction</a>

---


### NotificationRuleTimeRestrictionRestrictionList <a name="NotificationRuleTimeRestrictionRestrictionList" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionList.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_rule.NotificationRuleTimeRestrictionRestrictionList;

new NotificationRuleTimeRestrictionRestrictionList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionList.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionList.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionList.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionList.get"></a>

```java
public NotificationRuleTimeRestrictionRestrictionOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionList.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestriction">NotificationRuleTimeRestrictionRestriction</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionList.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestriction">NotificationRuleTimeRestrictionRestriction</a>>

---


### NotificationRuleTimeRestrictionRestrictionOutputReference <a name="NotificationRuleTimeRestrictionRestrictionOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_rule.NotificationRuleTimeRestrictionRestrictionOutputReference;

new NotificationRuleTimeRestrictionRestrictionOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.property.endHourInput">endHourInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.property.endMinInput">endMinInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.property.startHourInput">startHourInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.property.startMinInput">startMinInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.property.endHour">endHour</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.property.endMin">endMin</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.property.startHour">startHour</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.property.startMin">startMin</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestriction">NotificationRuleTimeRestrictionRestriction</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `endHourInput`<sup>Optional</sup> <a name="endHourInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.property.endHourInput"></a>

```java
public java.lang.Number getEndHourInput();
```

- *Type:* java.lang.Number

---

##### `endMinInput`<sup>Optional</sup> <a name="endMinInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.property.endMinInput"></a>

```java
public java.lang.Number getEndMinInput();
```

- *Type:* java.lang.Number

---

##### `startHourInput`<sup>Optional</sup> <a name="startHourInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.property.startHourInput"></a>

```java
public java.lang.Number getStartHourInput();
```

- *Type:* java.lang.Number

---

##### `startMinInput`<sup>Optional</sup> <a name="startMinInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.property.startMinInput"></a>

```java
public java.lang.Number getStartMinInput();
```

- *Type:* java.lang.Number

---

##### `endHour`<sup>Required</sup> <a name="endHour" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.property.endHour"></a>

```java
public java.lang.Number getEndHour();
```

- *Type:* java.lang.Number

---

##### `endMin`<sup>Required</sup> <a name="endMin" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.property.endMin"></a>

```java
public java.lang.Number getEndMin();
```

- *Type:* java.lang.Number

---

##### `startHour`<sup>Required</sup> <a name="startHour" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.property.startHour"></a>

```java
public java.lang.Number getStartHour();
```

- *Type:* java.lang.Number

---

##### `startMin`<sup>Required</sup> <a name="startMin" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.property.startMin"></a>

```java
public java.lang.Number getStartMin();
```

- *Type:* java.lang.Number

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionOutputReference.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestriction">NotificationRuleTimeRestrictionRestriction</a>

---


### NotificationRuleTimeRestrictionRestrictionsList <a name="NotificationRuleTimeRestrictionRestrictionsList" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsList.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_rule.NotificationRuleTimeRestrictionRestrictionsList;

new NotificationRuleTimeRestrictionRestrictionsList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsList.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsList.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsList.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsList.toString">toString</a></code> | Return a string representation of this resolvable object. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsList.get">get</a></code> | *No description.* |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsList.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsList.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsList.get"></a>

```java
public NotificationRuleTimeRestrictionRestrictionsOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsList.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictions">NotificationRuleTimeRestrictionRestrictions</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsList.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictions">NotificationRuleTimeRestrictionRestrictions</a>>

---


### NotificationRuleTimeRestrictionRestrictionsOutputReference <a name="NotificationRuleTimeRestrictionRestrictionsOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_rule.NotificationRuleTimeRestrictionRestrictionsOutputReference;

new NotificationRuleTimeRestrictionRestrictionsOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

whether the list is wrapping a set (will add tolist() to be able to access an item via an index).

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.computeFqn">computeFqn</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.resolve">resolve</a></code> | Produce the Token's value at resolution time. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.toString">toString</a></code> | Return a string representation of this resolvable object. |

---

##### `computeFqn` <a name="computeFqn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.computeFqn"></a>

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.property.endDayInput">endDayInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.property.endHourInput">endHourInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.property.endMinInput">endMinInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.property.startDayInput">startDayInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.property.startHourInput">startHourInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.property.startMinInput">startMinInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.property.endDay">endDay</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.property.endHour">endHour</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.property.endMin">endMin</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.property.startDay">startDay</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.property.startHour">startHour</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.property.startMin">startMin</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictions">NotificationRuleTimeRestrictionRestrictions</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `endDayInput`<sup>Optional</sup> <a name="endDayInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.property.endDayInput"></a>

```java
public java.lang.String getEndDayInput();
```

- *Type:* java.lang.String

---

##### `endHourInput`<sup>Optional</sup> <a name="endHourInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.property.endHourInput"></a>

```java
public java.lang.Number getEndHourInput();
```

- *Type:* java.lang.Number

---

##### `endMinInput`<sup>Optional</sup> <a name="endMinInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.property.endMinInput"></a>

```java
public java.lang.Number getEndMinInput();
```

- *Type:* java.lang.Number

---

##### `startDayInput`<sup>Optional</sup> <a name="startDayInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.property.startDayInput"></a>

```java
public java.lang.String getStartDayInput();
```

- *Type:* java.lang.String

---

##### `startHourInput`<sup>Optional</sup> <a name="startHourInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.property.startHourInput"></a>

```java
public java.lang.Number getStartHourInput();
```

- *Type:* java.lang.Number

---

##### `startMinInput`<sup>Optional</sup> <a name="startMinInput" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.property.startMinInput"></a>

```java
public java.lang.Number getStartMinInput();
```

- *Type:* java.lang.Number

---

##### `endDay`<sup>Required</sup> <a name="endDay" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.property.endDay"></a>

```java
public java.lang.String getEndDay();
```

- *Type:* java.lang.String

---

##### `endHour`<sup>Required</sup> <a name="endHour" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.property.endHour"></a>

```java
public java.lang.Number getEndHour();
```

- *Type:* java.lang.Number

---

##### `endMin`<sup>Required</sup> <a name="endMin" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.property.endMin"></a>

```java
public java.lang.Number getEndMin();
```

- *Type:* java.lang.Number

---

##### `startDay`<sup>Required</sup> <a name="startDay" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.property.startDay"></a>

```java
public java.lang.String getStartDay();
```

- *Type:* java.lang.String

---

##### `startHour`<sup>Required</sup> <a name="startHour" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.property.startHour"></a>

```java
public java.lang.Number getStartHour();
```

- *Type:* java.lang.Number

---

##### `startMin`<sup>Required</sup> <a name="startMin" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.property.startMin"></a>

```java
public java.lang.Number getStartMin();
```

- *Type:* java.lang.Number

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictionsOutputReference.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationRule.NotificationRuleTimeRestrictionRestrictions">NotificationRuleTimeRestrictionRestrictions</a>

---



