# `opsgenie_notification_policy`

Refer to the Terraform Registory for docs: [`opsgenie_notification_policy`](https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy).

# `notificationPolicy` Submodule <a name="`notificationPolicy` Submodule" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### NotificationPolicy <a name="NotificationPolicy" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy"></a>

Represents a {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy opsgenie_notification_policy}.

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicy;

NotificationPolicy.Builder.create(Construct scope, java.lang.String id)
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
    .filter(IResolvable)
    .filter(java.util.List<NotificationPolicyFilter>)
    .name(java.lang.String)
    .teamId(java.lang.String)
//  .autoCloseAction(IResolvable)
//  .autoCloseAction(java.util.List<NotificationPolicyAutoCloseAction>)
//  .autoRestartAction(IResolvable)
//  .autoRestartAction(java.util.List<NotificationPolicyAutoRestartAction>)
//  .deDuplicationAction(IResolvable)
//  .deDuplicationAction(java.util.List<NotificationPolicyDeDuplicationAction>)
//  .delayAction(IResolvable)
//  .delayAction(java.util.List<NotificationPolicyDelayAction>)
//  .enabled(java.lang.Boolean)
//  .enabled(IResolvable)
//  .id(java.lang.String)
//  .policyDescription(java.lang.String)
//  .suppress(java.lang.Boolean)
//  .suppress(IResolvable)
//  .timeRestriction(IResolvable)
//  .timeRestriction(java.util.List<NotificationPolicyTimeRestriction>)
    .build();
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.scope">scope</a></code> | <code>software.constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.id">id</a></code> | <code>java.lang.String</code> | The scoped construct ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.connection">connection</a></code> | <code>com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.count">count</a></code> | <code>java.lang.Number OR com.hashicorp.cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.dependsOn">dependsOn</a></code> | <code>java.util.List<com.hashicorp.cdktf.ITerraformDependable></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.forEach">forEach</a></code> | <code>com.hashicorp.cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.lifecycle">lifecycle</a></code> | <code>com.hashicorp.cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.provider">provider</a></code> | <code>com.hashicorp.cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.provisioners">provisioners</a></code> | <code>java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.filter">filter</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter">NotificationPolicyFilter</a>></code> | filter block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.name">name</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#name NotificationPolicy#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.teamId">teamId</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#team_id NotificationPolicy#team_id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.autoCloseAction">autoCloseAction</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction">NotificationPolicyAutoCloseAction</a>></code> | auto_close_action block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.autoRestartAction">autoRestartAction</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction">NotificationPolicyAutoRestartAction</a>></code> | auto_restart_action block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.deDuplicationAction">deDuplicationAction</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction">NotificationPolicyDeDuplicationAction</a>></code> | de_duplication_action block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.delayAction">delayAction</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction">NotificationPolicyDelayAction</a>></code> | delay_action block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.enabled">enabled</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#enabled NotificationPolicy#enabled}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.id">id</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#id NotificationPolicy#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.policyDescription">policyDescription</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#policy_description NotificationPolicy#policy_description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.suppress">suppress</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#suppress NotificationPolicy#suppress}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.timeRestriction">timeRestriction</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction">NotificationPolicyTimeRestriction</a>></code> | time_restriction block. |

---

##### `scope`<sup>Required</sup> <a name="scope" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.scope"></a>

- *Type:* software.constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.id"></a>

- *Type:* java.lang.String

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.connection"></a>

- *Type:* com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.count"></a>

- *Type:* java.lang.Number OR com.hashicorp.cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.dependsOn"></a>

- *Type:* java.util.List<com.hashicorp.cdktf.ITerraformDependable>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.forEach"></a>

- *Type:* com.hashicorp.cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.lifecycle"></a>

- *Type:* com.hashicorp.cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.provider"></a>

- *Type:* com.hashicorp.cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.provisioners"></a>

- *Type:* java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner>

---

##### `filter`<sup>Required</sup> <a name="filter" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.filter"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter">NotificationPolicyFilter</a>>

filter block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#filter NotificationPolicy#filter}

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.name"></a>

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#name NotificationPolicy#name}.

---

##### `teamId`<sup>Required</sup> <a name="teamId" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.teamId"></a>

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#team_id NotificationPolicy#team_id}.

---

##### `autoCloseAction`<sup>Optional</sup> <a name="autoCloseAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.autoCloseAction"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction">NotificationPolicyAutoCloseAction</a>>

auto_close_action block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#auto_close_action NotificationPolicy#auto_close_action}

---

##### `autoRestartAction`<sup>Optional</sup> <a name="autoRestartAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.autoRestartAction"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction">NotificationPolicyAutoRestartAction</a>>

auto_restart_action block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#auto_restart_action NotificationPolicy#auto_restart_action}

---

##### `deDuplicationAction`<sup>Optional</sup> <a name="deDuplicationAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.deDuplicationAction"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction">NotificationPolicyDeDuplicationAction</a>>

de_duplication_action block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#de_duplication_action NotificationPolicy#de_duplication_action}

---

##### `delayAction`<sup>Optional</sup> <a name="delayAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.delayAction"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction">NotificationPolicyDelayAction</a>>

delay_action block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#delay_action NotificationPolicy#delay_action}

---

##### `enabled`<sup>Optional</sup> <a name="enabled" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.enabled"></a>

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#enabled NotificationPolicy#enabled}.

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.id"></a>

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#id NotificationPolicy#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `policyDescription`<sup>Optional</sup> <a name="policyDescription" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.policyDescription"></a>

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#policy_description NotificationPolicy#policy_description}.

---

##### `suppress`<sup>Optional</sup> <a name="suppress" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.suppress"></a>

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#suppress NotificationPolicy#suppress}.

---

##### `timeRestriction`<sup>Optional</sup> <a name="timeRestriction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.Initializer.parameter.timeRestriction"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction">NotificationPolicyTimeRestriction</a>>

time_restriction block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_restriction NotificationPolicy#time_restriction}

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

```java
public java.lang.String toString()
```

Returns a string representation of this construct.

##### `addOverride` <a name="addOverride" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.addOverride"></a>

```java
public void addOverride(java.lang.String path, java.lang.Object value)
```

###### `path`<sup>Required</sup> <a name="path" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.addOverride.parameter.path"></a>

- *Type:* java.lang.String

---

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.addOverride.parameter.value"></a>

- *Type:* java.lang.Object

---

##### `overrideLogicalId` <a name="overrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.overrideLogicalId"></a>

```java
public void overrideLogicalId(java.lang.String newLogicalId)
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* java.lang.String

The new logical ID to use for this stack element.

---

##### `resetOverrideLogicalId` <a name="resetOverrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetOverrideLogicalId"></a>

```java
public void resetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `toMetadata` <a name="toMetadata" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.toMetadata"></a>

```java
public java.lang.Object toMetadata()
```

##### `toTerraform` <a name="toTerraform" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.toTerraform"></a>

```java
public java.lang.Object toTerraform()
```

Adds this resource to the terraform JSON output.

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `putAutoCloseAction` <a name="putAutoCloseAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putAutoCloseAction"></a>

```java
public void putAutoCloseAction(IResolvable OR java.util.List<NotificationPolicyAutoCloseAction> value)
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putAutoCloseAction.parameter.value"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction">NotificationPolicyAutoCloseAction</a>>

---

##### `putAutoRestartAction` <a name="putAutoRestartAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putAutoRestartAction"></a>

```java
public void putAutoRestartAction(IResolvable OR java.util.List<NotificationPolicyAutoRestartAction> value)
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putAutoRestartAction.parameter.value"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction">NotificationPolicyAutoRestartAction</a>>

---

##### `putDeDuplicationAction` <a name="putDeDuplicationAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putDeDuplicationAction"></a>

```java
public void putDeDuplicationAction(IResolvable OR java.util.List<NotificationPolicyDeDuplicationAction> value)
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putDeDuplicationAction.parameter.value"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction">NotificationPolicyDeDuplicationAction</a>>

---

##### `putDelayAction` <a name="putDelayAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putDelayAction"></a>

```java
public void putDelayAction(IResolvable OR java.util.List<NotificationPolicyDelayAction> value)
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putDelayAction.parameter.value"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction">NotificationPolicyDelayAction</a>>

---

##### `putFilter` <a name="putFilter" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putFilter"></a>

```java
public void putFilter(IResolvable OR java.util.List<NotificationPolicyFilter> value)
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putFilter.parameter.value"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter">NotificationPolicyFilter</a>>

---

##### `putTimeRestriction` <a name="putTimeRestriction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putTimeRestriction"></a>

```java
public void putTimeRestriction(IResolvable OR java.util.List<NotificationPolicyTimeRestriction> value)
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.putTimeRestriction.parameter.value"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction">NotificationPolicyTimeRestriction</a>>

---

##### `resetAutoCloseAction` <a name="resetAutoCloseAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetAutoCloseAction"></a>

```java
public void resetAutoCloseAction()
```

##### `resetAutoRestartAction` <a name="resetAutoRestartAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetAutoRestartAction"></a>

```java
public void resetAutoRestartAction()
```

##### `resetDeDuplicationAction` <a name="resetDeDuplicationAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetDeDuplicationAction"></a>

```java
public void resetDeDuplicationAction()
```

