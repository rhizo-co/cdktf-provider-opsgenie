# `data_opsgenie_heartbeat`

Refer to the Terraform Registory for docs: [`data_opsgenie_heartbeat`](https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat).

# `dataOpsgenieHeartbeat` Submodule <a name="`dataOpsgenieHeartbeat` Submodule" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### DataOpsgenieHeartbeat <a name="DataOpsgenieHeartbeat" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat"></a>

Represents a {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat opsgenie_heartbeat}.

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.data_opsgenie_heartbeat.DataOpsgenieHeartbeat;

DataOpsgenieHeartbeat.Builder.create(Construct scope, java.lang.String id)
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
    .name(java.lang.String)
//  .alertMessage(java.lang.String)
//  .alertPriority(java.lang.String)
//  .alertTags(java.util.List<java.lang.String>)
//  .description(java.lang.String)
//  .enabled(java.lang.Boolean)
//  .enabled(IResolvable)
//  .id(java.lang.String)
//  .interval(java.lang.Number)
//  .intervalUnit(java.lang.String)
//  .ownerTeamId(java.lang.String)
    .build();
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.scope">scope</a></code> | <code>software.constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.id">id</a></code> | <code>java.lang.String</code> | The scoped construct ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.connection">connection</a></code> | <code>com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.count">count</a></code> | <code>java.lang.Number OR com.hashicorp.cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.dependsOn">dependsOn</a></code> | <code>java.util.List<com.hashicorp.cdktf.ITerraformDependable></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.forEach">forEach</a></code> | <code>com.hashicorp.cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.lifecycle">lifecycle</a></code> | <code>com.hashicorp.cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.provider">provider</a></code> | <code>com.hashicorp.cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.provisioners">provisioners</a></code> | <code>java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.name">name</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#name DataOpsgenieHeartbeat#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.alertMessage">alertMessage</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_message DataOpsgenieHeartbeat#alert_message}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.alertPriority">alertPriority</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_priority DataOpsgenieHeartbeat#alert_priority}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.alertTags">alertTags</a></code> | <code>java.util.List<java.lang.String></code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_tags DataOpsgenieHeartbeat#alert_tags}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.description">description</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#description DataOpsgenieHeartbeat#description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.enabled">enabled</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#enabled DataOpsgenieHeartbeat#enabled}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.id">id</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#id DataOpsgenieHeartbeat#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.interval">interval</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#interval DataOpsgenieHeartbeat#interval}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.intervalUnit">intervalUnit</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#interval_unit DataOpsgenieHeartbeat#interval_unit}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.ownerTeamId">ownerTeamId</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#owner_team_id DataOpsgenieHeartbeat#owner_team_id}. |

---

##### `scope`<sup>Required</sup> <a name="scope" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.scope"></a>

- *Type:* software.constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.id"></a>

- *Type:* java.lang.String

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.connection"></a>

- *Type:* com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.count"></a>

- *Type:* java.lang.Number OR com.hashicorp.cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.dependsOn"></a>

- *Type:* java.util.List<com.hashicorp.cdktf.ITerraformDependable>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.forEach"></a>

- *Type:* com.hashicorp.cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.lifecycle"></a>

- *Type:* com.hashicorp.cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.provider"></a>

- *Type:* com.hashicorp.cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.provisioners"></a>

- *Type:* java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner>

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.name"></a>

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#name DataOpsgenieHeartbeat#name}.

---

##### `alertMessage`<sup>Optional</sup> <a name="alertMessage" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.alertMessage"></a>

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_message DataOpsgenieHeartbeat#alert_message}.

---

##### `alertPriority`<sup>Optional</sup> <a name="alertPriority" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.alertPriority"></a>

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_priority DataOpsgenieHeartbeat#alert_priority}.

---

##### `alertTags`<sup>Optional</sup> <a name="alertTags" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.alertTags"></a>

- *Type:* java.util.List<java.lang.String>

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_tags DataOpsgenieHeartbeat#alert_tags}.

---

##### `description`<sup>Optional</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.description"></a>

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#description DataOpsgenieHeartbeat#description}.

---