##### `resetDelayAction` <a name="resetDelayAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetDelayAction"></a>

```java
public void resetDelayAction()
```

##### `resetEnabled` <a name="resetEnabled" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetEnabled"></a>

```java
public void resetEnabled()
```

##### `resetId` <a name="resetId" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetId"></a>

```java
public void resetId()
```

##### `resetPolicyDescription` <a name="resetPolicyDescription" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetPolicyDescription"></a>

```java
public void resetPolicyDescription()
```

##### `resetSuppress` <a name="resetSuppress" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetSuppress"></a>

```java
public void resetSuppress()
```

##### `resetTimeRestriction` <a name="resetTimeRestriction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.resetTimeRestriction"></a>

```java
public void resetTimeRestriction()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.isConstruct">isConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.isTerraformElement">isTerraformElement</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.isTerraformResource">isTerraformResource</a></code> | *No description.* |

---

##### `isConstruct` <a name="isConstruct" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.isConstruct"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicy;

NotificationPolicy.isConstruct(java.lang.Object x)
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

- *Type:* java.lang.Object

Any object.

---

##### `isTerraformElement` <a name="isTerraformElement" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.isTerraformElement"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicy;

NotificationPolicy.isTerraformElement(java.lang.Object x)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.isTerraformElement.parameter.x"></a>

- *Type:* java.lang.Object

---

##### `isTerraformResource` <a name="isTerraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.isTerraformResource"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicy;

NotificationPolicy.isTerraformResource(java.lang.Object x)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.isTerraformResource.parameter.x"></a>

- *Type:* java.lang.Object

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.node">node</a></code> | <code>software.constructs.Node</code> | The tree node. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.cdktfStack">cdktfStack</a></code> | <code>com.hashicorp.cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.friendlyUniqueId">friendlyUniqueId</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.terraformMetaArguments">terraformMetaArguments</a></code> | <code>java.util.Map<java.lang.String, java.lang.Object></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.terraformResourceType">terraformResourceType</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.terraformGeneratorMetadata">terraformGeneratorMetadata</a></code> | <code>com.hashicorp.cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.connection">connection</a></code> | <code>com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.count">count</a></code> | <code>java.lang.Number OR com.hashicorp.cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.dependsOn">dependsOn</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.forEach">forEach</a></code> | <code>com.hashicorp.cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.lifecycle">lifecycle</a></code> | <code>com.hashicorp.cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.provider">provider</a></code> | <code>com.hashicorp.cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.provisioners">provisioners</a></code> | <code>java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.autoCloseAction">autoCloseAction</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList">NotificationPolicyAutoCloseActionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.autoRestartAction">autoRestartAction</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList">NotificationPolicyAutoRestartActionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.deDuplicationAction">deDuplicationAction</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList">NotificationPolicyDeDuplicationActionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.delayAction">delayAction</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList">NotificationPolicyDelayActionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.filter">filter</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList">NotificationPolicyFilterList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.timeRestriction">timeRestriction</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList">NotificationPolicyTimeRestrictionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.autoCloseActionInput">autoCloseActionInput</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction">NotificationPolicyAutoCloseAction</a>></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.autoRestartActionInput">autoRestartActionInput</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction">NotificationPolicyAutoRestartAction</a>></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.deDuplicationActionInput">deDuplicationActionInput</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction">NotificationPolicyDeDuplicationAction</a>></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.delayActionInput">delayActionInput</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction">NotificationPolicyDelayAction</a>></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.enabledInput">enabledInput</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.filterInput">filterInput</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter">NotificationPolicyFilter</a>></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.idInput">idInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.nameInput">nameInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.policyDescriptionInput">policyDescriptionInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.suppressInput">suppressInput</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.teamIdInput">teamIdInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.timeRestrictionInput">timeRestrictionInput</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction">NotificationPolicyTimeRestriction</a>></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.enabled">enabled</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.id">id</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.name">name</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.policyDescription">policyDescription</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.suppress">suppress</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.teamId">teamId</a></code> | <code>java.lang.String</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.node"></a>

```java
public Node getNode();
```

- *Type:* software.constructs.Node

The tree node.

---

##### `cdktfStack`<sup>Required</sup> <a name="cdktfStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.cdktfStack"></a>

```java
public TerraformStack getCdktfStack();
```

- *Type:* com.hashicorp.cdktf.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `friendlyUniqueId`<sup>Required</sup> <a name="friendlyUniqueId" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.friendlyUniqueId"></a>

```java
public java.lang.String getFriendlyUniqueId();
```

- *Type:* java.lang.String

---

##### `terraformMetaArguments`<sup>Required</sup> <a name="terraformMetaArguments" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.terraformMetaArguments"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getTerraformMetaArguments();
```

- *Type:* java.util.Map<java.lang.String, java.lang.Object>

---

##### `terraformResourceType`<sup>Required</sup> <a name="terraformResourceType" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.terraformResourceType"></a>

```java
public java.lang.String getTerraformResourceType();
```

- *Type:* java.lang.String

---

##### `terraformGeneratorMetadata`<sup>Optional</sup> <a name="terraformGeneratorMetadata" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.terraformGeneratorMetadata"></a>

```java
public TerraformProviderGeneratorMetadata getTerraformGeneratorMetadata();
```

- *Type:* com.hashicorp.cdktf.TerraformProviderGeneratorMetadata

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.connection"></a>

```java
public java.lang.Object getConnection();
```

- *Type:* com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.count"></a>

```java
public java.lang.Object getCount();
```

- *Type:* java.lang.Number OR com.hashicorp.cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.dependsOn"></a>

```java
public java.util.List<java.lang.String> getDependsOn();
```

- *Type:* java.util.List<java.lang.String>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.forEach"></a>

```java
public ITerraformIterator getForEach();
```

- *Type:* com.hashicorp.cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.lifecycle"></a>

```java
public TerraformResourceLifecycle getLifecycle();
```

- *Type:* com.hashicorp.cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.provider"></a>

```java
public TerraformProvider getProvider();
```

- *Type:* com.hashicorp.cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.provisioners"></a>

```java
public java.lang.Object getProvisioners();
```

- *Type:* java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner>

---

##### `autoCloseAction`<sup>Required</sup> <a name="autoCloseAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.autoCloseAction"></a>

```java
public NotificationPolicyAutoCloseActionList getAutoCloseAction();
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList">NotificationPolicyAutoCloseActionList</a>

---

##### `autoRestartAction`<sup>Required</sup> <a name="autoRestartAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.autoRestartAction"></a>

```java
public NotificationPolicyAutoRestartActionList getAutoRestartAction();
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList">NotificationPolicyAutoRestartActionList</a>

---

##### `deDuplicationAction`<sup>Required</sup> <a name="deDuplicationAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.deDuplicationAction"></a>

```java
public NotificationPolicyDeDuplicationActionList getDeDuplicationAction();
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList">NotificationPolicyDeDuplicationActionList</a>

---

##### `delayAction`<sup>Required</sup> <a name="delayAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.delayAction"></a>

```java
public NotificationPolicyDelayActionList getDelayAction();
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList">NotificationPolicyDelayActionList</a>

---

##### `filter`<sup>Required</sup> <a name="filter" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.filter"></a>

```java
public NotificationPolicyFilterList getFilter();
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList">NotificationPolicyFilterList</a>

---

##### `timeRestriction`<sup>Required</sup> <a name="timeRestriction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.timeRestriction"></a>

```java
public NotificationPolicyTimeRestrictionList getTimeRestriction();
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList">NotificationPolicyTimeRestrictionList</a>

---

##### `autoCloseActionInput`<sup>Optional</sup> <a name="autoCloseActionInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.autoCloseActionInput"></a>

```java
public java.lang.Object getAutoCloseActionInput();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction">NotificationPolicyAutoCloseAction</a>>

---

##### `autoRestartActionInput`<sup>Optional</sup> <a name="autoRestartActionInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.autoRestartActionInput"></a>

```java
public java.lang.Object getAutoRestartActionInput();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction">NotificationPolicyAutoRestartAction</a>>

---

##### `deDuplicationActionInput`<sup>Optional</sup> <a name="deDuplicationActionInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.deDuplicationActionInput"></a>

```java
public java.lang.Object getDeDuplicationActionInput();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction">NotificationPolicyDeDuplicationAction</a>>

---

##### `delayActionInput`<sup>Optional</sup> <a name="delayActionInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.delayActionInput"></a>

```java
public java.lang.Object getDelayActionInput();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction">NotificationPolicyDelayAction</a>>

---

##### `enabledInput`<sup>Optional</sup> <a name="enabledInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.enabledInput"></a>

```java
public java.lang.Object getEnabledInput();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

---

##### `filterInput`<sup>Optional</sup> <a name="filterInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.filterInput"></a>

```java
public java.lang.Object getFilterInput();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter">NotificationPolicyFilter</a>>

---

##### `idInput`<sup>Optional</sup> <a name="idInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.idInput"></a>

```java
public java.lang.String getIdInput();
```

- *Type:* java.lang.String

---

##### `nameInput`<sup>Optional</sup> <a name="nameInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.nameInput"></a>

```java
public java.lang.String getNameInput();
```

- *Type:* java.lang.String

---

##### `policyDescriptionInput`<sup>Optional</sup> <a name="policyDescriptionInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.policyDescriptionInput"></a>

```java
public java.lang.String getPolicyDescriptionInput();
```

- *Type:* java.lang.String

---

##### `suppressInput`<sup>Optional</sup> <a name="suppressInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.suppressInput"></a>

```java
public java.lang.Object getSuppressInput();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

---

##### `teamIdInput`<sup>Optional</sup> <a name="teamIdInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.teamIdInput"></a>

```java
public java.lang.String getTeamIdInput();
```

- *Type:* java.lang.String

---

##### `timeRestrictionInput`<sup>Optional</sup> <a name="timeRestrictionInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.timeRestrictionInput"></a>

```java
public java.lang.Object getTimeRestrictionInput();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction">NotificationPolicyTimeRestriction</a>>

---

##### `enabled`<sup>Required</sup> <a name="enabled" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.enabled"></a>

```java
public java.lang.Object getEnabled();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.id"></a>

```java
public java.lang.String getId();
```

- *Type:* java.lang.String

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.name"></a>

```java
public java.lang.String getName();
```

- *Type:* java.lang.String

---

##### `policyDescription`<sup>Required</sup> <a name="policyDescription" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.policyDescription"></a>

```java
public java.lang.String getPolicyDescription();
```

- *Type:* java.lang.String

---

##### `suppress`<sup>Required</sup> <a name="suppress" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.suppress"></a>

```java
public java.lang.Object getSuppress();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

---

##### `teamId`<sup>Required</sup> <a name="teamId" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.teamId"></a>

```java
public java.lang.String getTeamId();
```

- *Type:* java.lang.String

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.tfResourceType">tfResourceType</a></code> | <code>java.lang.String</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicy.property.tfResourceType"></a>

```java
public java.lang.String getTfResourceType();
```

- *Type:* java.lang.String

---

## Structs <a name="Structs" id="Structs"></a>

### NotificationPolicyAutoCloseAction <a name="NotificationPolicyAutoCloseAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyAutoCloseAction;

NotificationPolicyAutoCloseAction.builder()
    .duration(IResolvable)
    .duration(java.util.List<NotificationPolicyAutoCloseActionDuration>)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction.property.duration">duration</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration">NotificationPolicyAutoCloseActionDuration</a>></code> | duration block. |

---

##### `duration`<sup>Required</sup> <a name="duration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction.property.duration"></a>

```java
public java.lang.Object getDuration();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration">NotificationPolicyAutoCloseActionDuration</a>>

duration block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#duration NotificationPolicy#duration}

---

### NotificationPolicyAutoCloseActionDuration <a name="NotificationPolicyAutoCloseActionDuration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyAutoCloseActionDuration;

NotificationPolicyAutoCloseActionDuration.builder()
    .timeAmount(java.lang.Number)
//  .timeUnit(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration.property.timeAmount">timeAmount</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_amount NotificationPolicy#time_amount}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration.property.timeUnit">timeUnit</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_unit NotificationPolicy#time_unit}. |

---

##### `timeAmount`<sup>Required</sup> <a name="timeAmount" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration.property.timeAmount"></a>

```java
public java.lang.Number getTimeAmount();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_amount NotificationPolicy#time_amount}.

---

##### `timeUnit`<sup>Optional</sup> <a name="timeUnit" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration.property.timeUnit"></a>

```java
public java.lang.String getTimeUnit();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_unit NotificationPolicy#time_unit}.

---

### NotificationPolicyAutoRestartAction <a name="NotificationPolicyAutoRestartAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyAutoRestartAction;

NotificationPolicyAutoRestartAction.builder()
    .duration(IResolvable)
    .duration(java.util.List<NotificationPolicyAutoRestartActionDuration>)
    .maxRepeatCount(java.lang.Number)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction.property.duration">duration</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration">NotificationPolicyAutoRestartActionDuration</a>></code> | duration block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction.property.maxRepeatCount">maxRepeatCount</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#max_repeat_count NotificationPolicy#max_repeat_count}. |

---

##### `duration`<sup>Required</sup> <a name="duration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction.property.duration"></a>

```java
public java.lang.Object getDuration();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration">NotificationPolicyAutoRestartActionDuration</a>>

duration block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#duration NotificationPolicy#duration}

---

##### `maxRepeatCount`<sup>Required</sup> <a name="maxRepeatCount" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction.property.maxRepeatCount"></a>

```java
public java.lang.Number getMaxRepeatCount();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#max_repeat_count NotificationPolicy#max_repeat_count}.

---

### NotificationPolicyAutoRestartActionDuration <a name="NotificationPolicyAutoRestartActionDuration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyAutoRestartActionDuration;

NotificationPolicyAutoRestartActionDuration.builder()
    .timeAmount(java.lang.Number)
//  .timeUnit(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration.property.timeAmount">timeAmount</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_amount NotificationPolicy#time_amount}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration.property.timeUnit">timeUnit</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_unit NotificationPolicy#time_unit}. |

---

##### `timeAmount`<sup>Required</sup> <a name="timeAmount" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration.property.timeAmount"></a>

```java
public java.lang.Number getTimeAmount();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_amount NotificationPolicy#time_amount}.

---

##### `timeUnit`<sup>Optional</sup> <a name="timeUnit" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration.property.timeUnit"></a>

```java
public java.lang.String getTimeUnit();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_unit NotificationPolicy#time_unit}.

---

### NotificationPolicyConfig <a name="NotificationPolicyConfig" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyConfig;

NotificationPolicyConfig.builder()
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
    .filter(IResolvable)
    .filter(java.util.List<NotificationPolicyFilter>)
    .name(java.lang.String)
    .teamId(java.lang.String)
//  .autoCloseAction(IResolvable)
//  .autoCloseAction(java.util.List<NotificationPolicyAutoCloseAction>)
//  .autoRestartAction(IResolvable)
//  .autoRestartAction(java.util.List<NotificationPolicyAutoRestartAction>)
//  .deDuplicationAction(IResolvable)
//  .deDuplicationAction(java.util.List<NotificationPolicyDeDuplicationAction>)
//  .delayAction(IResolvable)
//  .delayAction(java.util.List<NotificationPolicyDelayAction>)
//  .enabled(java.lang.Boolean)
//  .enabled(IResolvable)
//  .id(java.lang.String)
//  .policyDescription(java.lang.String)
//  .suppress(java.lang.Boolean)
//  .suppress(IResolvable)
//  .timeRestriction(IResolvable)
//  .timeRestriction(java.util.List<NotificationPolicyTimeRestriction>)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.connection">connection</a></code> | <code>com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.count">count</a></code> | <code>java.lang.Number OR com.hashicorp.cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.dependsOn">dependsOn</a></code> | <code>java.util.List<com.hashicorp.cdktf.ITerraformDependable></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.forEach">forEach</a></code> | <code>com.hashicorp.cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.lifecycle">lifecycle</a></code> | <code>com.hashicorp.cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.provider">provider</a></code> | <code>com.hashicorp.cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.provisioners">provisioners</a></code> | <code>java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.filter">filter</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter">NotificationPolicyFilter</a>></code> | filter block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.name">name</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#name NotificationPolicy#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.teamId">teamId</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#team_id NotificationPolicy#team_id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.autoCloseAction">autoCloseAction</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction">NotificationPolicyAutoCloseAction</a>></code> | auto_close_action block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.autoRestartAction">autoRestartAction</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction">NotificationPolicyAutoRestartAction</a>></code> | auto_restart_action block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.deDuplicationAction">deDuplicationAction</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction">NotificationPolicyDeDuplicationAction</a>></code> | de_duplication_action block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.delayAction">delayAction</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction">NotificationPolicyDelayAction</a>></code> | delay_action block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.enabled">enabled</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#enabled NotificationPolicy#enabled}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.id">id</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#id NotificationPolicy#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.policyDescription">policyDescription</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#policy_description NotificationPolicy#policy_description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.suppress">suppress</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#suppress NotificationPolicy#suppress}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.timeRestriction">timeRestriction</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction">NotificationPolicyTimeRestriction</a>></code> | time_restriction block. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.connection"></a>

```java
public java.lang.Object getConnection();
```

- *Type:* com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.count"></a>

```java
public java.lang.Object getCount();
```

- *Type:* java.lang.Number OR com.hashicorp.cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.dependsOn"></a>

```java
public java.util.List<ITerraformDependable> getDependsOn();
```

- *Type:* java.util.List<com.hashicorp.cdktf.ITerraformDependable>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.forEach"></a>

```java
public ITerraformIterator getForEach();
```

- *Type:* com.hashicorp.cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.lifecycle"></a>

```java
public TerraformResourceLifecycle getLifecycle();
```

- *Type:* com.hashicorp.cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.provider"></a>

```java
public TerraformProvider getProvider();
```

- *Type:* com.hashicorp.cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.provisioners"></a>

```java
public java.lang.Object getProvisioners();
```

- *Type:* java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner>

---

##### `filter`<sup>Required</sup> <a name="filter" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.filter"></a>

```java
public java.lang.Object getFilter();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter">NotificationPolicyFilter</a>>

filter block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#filter NotificationPolicy#filter}

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.name"></a>

```java
public java.lang.String getName();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#name NotificationPolicy#name}.

---

##### `teamId`<sup>Required</sup> <a name="teamId" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.teamId"></a>

```java
public java.lang.String getTeamId();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#team_id NotificationPolicy#team_id}.