##### `enabled`<sup>Optional</sup> <a name="enabled" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.enabled"></a>

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#enabled DataOpsgenieHeartbeat#enabled}.

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.id"></a>

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#id DataOpsgenieHeartbeat#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `interval`<sup>Optional</sup> <a name="interval" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.interval"></a>

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#interval DataOpsgenieHeartbeat#interval}.

---

##### `intervalUnit`<sup>Optional</sup> <a name="intervalUnit" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.intervalUnit"></a>

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#interval_unit DataOpsgenieHeartbeat#interval_unit}.

---

##### `ownerTeamId`<sup>Optional</sup> <a name="ownerTeamId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.ownerTeamId"></a>

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#owner_team_id DataOpsgenieHeartbeat#owner_team_id}.

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.toString">toString</a></code> | Returns a string representation of this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.addOverride">addOverride</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.overrideLogicalId">overrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetOverrideLogicalId">resetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.toMetadata">toMetadata</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.toTerraform">toTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetAlertMessage">resetAlertMessage</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetAlertPriority">resetAlertPriority</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetAlertTags">resetAlertTags</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetDescription">resetDescription</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetEnabled">resetEnabled</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetId">resetId</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetInterval">resetInterval</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetIntervalUnit">resetIntervalUnit</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetOwnerTeamId">resetOwnerTeamId</a></code> | *No description.* |

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.toString"></a>

```java
public java.lang.String toString()
```

Returns a string representation of this construct.

##### `addOverride` <a name="addOverride" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.addOverride"></a>

```java
public void addOverride(java.lang.String path, java.lang.Object value)
```

###### `path`<sup>Required</sup> <a name="path" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.addOverride.parameter.path"></a>

- *Type:* java.lang.String

---

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.addOverride.parameter.value"></a>

- *Type:* java.lang.Object

---

##### `overrideLogicalId` <a name="overrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.overrideLogicalId"></a>

```java
public void overrideLogicalId(java.lang.String newLogicalId)
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* java.lang.String

The new logical ID to use for this stack element.

---

##### `resetOverrideLogicalId` <a name="resetOverrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetOverrideLogicalId"></a>

```java
public void resetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `toMetadata` <a name="toMetadata" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.toMetadata"></a>

```java
public java.lang.Object toMetadata()
```

##### `toTerraform` <a name="toTerraform" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.toTerraform"></a>

```java
public java.lang.Object toTerraform()
```

Adds this resource to the terraform JSON output.

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `resetAlertMessage` <a name="resetAlertMessage" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetAlertMessage"></a>

```java
public void resetAlertMessage()
```

##### `resetAlertPriority` <a name="resetAlertPriority" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetAlertPriority"></a>

```java
public void resetAlertPriority()
```

##### `resetAlertTags` <a name="resetAlertTags" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetAlertTags"></a>

```java
public void resetAlertTags()
```

##### `resetDescription` <a name="resetDescription" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetDescription"></a>

```java
public void resetDescription()
```

##### `resetEnabled` <a name="resetEnabled" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetEnabled"></a>

```java
public void resetEnabled()
```

##### `resetId` <a name="resetId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetId"></a>

```java
public void resetId()
```

##### `resetInterval` <a name="resetInterval" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetInterval"></a>

```java
public void resetInterval()
```

##### `resetIntervalUnit` <a name="resetIntervalUnit" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetIntervalUnit"></a>

```java
public void resetIntervalUnit()
```

##### `resetOwnerTeamId` <a name="resetOwnerTeamId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetOwnerTeamId"></a>