---

##### `autoCloseAction`<sup>Optional</sup> <a name="autoCloseAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.autoCloseAction"></a>

```java
public java.lang.Object getAutoCloseAction();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction">NotificationPolicyAutoCloseAction</a>>

auto_close_action block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#auto_close_action NotificationPolicy#auto_close_action}

---

##### `autoRestartAction`<sup>Optional</sup> <a name="autoRestartAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.autoRestartAction"></a>

```java
public java.lang.Object getAutoRestartAction();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction">NotificationPolicyAutoRestartAction</a>>

auto_restart_action block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#auto_restart_action NotificationPolicy#auto_restart_action}

---

##### `deDuplicationAction`<sup>Optional</sup> <a name="deDuplicationAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.deDuplicationAction"></a>

```java
public java.lang.Object getDeDuplicationAction();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction">NotificationPolicyDeDuplicationAction</a>>

de_duplication_action block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#de_duplication_action NotificationPolicy#de_duplication_action}

---

##### `delayAction`<sup>Optional</sup> <a name="delayAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.delayAction"></a>

```java
public java.lang.Object getDelayAction();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction">NotificationPolicyDelayAction</a>>

delay_action block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#delay_action NotificationPolicy#delay_action}

---

##### `enabled`<sup>Optional</sup> <a name="enabled" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.enabled"></a>

```java
public java.lang.Object getEnabled();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#enabled NotificationPolicy#enabled}.

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.id"></a>

```java
public java.lang.String getId();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#id NotificationPolicy#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `policyDescription`<sup>Optional</sup> <a name="policyDescription" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.policyDescription"></a>

```java
public java.lang.String getPolicyDescription();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#policy_description NotificationPolicy#policy_description}.

---

##### `suppress`<sup>Optional</sup> <a name="suppress" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.suppress"></a>

```java
public java.lang.Object getSuppress();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#suppress NotificationPolicy#suppress}.

---

##### `timeRestriction`<sup>Optional</sup> <a name="timeRestriction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyConfig.property.timeRestriction"></a>

```java
public java.lang.Object getTimeRestriction();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction">NotificationPolicyTimeRestriction</a>>

time_restriction block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_restriction NotificationPolicy#time_restriction}

---

### NotificationPolicyDeDuplicationAction <a name="NotificationPolicyDeDuplicationAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyDeDuplicationAction;

NotificationPolicyDeDuplicationAction.builder()
    .count(java.lang.Number)
    .deDuplicationActionType(java.lang.String)
//  .duration(IResolvable)
//  .duration(java.util.List<NotificationPolicyDeDuplicationActionDuration>)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction.property.count">count</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#count NotificationPolicy#count}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction.property.deDuplicationActionType">deDuplicationActionType</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#de_duplication_action_type NotificationPolicy#de_duplication_action_type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction.property.duration">duration</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration">NotificationPolicyDeDuplicationActionDuration</a>></code> | duration block. |

---

##### `count`<sup>Required</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction.property.count"></a>

```java
public java.lang.Number getCount();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#count NotificationPolicy#count}.

---

##### `deDuplicationActionType`<sup>Required</sup> <a name="deDuplicationActionType" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction.property.deDuplicationActionType"></a>

```java
public java.lang.String getDeDuplicationActionType();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#de_duplication_action_type NotificationPolicy#de_duplication_action_type}.

---

##### `duration`<sup>Optional</sup> <a name="duration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction.property.duration"></a>

```java
public java.lang.Object getDuration();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration">NotificationPolicyDeDuplicationActionDuration</a>>

duration block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#duration NotificationPolicy#duration}

---

### NotificationPolicyDeDuplicationActionDuration <a name="NotificationPolicyDeDuplicationActionDuration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyDeDuplicationActionDuration;

NotificationPolicyDeDuplicationActionDuration.builder()
    .timeAmount(java.lang.Number)
//  .timeUnit(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration.property.timeAmount">timeAmount</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_amount NotificationPolicy#time_amount}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration.property.timeUnit">timeUnit</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_unit NotificationPolicy#time_unit}. |

---

##### `timeAmount`<sup>Required</sup> <a name="timeAmount" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration.property.timeAmount"></a>

```java
public java.lang.Number getTimeAmount();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_amount NotificationPolicy#time_amount}.

---

##### `timeUnit`<sup>Optional</sup> <a name="timeUnit" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration.property.timeUnit"></a>

```java
public java.lang.String getTimeUnit();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_unit NotificationPolicy#time_unit}.

---

### NotificationPolicyDelayAction <a name="NotificationPolicyDelayAction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyDelayAction;

NotificationPolicyDelayAction.builder()
    .delayOption(java.lang.String)
//  .duration(IResolvable)
//  .duration(java.util.List<NotificationPolicyDelayActionDuration>)
//  .untilHour(java.lang.Number)
//  .untilMinute(java.lang.Number)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction.property.delayOption">delayOption</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#delay_option NotificationPolicy#delay_option}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction.property.duration">duration</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration">NotificationPolicyDelayActionDuration</a>></code> | duration block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction.property.untilHour">untilHour</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#until_hour NotificationPolicy#until_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction.property.untilMinute">untilMinute</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#until_minute NotificationPolicy#until_minute}. |

---

##### `delayOption`<sup>Required</sup> <a name="delayOption" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction.property.delayOption"></a>

```java
public java.lang.String getDelayOption();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#delay_option NotificationPolicy#delay_option}.

---

##### `duration`<sup>Optional</sup> <a name="duration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction.property.duration"></a>

```java
public java.lang.Object getDuration();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration">NotificationPolicyDelayActionDuration</a>>

duration block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#duration NotificationPolicy#duration}

---

##### `untilHour`<sup>Optional</sup> <a name="untilHour" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction.property.untilHour"></a>

```java
public java.lang.Number getUntilHour();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#until_hour NotificationPolicy#until_hour}.

---

##### `untilMinute`<sup>Optional</sup> <a name="untilMinute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction.property.untilMinute"></a>

```java
public java.lang.Number getUntilMinute();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#until_minute NotificationPolicy#until_minute}.

---

### NotificationPolicyDelayActionDuration <a name="NotificationPolicyDelayActionDuration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyDelayActionDuration;

NotificationPolicyDelayActionDuration.builder()
    .timeAmount(java.lang.Number)
//  .timeUnit(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration.property.timeAmount">timeAmount</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_amount NotificationPolicy#time_amount}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration.property.timeUnit">timeUnit</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_unit NotificationPolicy#time_unit}. |

---

##### `timeAmount`<sup>Required</sup> <a name="timeAmount" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration.property.timeAmount"></a>

```java
public java.lang.Number getTimeAmount();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_amount NotificationPolicy#time_amount}.

---

##### `timeUnit`<sup>Optional</sup> <a name="timeUnit" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration.property.timeUnit"></a>

```java
public java.lang.String getTimeUnit();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#time_unit NotificationPolicy#time_unit}.

---

### NotificationPolicyFilter <a name="NotificationPolicyFilter" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyFilter;

NotificationPolicyFilter.builder()
//  .conditions(IResolvable)
//  .conditions(java.util.List<NotificationPolicyFilterConditions>)
//  .type(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter.property.conditions">conditions</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions">NotificationPolicyFilterConditions</a>></code> | conditions block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter.property.type">type</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#type NotificationPolicy#type}. |

---

##### `conditions`<sup>Optional</sup> <a name="conditions" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter.property.conditions"></a>

```java
public java.lang.Object getConditions();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions">NotificationPolicyFilterConditions</a>>

conditions block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#conditions NotificationPolicy#conditions}

---

##### `type`<sup>Optional</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter.property.type"></a>

```java
public java.lang.String getType();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#type NotificationPolicy#type}.

---

### NotificationPolicyFilterConditions <a name="NotificationPolicyFilterConditions" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyFilterConditions;

NotificationPolicyFilterConditions.builder()
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
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.property.field">field</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#field NotificationPolicy#field}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.property.operation">operation</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#operation NotificationPolicy#operation}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.property.expectedValue">expectedValue</a></code> | <code>java.lang.String</code> | User defined value that will be compared with alert field according to the operation. Default value is empty string. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.property.key">key</a></code> | <code>java.lang.String</code> | If 'field' is set as 'extra-properties', key could be used for key-value pair. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.property.not">not</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | Indicates behaviour of the given operation. Default value is false. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.property.order">order</a></code> | <code>java.lang.Number</code> | Order of the condition in conditions list. |

---

##### `field`<sup>Required</sup> <a name="field" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.property.field"></a>

```java
public java.lang.String getField();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#field NotificationPolicy#field}.

---

##### `operation`<sup>Required</sup> <a name="operation" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.property.operation"></a>

```java
public java.lang.String getOperation();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#operation NotificationPolicy#operation}.

---

##### `expectedValue`<sup>Optional</sup> <a name="expectedValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.property.expectedValue"></a>

```java
public java.lang.String getExpectedValue();
```

- *Type:* java.lang.String

User defined value that will be compared with alert field according to the operation. Default value is empty string.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#expected_value NotificationPolicy#expected_value}

---

##### `key`<sup>Optional</sup> <a name="key" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.property.key"></a>

```java
public java.lang.String getKey();
```

- *Type:* java.lang.String

If 'field' is set as 'extra-properties', key could be used for key-value pair.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#key NotificationPolicy#key}

---

##### `not`<sup>Optional</sup> <a name="not" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.property.not"></a>

```java
public java.lang.Object getNot();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

Indicates behaviour of the given operation. Default value is false.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#not NotificationPolicy#not}

---

##### `order`<sup>Optional</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions.property.order"></a>

```java
public java.lang.Number getOrder();
```

- *Type:* java.lang.Number

Order of the condition in conditions list.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#order NotificationPolicy#order}

---

### NotificationPolicyTimeRestriction <a name="NotificationPolicyTimeRestriction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyTimeRestriction;

NotificationPolicyTimeRestriction.builder()
    .type(java.lang.String)
//  .restriction(IResolvable)
//  .restriction(java.util.List<NotificationPolicyTimeRestrictionRestriction>)
//  .restrictions(IResolvable)
//  .restrictions(java.util.List<NotificationPolicyTimeRestrictionRestrictions>)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction.property.type">type</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#type NotificationPolicy#type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction.property.restriction">restriction</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction">NotificationPolicyTimeRestrictionRestriction</a>></code> | restriction block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction.property.restrictions">restrictions</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions">NotificationPolicyTimeRestrictionRestrictions</a>></code> | restrictions block. |

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction.property.type"></a>

```java
public java.lang.String getType();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#type NotificationPolicy#type}.

---

##### `restriction`<sup>Optional</sup> <a name="restriction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction.property.restriction"></a>

```java
public java.lang.Object getRestriction();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction">NotificationPolicyTimeRestrictionRestriction</a>>

restriction block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#restriction NotificationPolicy#restriction}

---

##### `restrictions`<sup>Optional</sup> <a name="restrictions" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction.property.restrictions"></a>

```java
public java.lang.Object getRestrictions();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions">NotificationPolicyTimeRestrictionRestrictions</a>>

restrictions block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#restrictions NotificationPolicy#restrictions}

---

### NotificationPolicyTimeRestrictionRestriction <a name="NotificationPolicyTimeRestrictionRestriction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyTimeRestrictionRestriction;

NotificationPolicyTimeRestrictionRestriction.builder()
    .endHour(java.lang.Number)
    .endMin(java.lang.Number)
    .startHour(java.lang.Number)
    .startMin(java.lang.Number)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction.property.endHour">endHour</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#end_hour NotificationPolicy#end_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction.property.endMin">endMin</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#end_min NotificationPolicy#end_min}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction.property.startHour">startHour</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#start_hour NotificationPolicy#start_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction.property.startMin">startMin</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#start_min NotificationPolicy#start_min}. |

---

##### `endHour`<sup>Required</sup> <a name="endHour" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction.property.endHour"></a>

```java
public java.lang.Number getEndHour();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#end_hour NotificationPolicy#end_hour}.

---

##### `endMin`<sup>Required</sup> <a name="endMin" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction.property.endMin"></a>

```java
public java.lang.Number getEndMin();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#end_min NotificationPolicy#end_min}.

---

##### `startHour`<sup>Required</sup> <a name="startHour" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction.property.startHour"></a>

```java
public java.lang.Number getStartHour();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#start_hour NotificationPolicy#start_hour}.

---

##### `startMin`<sup>Required</sup> <a name="startMin" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction.property.startMin"></a>

```java
public java.lang.Number getStartMin();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#start_min NotificationPolicy#start_min}.

---

### NotificationPolicyTimeRestrictionRestrictions <a name="NotificationPolicyTimeRestrictionRestrictions" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyTimeRestrictionRestrictions;

NotificationPolicyTimeRestrictionRestrictions.builder()
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
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.property.endDay">endDay</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#end_day NotificationPolicy#end_day}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.property.endHour">endHour</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#end_hour NotificationPolicy#end_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.property.endMin">endMin</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#end_min NotificationPolicy#end_min}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.property.startDay">startDay</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#start_day NotificationPolicy#start_day}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.property.startHour">startHour</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#start_hour NotificationPolicy#start_hour}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.property.startMin">startMin</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#start_min NotificationPolicy#start_min}. |

---

##### `endDay`<sup>Required</sup> <a name="endDay" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.property.endDay"></a>

```java
public java.lang.String getEndDay();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#end_day NotificationPolicy#end_day}.

---

##### `endHour`<sup>Required</sup> <a name="endHour" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.property.endHour"></a>

```java
public java.lang.Number getEndHour();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#end_hour NotificationPolicy#end_hour}.

---

##### `endMin`<sup>Required</sup> <a name="endMin" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.property.endMin"></a>

```java
public java.lang.Number getEndMin();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#end_min NotificationPolicy#end_min}.

---

##### `startDay`<sup>Required</sup> <a name="startDay" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.property.startDay"></a>

```java
public java.lang.String getStartDay();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#start_day NotificationPolicy#start_day}.

---

##### `startHour`<sup>Required</sup> <a name="startHour" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.property.startHour"></a>

```java
public java.lang.Number getStartHour();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#start_hour NotificationPolicy#start_hour}.

---

##### `startMin`<sup>Required</sup> <a name="startMin" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions.property.startMin"></a>

```java
public java.lang.Number getStartMin();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/notification_policy#start_min NotificationPolicy#start_min}.

---

## Classes <a name="Classes" id="Classes"></a>

### NotificationPolicyAutoCloseActionDurationList <a name="NotificationPolicyAutoCloseActionDurationList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyAutoCloseActionDurationList;

new NotificationPolicyAutoCloseActionDurationList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.get"></a>

```java
public NotificationPolicyAutoCloseActionDurationOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration">NotificationPolicyAutoCloseActionDuration</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration">NotificationPolicyAutoCloseActionDuration</a>>

---


### NotificationPolicyAutoCloseActionDurationOutputReference <a name="NotificationPolicyAutoCloseActionDurationOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyAutoCloseActionDurationOutputReference;

new NotificationPolicyAutoCloseActionDurationOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetTimeUnit` <a name="resetTimeUnit" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.resetTimeUnit"></a>

```java
public void resetTimeUnit()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.timeAmountInput">timeAmountInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.timeUnitInput">timeUnitInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.timeAmount">timeAmount</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.timeUnit">timeUnit</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration">NotificationPolicyAutoCloseActionDuration</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `timeAmountInput`<sup>Optional</sup> <a name="timeAmountInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.timeAmountInput"></a>

```java
public java.lang.Number getTimeAmountInput();
```

- *Type:* java.lang.Number

---

##### `timeUnitInput`<sup>Optional</sup> <a name="timeUnitInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.timeUnitInput"></a>

```java
public java.lang.String getTimeUnitInput();
```

- *Type:* java.lang.String

---

##### `timeAmount`<sup>Required</sup> <a name="timeAmount" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.timeAmount"></a>

```java
public java.lang.Number getTimeAmount();
```

- *Type:* java.lang.Number

---

##### `timeUnit`<sup>Required</sup> <a name="timeUnit" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.timeUnit"></a>

```java
public java.lang.String getTimeUnit();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationOutputReference.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration">NotificationPolicyAutoCloseActionDuration</a>

---


### NotificationPolicyAutoCloseActionList <a name="NotificationPolicyAutoCloseActionList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyAutoCloseActionList;

new NotificationPolicyAutoCloseActionList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.get"></a>

```java
public NotificationPolicyAutoCloseActionOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction">NotificationPolicyAutoCloseAction</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionList.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction">NotificationPolicyAutoCloseAction</a>>

---


### NotificationPolicyAutoCloseActionOutputReference <a name="NotificationPolicyAutoCloseActionOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyAutoCloseActionOutputReference;

new NotificationPolicyAutoCloseActionOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `putDuration` <a name="putDuration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.putDuration"></a>

```java
public void putDuration(IResolvable OR java.util.List<NotificationPolicyAutoCloseActionDuration> value)
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.putDuration.parameter.value"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration">NotificationPolicyAutoCloseActionDuration</a>>

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.property.duration">duration</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList">NotificationPolicyAutoCloseActionDurationList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.property.durationInput">durationInput</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration">NotificationPolicyAutoCloseActionDuration</a>></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction">NotificationPolicyAutoCloseAction</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `duration`<sup>Required</sup> <a name="duration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.property.duration"></a>

```java
public NotificationPolicyAutoCloseActionDurationList getDuration();
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDurationList">NotificationPolicyAutoCloseActionDurationList</a>

---

##### `durationInput`<sup>Optional</sup> <a name="durationInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.property.durationInput"></a>

```java
public java.lang.Object getDurationInput();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionDuration">NotificationPolicyAutoCloseActionDuration</a>>

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseActionOutputReference.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoCloseAction">NotificationPolicyAutoCloseAction</a>

---


### NotificationPolicyAutoRestartActionDurationList <a name="NotificationPolicyAutoRestartActionDurationList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyAutoRestartActionDurationList;

new NotificationPolicyAutoRestartActionDurationList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.get"></a>