```java
public void resetOwnerTeamId()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isConstruct">isConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isTerraformElement">isTerraformElement</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isTerraformDataSource">isTerraformDataSource</a></code> | *No description.* |

---

##### `isConstruct` <a name="isConstruct" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isConstruct"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.data_opsgenie_heartbeat.DataOpsgenieHeartbeat;

DataOpsgenieHeartbeat.isConstruct(java.lang.Object x)
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

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isConstruct.parameter.x"></a>

- *Type:* java.lang.Object

Any object.

---

##### `isTerraformElement` <a name="isTerraformElement" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isTerraformElement"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.data_opsgenie_heartbeat.DataOpsgenieHeartbeat;

DataOpsgenieHeartbeat.isTerraformElement(java.lang.Object x)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isTerraformElement.parameter.x"></a>

- *Type:* java.lang.Object

---

##### `isTerraformDataSource` <a name="isTerraformDataSource" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isTerraformDataSource"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.data_opsgenie_heartbeat.DataOpsgenieHeartbeat;

DataOpsgenieHeartbeat.isTerraformDataSource(java.lang.Object x)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isTerraformDataSource.parameter.x"></a>

- *Type:* java.lang.Object

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.node">node</a></code> | <code>software.constructs.Node</code> | The tree node. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.cdktfStack">cdktfStack</a></code> | <code>com.hashicorp.cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.friendlyUniqueId">friendlyUniqueId</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.terraformMetaArguments">terraformMetaArguments</a></code> | <code>java.util.Map<java.lang.String, java.lang.Object></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.terraformResourceType">terraformResourceType</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.terraformGeneratorMetadata">terraformGeneratorMetadata</a></code> | <code>com.hashicorp.cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.count">count</a></code> | <code>java.lang.Number OR com.hashicorp.cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.dependsOn">dependsOn</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.forEach">forEach</a></code> | <code>com.hashicorp.cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.lifecycle">lifecycle</a></code> | <code>com.hashicorp.cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.provider">provider</a></code> | <code>com.hashicorp.cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertMessageInput">alertMessageInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertPriorityInput">alertPriorityInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertTagsInput">alertTagsInput</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.descriptionInput">descriptionInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.enabledInput">enabledInput</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.idInput">idInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.intervalInput">intervalInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.intervalUnitInput">intervalUnitInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.nameInput">nameInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.ownerTeamIdInput">ownerTeamIdInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertMessage">alertMessage</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertPriority">alertPriority</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertTags">alertTags</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.description">description</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.enabled">enabled</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.id">id</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.interval">interval</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.intervalUnit">intervalUnit</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.name">name</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.ownerTeamId">ownerTeamId</a></code> | <code>java.lang.String</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.node"></a>

```java
public Node getNode();
```

- *Type:* software.constructs.Node

The tree node.

---

##### `cdktfStack`<sup>Required</sup> <a name="cdktfStack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.cdktfStack"></a>

```java
public TerraformStack getCdktfStack();
```

- *Type:* com.hashicorp.cdktf.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `friendlyUniqueId`<sup>Required</sup> <a name="friendlyUniqueId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.friendlyUniqueId"></a>

```java
public java.lang.String getFriendlyUniqueId();
```

- *Type:* java.lang.String

---

##### `terraformMetaArguments`<sup>Required</sup> <a name="terraformMetaArguments" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.terraformMetaArguments"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getTerraformMetaArguments();
```

- *Type:* java.util.Map<java.lang.String, java.lang.Object>

---

##### `terraformResourceType`<sup>Required</sup> <a name="terraformResourceType" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.terraformResourceType"></a>

```java
public java.lang.String getTerraformResourceType();
```

- *Type:* java.lang.String

---

##### `terraformGeneratorMetadata`<sup>Optional</sup> <a name="terraformGeneratorMetadata" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.terraformGeneratorMetadata"></a>

```java
public TerraformProviderGeneratorMetadata getTerraformGeneratorMetadata();
```

- *Type:* com.hashicorp.cdktf.TerraformProviderGeneratorMetadata

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.count"></a>

```java
public java.lang.Object getCount();
```

- *Type:* java.lang.Number OR com.hashicorp.cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.dependsOn"></a>

```java
public java.util.List<java.lang.String> getDependsOn();
```

- *Type:* java.util.List<java.lang.String>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.forEach"></a>

```java
public ITerraformIterator getForEach();
```

- *Type:* com.hashicorp.cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.lifecycle"></a>

```java
public TerraformResourceLifecycle getLifecycle();
```

- *Type:* com.hashicorp.cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.provider"></a>

```java
public TerraformProvider getProvider();
```

- *Type:* com.hashicorp.cdktf.TerraformProvider

---

##### `alertMessageInput`<sup>Optional</sup> <a name="alertMessageInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertMessageInput"></a>

```java
public java.lang.String getAlertMessageInput();
```

- *Type:* java.lang.String

---

##### `alertPriorityInput`<sup>Optional</sup> <a name="alertPriorityInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertPriorityInput"></a>

```java
public java.lang.String getAlertPriorityInput();
```