```java
public NotificationPolicyAutoRestartActionDurationOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration">NotificationPolicyAutoRestartActionDuration</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration">NotificationPolicyAutoRestartActionDuration</a>>

---


### NotificationPolicyAutoRestartActionDurationOutputReference <a name="NotificationPolicyAutoRestartActionDurationOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyAutoRestartActionDurationOutputReference;

new NotificationPolicyAutoRestartActionDurationOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetTimeUnit` <a name="resetTimeUnit" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.resetTimeUnit"></a>

```java
public void resetTimeUnit()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.timeAmountInput">timeAmountInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.timeUnitInput">timeUnitInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.timeAmount">timeAmount</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.timeUnit">timeUnit</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration">NotificationPolicyAutoRestartActionDuration</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `timeAmountInput`<sup>Optional</sup> <a name="timeAmountInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.timeAmountInput"></a>

```java
public java.lang.Number getTimeAmountInput();
```

- *Type:* java.lang.Number

---

##### `timeUnitInput`<sup>Optional</sup> <a name="timeUnitInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.timeUnitInput"></a>

```java
public java.lang.String getTimeUnitInput();
```

- *Type:* java.lang.String

---

##### `timeAmount`<sup>Required</sup> <a name="timeAmount" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.timeAmount"></a>

```java
public java.lang.Number getTimeAmount();
```

- *Type:* java.lang.Number

---

##### `timeUnit`<sup>Required</sup> <a name="timeUnit" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.timeUnit"></a>

```java
public java.lang.String getTimeUnit();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationOutputReference.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration">NotificationPolicyAutoRestartActionDuration</a>

---


### NotificationPolicyAutoRestartActionList <a name="NotificationPolicyAutoRestartActionList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyAutoRestartActionList;

new NotificationPolicyAutoRestartActionList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.get"></a>

```java
public NotificationPolicyAutoRestartActionOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction">NotificationPolicyAutoRestartAction</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionList.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction">NotificationPolicyAutoRestartAction</a>>

---


### NotificationPolicyAutoRestartActionOutputReference <a name="NotificationPolicyAutoRestartActionOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyAutoRestartActionOutputReference;

new NotificationPolicyAutoRestartActionOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `putDuration` <a name="putDuration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.putDuration"></a>

```java
public void putDuration(IResolvable OR java.util.List<NotificationPolicyAutoRestartActionDuration> value)
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.putDuration.parameter.value"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration">NotificationPolicyAutoRestartActionDuration</a>>

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.duration">duration</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList">NotificationPolicyAutoRestartActionDurationList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.durationInput">durationInput</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration">NotificationPolicyAutoRestartActionDuration</a>></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.maxRepeatCountInput">maxRepeatCountInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.maxRepeatCount">maxRepeatCount</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction">NotificationPolicyAutoRestartAction</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `duration`<sup>Required</sup> <a name="duration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.duration"></a>

```java
public NotificationPolicyAutoRestartActionDurationList getDuration();
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDurationList">NotificationPolicyAutoRestartActionDurationList</a>

---

##### `durationInput`<sup>Optional</sup> <a name="durationInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.durationInput"></a>

```java
public java.lang.Object getDurationInput();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionDuration">NotificationPolicyAutoRestartActionDuration</a>>

---

##### `maxRepeatCountInput`<sup>Optional</sup> <a name="maxRepeatCountInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.maxRepeatCountInput"></a>

```java
public java.lang.Number getMaxRepeatCountInput();
```

- *Type:* java.lang.Number

---

##### `maxRepeatCount`<sup>Required</sup> <a name="maxRepeatCount" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.maxRepeatCount"></a>

```java
public java.lang.Number getMaxRepeatCount();
```

- *Type:* java.lang.Number

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartActionOutputReference.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyAutoRestartAction">NotificationPolicyAutoRestartAction</a>

---


### NotificationPolicyDeDuplicationActionDurationList <a name="NotificationPolicyDeDuplicationActionDurationList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyDeDuplicationActionDurationList;

new NotificationPolicyDeDuplicationActionDurationList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.get"></a>

```java
public NotificationPolicyDeDuplicationActionDurationOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration">NotificationPolicyDeDuplicationActionDuration</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration">NotificationPolicyDeDuplicationActionDuration</a>>

---


### NotificationPolicyDeDuplicationActionDurationOutputReference <a name="NotificationPolicyDeDuplicationActionDurationOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyDeDuplicationActionDurationOutputReference;

new NotificationPolicyDeDuplicationActionDurationOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetTimeUnit` <a name="resetTimeUnit" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.resetTimeUnit"></a>

```java
public void resetTimeUnit()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.timeAmountInput">timeAmountInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.timeUnitInput">timeUnitInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.timeAmount">timeAmount</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.timeUnit">timeUnit</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration">NotificationPolicyDeDuplicationActionDuration</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `timeAmountInput`<sup>Optional</sup> <a name="timeAmountInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.timeAmountInput"></a>

```java
public java.lang.Number getTimeAmountInput();
```

- *Type:* java.lang.Number

---

##### `timeUnitInput`<sup>Optional</sup> <a name="timeUnitInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.timeUnitInput"></a>

```java
public java.lang.String getTimeUnitInput();
```

- *Type:* java.lang.String

---

##### `timeAmount`<sup>Required</sup> <a name="timeAmount" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.timeAmount"></a>

```java
public java.lang.Number getTimeAmount();
```

- *Type:* java.lang.Number

---

##### `timeUnit`<sup>Required</sup> <a name="timeUnit" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.timeUnit"></a>

```java
public java.lang.String getTimeUnit();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationOutputReference.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration">NotificationPolicyDeDuplicationActionDuration</a>

---


### NotificationPolicyDeDuplicationActionList <a name="NotificationPolicyDeDuplicationActionList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyDeDuplicationActionList;

new NotificationPolicyDeDuplicationActionList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.get"></a>

```java
public NotificationPolicyDeDuplicationActionOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction">NotificationPolicyDeDuplicationAction</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionList.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction">NotificationPolicyDeDuplicationAction</a>>

---


### NotificationPolicyDeDuplicationActionOutputReference <a name="NotificationPolicyDeDuplicationActionOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyDeDuplicationActionOutputReference;

new NotificationPolicyDeDuplicationActionOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `putDuration` <a name="putDuration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.putDuration"></a>

```java
public void putDuration(IResolvable OR java.util.List<NotificationPolicyDeDuplicationActionDuration> value)
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.putDuration.parameter.value"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration">NotificationPolicyDeDuplicationActionDuration</a>>

---

##### `resetDuration` <a name="resetDuration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.resetDuration"></a>

```java
public void resetDuration()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.duration">duration</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList">NotificationPolicyDeDuplicationActionDurationList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.countInput">countInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.deDuplicationActionTypeInput">deDuplicationActionTypeInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.durationInput">durationInput</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration">NotificationPolicyDeDuplicationActionDuration</a>></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.count">count</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.deDuplicationActionType">deDuplicationActionType</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction">NotificationPolicyDeDuplicationAction</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `duration`<sup>Required</sup> <a name="duration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.duration"></a>

```java
public NotificationPolicyDeDuplicationActionDurationList getDuration();
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDurationList">NotificationPolicyDeDuplicationActionDurationList</a>

---

##### `countInput`<sup>Optional</sup> <a name="countInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.countInput"></a>

```java
public java.lang.Number getCountInput();
```

- *Type:* java.lang.Number

---

##### `deDuplicationActionTypeInput`<sup>Optional</sup> <a name="deDuplicationActionTypeInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.deDuplicationActionTypeInput"></a>

```java
public java.lang.String getDeDuplicationActionTypeInput();
```

- *Type:* java.lang.String

---

##### `durationInput`<sup>Optional</sup> <a name="durationInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.durationInput"></a>

```java
public java.lang.Object getDurationInput();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionDuration">NotificationPolicyDeDuplicationActionDuration</a>>

---

##### `count`<sup>Required</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.count"></a>

```java
public java.lang.Number getCount();
```

- *Type:* java.lang.Number

---

##### `deDuplicationActionType`<sup>Required</sup> <a name="deDuplicationActionType" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.deDuplicationActionType"></a>

```java
public java.lang.String getDeDuplicationActionType();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationActionOutputReference.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDeDuplicationAction">NotificationPolicyDeDuplicationAction</a>

---


### NotificationPolicyDelayActionDurationList <a name="NotificationPolicyDelayActionDurationList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyDelayActionDurationList;

new NotificationPolicyDelayActionDurationList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.get"></a>

```java
public NotificationPolicyDelayActionDurationOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration">NotificationPolicyDelayActionDuration</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration">NotificationPolicyDelayActionDuration</a>>

---


### NotificationPolicyDelayActionDurationOutputReference <a name="NotificationPolicyDelayActionDurationOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyDelayActionDurationOutputReference;

new NotificationPolicyDelayActionDurationOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetTimeUnit` <a name="resetTimeUnit" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.resetTimeUnit"></a>

```java
public void resetTimeUnit()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.timeAmountInput">timeAmountInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.timeUnitInput">timeUnitInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.timeAmount">timeAmount</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.timeUnit">timeUnit</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration">NotificationPolicyDelayActionDuration</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `timeAmountInput`<sup>Optional</sup> <a name="timeAmountInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.timeAmountInput"></a>

```java
public java.lang.Number getTimeAmountInput();
```

- *Type:* java.lang.Number

---

##### `timeUnitInput`<sup>Optional</sup> <a name="timeUnitInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.timeUnitInput"></a>

```java
public java.lang.String getTimeUnitInput();
```

- *Type:* java.lang.String

---

##### `timeAmount`<sup>Required</sup> <a name="timeAmount" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.timeAmount"></a>

```java
public java.lang.Number getTimeAmount();
```

- *Type:* java.lang.Number

---

##### `timeUnit`<sup>Required</sup> <a name="timeUnit" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.timeUnit"></a>

```java
public java.lang.String getTimeUnit();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationOutputReference.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration">NotificationPolicyDelayActionDuration</a>

---


### NotificationPolicyDelayActionList <a name="NotificationPolicyDelayActionList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyDelayActionList;

new NotificationPolicyDelayActionList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.get"></a>

```java
public NotificationPolicyDelayActionOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction">NotificationPolicyDelayAction</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionList.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction">NotificationPolicyDelayAction</a>>

---


### NotificationPolicyDelayActionOutputReference <a name="NotificationPolicyDelayActionOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyDelayActionOutputReference;

new NotificationPolicyDelayActionOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `putDuration` <a name="putDuration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.putDuration"></a>

```java
public void putDuration(IResolvable OR java.util.List<NotificationPolicyDelayActionDuration> value)
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.putDuration.parameter.value"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration">NotificationPolicyDelayActionDuration</a>>

---

##### `resetDuration` <a name="resetDuration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.resetDuration"></a>

```java
public void resetDuration()
```

##### `resetUntilHour` <a name="resetUntilHour" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.resetUntilHour"></a>

```java
public void resetUntilHour()
```

##### `resetUntilMinute` <a name="resetUntilMinute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.resetUntilMinute"></a>

```java
public void resetUntilMinute()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.duration">duration</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList">NotificationPolicyDelayActionDurationList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.delayOptionInput">delayOptionInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.durationInput">durationInput</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration">NotificationPolicyDelayActionDuration</a>></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.untilHourInput">untilHourInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.untilMinuteInput">untilMinuteInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.delayOption">delayOption</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.untilHour">untilHour</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.untilMinute">untilMinute</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction">NotificationPolicyDelayAction</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `duration`<sup>Required</sup> <a name="duration" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.duration"></a>

```java
public NotificationPolicyDelayActionDurationList getDuration();
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDurationList">NotificationPolicyDelayActionDurationList</a>

---

##### `delayOptionInput`<sup>Optional</sup> <a name="delayOptionInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.delayOptionInput"></a>

```java
public java.lang.String getDelayOptionInput();
```

- *Type:* java.lang.String

---

##### `durationInput`<sup>Optional</sup> <a name="durationInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.durationInput"></a>

```java
public java.lang.Object getDurationInput();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionDuration">NotificationPolicyDelayActionDuration</a>>

---

##### `untilHourInput`<sup>Optional</sup> <a name="untilHourInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.untilHourInput"></a>

```java
public java.lang.Number getUntilHourInput();
```

- *Type:* java.lang.Number

---

##### `untilMinuteInput`<sup>Optional</sup> <a name="untilMinuteInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.untilMinuteInput"></a>

```java
public java.lang.Number getUntilMinuteInput();
```

- *Type:* java.lang.Number

---

##### `delayOption`<sup>Required</sup> <a name="delayOption" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.delayOption"></a>

```java
public java.lang.String getDelayOption();
```

- *Type:* java.lang.String

---

##### `untilHour`<sup>Required</sup> <a name="untilHour" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.untilHour"></a>

```java
public java.lang.Number getUntilHour();
```

- *Type:* java.lang.Number

---

##### `untilMinute`<sup>Required</sup> <a name="untilMinute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.untilMinute"></a>

```java
public java.lang.Number getUntilMinute();
```

- *Type:* java.lang.Number

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayActionOutputReference.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyDelayAction">NotificationPolicyDelayAction</a>

---


### NotificationPolicyFilterConditionsList <a name="NotificationPolicyFilterConditionsList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyFilterConditionsList;

new NotificationPolicyFilterConditionsList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.get"></a>

```java
public NotificationPolicyFilterConditionsOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions">NotificationPolicyFilterConditions</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions">NotificationPolicyFilterConditions</a>>

---


### NotificationPolicyFilterConditionsOutputReference <a name="NotificationPolicyFilterConditionsOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyFilterConditionsOutputReference;

new NotificationPolicyFilterConditionsOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetExpectedValue` <a name="resetExpectedValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.resetExpectedValue"></a>

```java
public void resetExpectedValue()
```

##### `resetKey` <a name="resetKey" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.resetKey"></a>

```java
public void resetKey()
```

##### `resetNot` <a name="resetNot" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.resetNot"></a>

```java
public void resetNot()
```

##### `resetOrder` <a name="resetOrder" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.resetOrder"></a>

```java
public void resetOrder()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.expectedValueInput">expectedValueInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.fieldInput">fieldInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.keyInput">keyInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.notInput">notInput</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.operationInput">operationInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.orderInput">orderInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.expectedValue">expectedValue</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.field">field</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.key">key</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.not">not</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.operation">operation</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.order">order</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions">NotificationPolicyFilterConditions</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `expectedValueInput`<sup>Optional</sup> <a name="expectedValueInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.expectedValueInput"></a>

```java
public java.lang.String getExpectedValueInput();
```

- *Type:* java.lang.String

---

##### `fieldInput`<sup>Optional</sup> <a name="fieldInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.fieldInput"></a>

```java
public java.lang.String getFieldInput();
```

- *Type:* java.lang.String

---

##### `keyInput`<sup>Optional</sup> <a name="keyInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.keyInput"></a>

```java
public java.lang.String getKeyInput();
```

- *Type:* java.lang.String

---

##### `notInput`<sup>Optional</sup> <a name="notInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.notInput"></a>

```java
public java.lang.Object getNotInput();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

---

##### `operationInput`<sup>Optional</sup> <a name="operationInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.operationInput"></a>

```java
public java.lang.String getOperationInput();
```

- *Type:* java.lang.String

---

##### `orderInput`<sup>Optional</sup> <a name="orderInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.orderInput"></a>

```java
public java.lang.Number getOrderInput();
```

- *Type:* java.lang.Number

---

##### `expectedValue`<sup>Required</sup> <a name="expectedValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.expectedValue"></a>

```java
public java.lang.String getExpectedValue();
```

- *Type:* java.lang.String

---

##### `field`<sup>Required</sup> <a name="field" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.field"></a>

```java
public java.lang.String getField();
```

- *Type:* java.lang.String

---

##### `key`<sup>Required</sup> <a name="key" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.key"></a>

```java
public java.lang.String getKey();
```

- *Type:* java.lang.String

---

##### `not`<sup>Required</sup> <a name="not" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.not"></a>

```java
public java.lang.Object getNot();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

---

##### `operation`<sup>Required</sup> <a name="operation" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.operation"></a>

```java
public java.lang.String getOperation();
```

- *Type:* java.lang.String

---

##### `order`<sup>Required</sup> <a name="order" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.order"></a>

```java
public java.lang.Number getOrder();
```

- *Type:* java.lang.Number

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsOutputReference.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions">NotificationPolicyFilterConditions</a>

---


### NotificationPolicyFilterList <a name="NotificationPolicyFilterList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyFilterList;

new NotificationPolicyFilterList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.get"></a>

```java
public NotificationPolicyFilterOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter">NotificationPolicyFilter</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterList.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter">NotificationPolicyFilter</a>>

---


### NotificationPolicyFilterOutputReference <a name="NotificationPolicyFilterOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyFilterOutputReference;

new NotificationPolicyFilterOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `putConditions` <a name="putConditions" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.putConditions"></a>

```java
public void putConditions(IResolvable OR java.util.List<NotificationPolicyFilterConditions> value)
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.putConditions.parameter.value"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions">NotificationPolicyFilterConditions</a>>

---

##### `resetConditions` <a name="resetConditions" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.resetConditions"></a>

```java
public void resetConditions()
```

##### `resetType` <a name="resetType" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.resetType"></a>

```java
public void resetType()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.conditions">conditions</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList">NotificationPolicyFilterConditionsList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.conditionsInput">conditionsInput</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions">NotificationPolicyFilterConditions</a>></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.typeInput">typeInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.type">type</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter">NotificationPolicyFilter</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `conditions`<sup>Required</sup> <a name="conditions" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.conditions"></a>

```java
public NotificationPolicyFilterConditionsList getConditions();
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditionsList">NotificationPolicyFilterConditionsList</a>

---

##### `conditionsInput`<sup>Optional</sup> <a name="conditionsInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.conditionsInput"></a>

```java
public java.lang.Object getConditionsInput();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterConditions">NotificationPolicyFilterConditions</a>>

---

##### `typeInput`<sup>Optional</sup> <a name="typeInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.typeInput"></a>

```java
public java.lang.String getTypeInput();
```

- *Type:* java.lang.String

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.type"></a>

```java
public java.lang.String getType();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilterOutputReference.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyFilter">NotificationPolicyFilter</a>

---