- *Type:* java.lang.String

---

##### `alertTagsInput`<sup>Optional</sup> <a name="alertTagsInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertTagsInput"></a>

```java
public java.util.List<java.lang.String> getAlertTagsInput();
```

- *Type:* java.util.List<java.lang.String>

---

##### `descriptionInput`<sup>Optional</sup> <a name="descriptionInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.descriptionInput"></a>

```java
public java.lang.String getDescriptionInput();
```

- *Type:* java.lang.String

---

##### `enabledInput`<sup>Optional</sup> <a name="enabledInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.enabledInput"></a>

```java
public java.lang.Object getEnabledInput();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

---

##### `idInput`<sup>Optional</sup> <a name="idInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.idInput"></a>

```java
public java.lang.String getIdInput();
```

- *Type:* java.lang.String

---

##### `intervalInput`<sup>Optional</sup> <a name="intervalInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.intervalInput"></a>

```java
public java.lang.Number getIntervalInput();
```

- *Type:* java.lang.Number

---

##### `intervalUnitInput`<sup>Optional</sup> <a name="intervalUnitInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.intervalUnitInput"></a>

```java
public java.lang.String getIntervalUnitInput();
```

- *Type:* java.lang.String

---

##### `nameInput`<sup>Optional</sup> <a name="nameInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.nameInput"></a>

```java
public java.lang.String getNameInput();
```

- *Type:* java.lang.String

---

##### `ownerTeamIdInput`<sup>Optional</sup> <a name="ownerTeamIdInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.ownerTeamIdInput"></a>

```java
public java.lang.String getOwnerTeamIdInput();
```

- *Type:* java.lang.String

---

##### `alertMessage`<sup>Required</sup> <a name="alertMessage" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertMessage"></a>

```java
public java.lang.String getAlertMessage();
```

- *Type:* java.lang.String

---

##### `alertPriority`<sup>Required</sup> <a name="alertPriority" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertPriority"></a>

```java
public java.lang.String getAlertPriority();
```

- *Type:* java.lang.String

---

##### `alertTags`<sup>Required</sup> <a name="alertTags" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertTags"></a>

```java
public java.util.List<java.lang.String> getAlertTags();
```

- *Type:* java.util.List<java.lang.String>

---

##### `description`<sup>Required</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.description"></a>

```java
public java.lang.String getDescription();
```

- *Type:* java.lang.String

---

##### `enabled`<sup>Required</sup> <a name="enabled" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.enabled"></a>

```java
public java.lang.Object getEnabled();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.id"></a>

```java
public java.lang.String getId();
```

- *Type:* java.lang.String

---

##### `interval`<sup>Required</sup> <a name="interval" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.interval"></a>

```java
public java.lang.Number getInterval();
```

- *Type:* java.lang.Number

---

##### `intervalUnit`<sup>Required</sup> <a name="intervalUnit" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.intervalUnit"></a>

```java
public java.lang.String getIntervalUnit();
```

- *Type:* java.lang.String

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.name"></a>

```java
public java.lang.String getName();
```

- *Type:* java.lang.String

---

##### `ownerTeamId`<sup>Required</sup> <a name="ownerTeamId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.ownerTeamId"></a>

```java
public java.lang.String getOwnerTeamId();
```

- *Type:* java.lang.String

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.tfResourceType">tfResourceType</a></code> | <code>java.lang.String</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.tfResourceType"></a>

```java
public java.lang.String getTfResourceType();
```

- *Type:* java.lang.String

---

## Structs <a name="Structs" id="Structs"></a>

### DataOpsgenieHeartbeatConfig <a name="DataOpsgenieHeartbeatConfig" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.data_opsgenie_heartbeat.DataOpsgenieHeartbeatConfig;

DataOpsgenieHeartbeatConfig.builder()
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
    .name(java.lang.String)
//  .alertMessage(java.lang.String)
//  .alertPriority(java.lang.String)
//  .alertTags(java.util.List<java.lang.String>)
//  .description(java.lang.String)
//  .enabled(java.lang.Boolean)
//  .enabled(IResolvable)
//  .id(java.lang.String)
//  .interval(java.lang.Number)
//  .intervalUnit(java.lang.String)
//  .ownerTeamId(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.connection">connection</a></code> | <code>com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.count">count</a></code> | <code>java.lang.Number OR com.hashicorp.cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.dependsOn">dependsOn</a></code> | <code>java.util.List<com.hashicorp.cdktf.ITerraformDependable></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.forEach">forEach</a></code> | <code>com.hashicorp.cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.lifecycle">lifecycle</a></code> | <code>com.hashicorp.cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.provider">provider</a></code> | <code>com.hashicorp.cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.provisioners">provisioners</a></code> | <code>java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.name">name</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#name DataOpsgenieHeartbeat#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.alertMessage">alertMessage</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_message DataOpsgenieHeartbeat#alert_message}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.alertPriority">alertPriority</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_priority DataOpsgenieHeartbeat#alert_priority}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.alertTags">alertTags</a></code> | <code>java.util.List<java.lang.String></code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_tags DataOpsgenieHeartbeat#alert_tags}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.description">description</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#description DataOpsgenieHeartbeat#description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.enabled">enabled</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#enabled DataOpsgenieHeartbeat#enabled}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.id">id</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#id DataOpsgenieHeartbeat#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.interval">interval</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#interval DataOpsgenieHeartbeat#interval}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.intervalUnit">intervalUnit</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#interval_unit DataOpsgenieHeartbeat#interval_unit}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.ownerTeamId">ownerTeamId</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#owner_team_id DataOpsgenieHeartbeat#owner_team_id}. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.connection"></a>

```java
public java.lang.Object getConnection();
```

- *Type:* com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.count"></a>

```java
public java.lang.Object getCount();
```

- *Type:* java.lang.Number OR com.hashicorp.cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.dependsOn"></a>

```java
public java.util.List<ITerraformDependable> getDependsOn();
```

- *Type:* java.util.List<com.hashicorp.cdktf.ITerraformDependable>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.forEach"></a>

```java
public ITerraformIterator getForEach();
```

- *Type:* com.hashicorp.cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.lifecycle"></a>

```java
public TerraformResourceLifecycle getLifecycle();
```

- *Type:* com.hashicorp.cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.provider"></a>

```java
public TerraformProvider getProvider();
```

- *Type:* com.hashicorp.cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.provisioners"></a>

```java
public java.lang.Object getProvisioners();
```

- *Type:* java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner>

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.name"></a>

```java
public java.lang.String getName();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#name DataOpsgenieHeartbeat#name}.

---

##### `alertMessage`<sup>Optional</sup> <a name="alertMessage" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.alertMessage"></a>

```java
public java.lang.String getAlertMessage();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_message DataOpsgenieHeartbeat#alert_message}.

---

##### `alertPriority`<sup>Optional</sup> <a name="alertPriority" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.alertPriority"></a>

```java
public java.lang.String getAlertPriority();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_priority DataOpsgenieHeartbeat#alert_priority}.

---

##### `alertTags`<sup>Optional</sup> <a name="alertTags" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.alertTags"></a>

```java
public java.util.List<java.lang.String> getAlertTags();
```

- *Type:* java.util.List<java.lang.String>

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_tags DataOpsgenieHeartbeat#alert_tags}.

---

##### `description`<sup>Optional</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.description"></a>

```java
public java.lang.String getDescription();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#description DataOpsgenieHeartbeat#description}.

---

##### `enabled`<sup>Optional</sup> <a name="enabled" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.enabled"></a>

```java
public java.lang.Object getEnabled();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#enabled DataOpsgenieHeartbeat#enabled}.

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.id"></a>

```java
public java.lang.String getId();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#id DataOpsgenieHeartbeat#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `interval`<sup>Optional</sup> <a name="interval" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.interval"></a>

```java
public java.lang.Number getInterval();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#interval DataOpsgenieHeartbeat#interval}.

---

##### `intervalUnit`<sup>Optional</sup> <a name="intervalUnit" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.intervalUnit"></a>

```java
public java.lang.String getIntervalUnit();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#interval_unit DataOpsgenieHeartbeat#interval_unit}.

---

##### `ownerTeamId`<sup>Optional</sup> <a name="ownerTeamId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.ownerTeamId"></a>

```java
public java.lang.String getOwnerTeamId();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#owner_team_id DataOpsgenieHeartbeat#owner_team_id}.

---