### NotificationPolicyTimeRestrictionList <a name="NotificationPolicyTimeRestrictionList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyTimeRestrictionList;

new NotificationPolicyTimeRestrictionList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.get"></a>

```java
public NotificationPolicyTimeRestrictionOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction">NotificationPolicyTimeRestriction</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionList.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction">NotificationPolicyTimeRestriction</a>>

---


### NotificationPolicyTimeRestrictionOutputReference <a name="NotificationPolicyTimeRestrictionOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyTimeRestrictionOutputReference;

new NotificationPolicyTimeRestrictionOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `putRestriction` <a name="putRestriction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.putRestriction"></a>

```java
public void putRestriction(IResolvable OR java.util.List<NotificationPolicyTimeRestrictionRestriction> value)
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.putRestriction.parameter.value"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction">NotificationPolicyTimeRestrictionRestriction</a>>

---

##### `putRestrictions` <a name="putRestrictions" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.putRestrictions"></a>

```java
public void putRestrictions(IResolvable OR java.util.List<NotificationPolicyTimeRestrictionRestrictions> value)
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.putRestrictions.parameter.value"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions">NotificationPolicyTimeRestrictionRestrictions</a>>

---

##### `resetRestriction` <a name="resetRestriction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.resetRestriction"></a>

```java
public void resetRestriction()
```

##### `resetRestrictions` <a name="resetRestrictions" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.resetRestrictions"></a>

```java
public void resetRestrictions()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.restriction">restriction</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList">NotificationPolicyTimeRestrictionRestrictionList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.restrictions">restrictions</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList">NotificationPolicyTimeRestrictionRestrictionsList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.restrictionInput">restrictionInput</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction">NotificationPolicyTimeRestrictionRestriction</a>></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.restrictionsInput">restrictionsInput</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions">NotificationPolicyTimeRestrictionRestrictions</a>></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.typeInput">typeInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.type">type</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction">NotificationPolicyTimeRestriction</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `restriction`<sup>Required</sup> <a name="restriction" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.restriction"></a>

```java
public NotificationPolicyTimeRestrictionRestrictionList getRestriction();
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList">NotificationPolicyTimeRestrictionRestrictionList</a>

---

##### `restrictions`<sup>Required</sup> <a name="restrictions" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.restrictions"></a>

```java
public NotificationPolicyTimeRestrictionRestrictionsList getRestrictions();
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList">NotificationPolicyTimeRestrictionRestrictionsList</a>

---

##### `restrictionInput`<sup>Optional</sup> <a name="restrictionInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.restrictionInput"></a>

```java
public java.lang.Object getRestrictionInput();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction">NotificationPolicyTimeRestrictionRestriction</a>>

---

##### `restrictionsInput`<sup>Optional</sup> <a name="restrictionsInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.restrictionsInput"></a>

```java
public java.lang.Object getRestrictionsInput();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions">NotificationPolicyTimeRestrictionRestrictions</a>>

---

##### `typeInput`<sup>Optional</sup> <a name="typeInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.typeInput"></a>

```java
public java.lang.String getTypeInput();
```

- *Type:* java.lang.String

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.type"></a>

```java
public java.lang.String getType();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionOutputReference.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestriction">NotificationPolicyTimeRestriction</a>

---


### NotificationPolicyTimeRestrictionRestrictionList <a name="NotificationPolicyTimeRestrictionRestrictionList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyTimeRestrictionRestrictionList;

new NotificationPolicyTimeRestrictionRestrictionList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.get"></a>

```java
public NotificationPolicyTimeRestrictionRestrictionOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction">NotificationPolicyTimeRestrictionRestriction</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionList.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction">NotificationPolicyTimeRestrictionRestriction</a>>

---


### NotificationPolicyTimeRestrictionRestrictionOutputReference <a name="NotificationPolicyTimeRestrictionRestrictionOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyTimeRestrictionRestrictionOutputReference;

new NotificationPolicyTimeRestrictionRestrictionOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.endHourInput">endHourInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.endMinInput">endMinInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.startHourInput">startHourInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.startMinInput">startMinInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.endHour">endHour</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.endMin">endMin</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.startHour">startHour</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.startMin">startMin</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction">NotificationPolicyTimeRestrictionRestriction</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `endHourInput`<sup>Optional</sup> <a name="endHourInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.endHourInput"></a>

```java
public java.lang.Number getEndHourInput();
```

- *Type:* java.lang.Number

---

##### `endMinInput`<sup>Optional</sup> <a name="endMinInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.endMinInput"></a>

```java
public java.lang.Number getEndMinInput();
```

- *Type:* java.lang.Number

---

##### `startHourInput`<sup>Optional</sup> <a name="startHourInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.startHourInput"></a>

```java
public java.lang.Number getStartHourInput();
```

- *Type:* java.lang.Number

---

##### `startMinInput`<sup>Optional</sup> <a name="startMinInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.startMinInput"></a>

```java
public java.lang.Number getStartMinInput();
```

- *Type:* java.lang.Number

---

##### `endHour`<sup>Required</sup> <a name="endHour" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.endHour"></a>

```java
public java.lang.Number getEndHour();
```

- *Type:* java.lang.Number

---

##### `endMin`<sup>Required</sup> <a name="endMin" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.endMin"></a>

```java
public java.lang.Number getEndMin();
```

- *Type:* java.lang.Number

---

##### `startHour`<sup>Required</sup> <a name="startHour" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.startHour"></a>

```java
public java.lang.Number getStartHour();
```

- *Type:* java.lang.Number

---

##### `startMin`<sup>Required</sup> <a name="startMin" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.startMin"></a>

```java
public java.lang.Number getStartMin();
```

- *Type:* java.lang.Number

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionOutputReference.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestriction">NotificationPolicyTimeRestrictionRestriction</a>

---


### NotificationPolicyTimeRestrictionRestrictionsList <a name="NotificationPolicyTimeRestrictionRestrictionsList" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyTimeRestrictionRestrictionsList;

new NotificationPolicyTimeRestrictionRestrictionsList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.get"></a>

```java
public NotificationPolicyTimeRestrictionRestrictionsOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions">NotificationPolicyTimeRestrictionRestrictions</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsList.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions">NotificationPolicyTimeRestrictionRestrictions</a>>

---


### NotificationPolicyTimeRestrictionRestrictionsOutputReference <a name="NotificationPolicyTimeRestrictionRestrictionsOutputReference" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.notification_policy.NotificationPolicyTimeRestrictionRestrictionsOutputReference;

new NotificationPolicyTimeRestrictionRestrictionsOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.endDayInput">endDayInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.endHourInput">endHourInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.endMinInput">endMinInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.startDayInput">startDayInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.startHourInput">startHourInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.startMinInput">startMinInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.endDay">endDay</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.endHour">endHour</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.endMin">endMin</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.startDay">startDay</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.startHour">startHour</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.startMin">startMin</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions">NotificationPolicyTimeRestrictionRestrictions</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `endDayInput`<sup>Optional</sup> <a name="endDayInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.endDayInput"></a>

```java
public java.lang.String getEndDayInput();
```

- *Type:* java.lang.String

---

##### `endHourInput`<sup>Optional</sup> <a name="endHourInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.endHourInput"></a>

```java
public java.lang.Number getEndHourInput();
```

- *Type:* java.lang.Number

---

##### `endMinInput`<sup>Optional</sup> <a name="endMinInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.endMinInput"></a>

```java
public java.lang.Number getEndMinInput();
```

- *Type:* java.lang.Number

---

##### `startDayInput`<sup>Optional</sup> <a name="startDayInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.startDayInput"></a>

```java
public java.lang.String getStartDayInput();
```

- *Type:* java.lang.String

---

##### `startHourInput`<sup>Optional</sup> <a name="startHourInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.startHourInput"></a>

```java
public java.lang.Number getStartHourInput();
```

- *Type:* java.lang.Number

---

##### `startMinInput`<sup>Optional</sup> <a name="startMinInput" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.startMinInput"></a>

```java
public java.lang.Number getStartMinInput();
```

- *Type:* java.lang.Number

---

##### `endDay`<sup>Required</sup> <a name="endDay" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.endDay"></a>

```java
public java.lang.String getEndDay();
```

- *Type:* java.lang.String

---

##### `endHour`<sup>Required</sup> <a name="endHour" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.endHour"></a>

```java
public java.lang.Number getEndHour();
```

- *Type:* java.lang.Number

---

##### `endMin`<sup>Required</sup> <a name="endMin" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.endMin"></a>

```java
public java.lang.Number getEndMin();
```

- *Type:* java.lang.Number

---

##### `startDay`<sup>Required</sup> <a name="startDay" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.startDay"></a>

```java
public java.lang.String getStartDay();
```

- *Type:* java.lang.String

---

##### `startHour`<sup>Required</sup> <a name="startHour" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.startHour"></a>

```java
public java.lang.Number getStartHour();
```

- *Type:* java.lang.Number

---

##### `startMin`<sup>Required</sup> <a name="startMin" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.startMin"></a>

```java
public java.lang.Number getStartMin();
```

- *Type:* java.lang.Number

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictionsOutputReference.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.notificationPolicy.NotificationPolicyTimeRestrictionRestrictions">NotificationPolicyTimeRestrictionRestrictions</a>

---



