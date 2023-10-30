# `data_opsgenie_escalation`

Refer to the Terraform Registory for docs: [`data_opsgenie_escalation`](https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation).

# `dataOpsgenieEscalation` Submodule <a name="`dataOpsgenieEscalation` Submodule" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### DataOpsgenieEscalation <a name="DataOpsgenieEscalation" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation"></a>

Represents a {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation opsgenie_escalation}.

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.data_opsgenie_escalation.DataOpsgenieEscalation;

DataOpsgenieEscalation.Builder.create(Construct scope, java.lang.String id)
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
//  .description(java.lang.String)
//  .id(java.lang.String)
//  .ownerTeamId(java.lang.String)
//  .repeat(IResolvable)
//  .repeat(java.util.List<DataOpsgenieEscalationRepeat>)
//  .rules(IResolvable)
//  .rules(java.util.List<DataOpsgenieEscalationRules>)
    .build();
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.scope">scope</a></code> | <code>software.constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.id">id</a></code> | <code>java.lang.String</code> | The scoped construct ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.connection">connection</a></code> | <code>com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.count">count</a></code> | <code>java.lang.Number OR com.hashicorp.cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.dependsOn">dependsOn</a></code> | <code>java.util.List<com.hashicorp.cdktf.ITerraformDependable></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.forEach">forEach</a></code> | <code>com.hashicorp.cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.lifecycle">lifecycle</a></code> | <code>com.hashicorp.cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.provider">provider</a></code> | <code>com.hashicorp.cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.provisioners">provisioners</a></code> | <code>java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.name">name</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#name DataOpsgenieEscalation#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.description">description</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#description DataOpsgenieEscalation#description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.id">id</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#id DataOpsgenieEscalation#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.ownerTeamId">ownerTeamId</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#owner_team_id DataOpsgenieEscalation#owner_team_id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.repeat">repeat</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat">DataOpsgenieEscalationRepeat</a>></code> | repeat block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.rules">rules</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules">DataOpsgenieEscalationRules</a>></code> | rules block. |

---

##### `scope`<sup>Required</sup> <a name="scope" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.scope"></a>

- *Type:* software.constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.id"></a>

- *Type:* java.lang.String

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.connection"></a>

- *Type:* com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.count"></a>

- *Type:* java.lang.Number OR com.hashicorp.cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.dependsOn"></a>

- *Type:* java.util.List<com.hashicorp.cdktf.ITerraformDependable>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.forEach"></a>

- *Type:* com.hashicorp.cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.lifecycle"></a>

- *Type:* com.hashicorp.cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.provider"></a>

- *Type:* com.hashicorp.cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.provisioners"></a>

- *Type:* java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner>

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.name"></a>

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#name DataOpsgenieEscalation#name}.

---

##### `description`<sup>Optional</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.description"></a>

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#description DataOpsgenieEscalation#description}.

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.id"></a>

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#id DataOpsgenieEscalation#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `ownerTeamId`<sup>Optional</sup> <a name="ownerTeamId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.ownerTeamId"></a>

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#owner_team_id DataOpsgenieEscalation#owner_team_id}.

---

##### `repeat`<sup>Optional</sup> <a name="repeat" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.repeat"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat">DataOpsgenieEscalationRepeat</a>>

repeat block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#repeat DataOpsgenieEscalation#repeat}

---

##### `rules`<sup>Optional</sup> <a name="rules" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.Initializer.parameter.rules"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules">DataOpsgenieEscalationRules</a>>

rules block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#rules DataOpsgenieEscalation#rules}

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

```java
public java.lang.String toString()
```

Returns a string representation of this construct.

##### `addOverride` <a name="addOverride" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.addOverride"></a>

```java
public void addOverride(java.lang.String path, java.lang.Object value)
```

###### `path`<sup>Required</sup> <a name="path" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.addOverride.parameter.path"></a>

- *Type:* java.lang.String

---

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.addOverride.parameter.value"></a>

- *Type:* java.lang.Object

---

##### `overrideLogicalId` <a name="overrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.overrideLogicalId"></a>

```java
public void overrideLogicalId(java.lang.String newLogicalId)
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* java.lang.String

The new logical ID to use for this stack element.

---

##### `resetOverrideLogicalId` <a name="resetOverrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetOverrideLogicalId"></a>

```java
public void resetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `toMetadata` <a name="toMetadata" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.toMetadata"></a>

```java
public java.lang.Object toMetadata()
```

##### `toTerraform` <a name="toTerraform" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.toTerraform"></a>

```java
public java.lang.Object toTerraform()
```

Adds this resource to the terraform JSON output.

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `putRepeat` <a name="putRepeat" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.putRepeat"></a>

```java
public void putRepeat(IResolvable OR java.util.List<DataOpsgenieEscalationRepeat> value)
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.putRepeat.parameter.value"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat">DataOpsgenieEscalationRepeat</a>>

---

##### `putRules` <a name="putRules" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.putRules"></a>

```java
public void putRules(IResolvable OR java.util.List<DataOpsgenieEscalationRules> value)
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.putRules.parameter.value"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules">DataOpsgenieEscalationRules</a>>

---

##### `resetDescription` <a name="resetDescription" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetDescription"></a>

```java
public void resetDescription()
```

##### `resetId` <a name="resetId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetId"></a>

```java
public void resetId()
```

##### `resetOwnerTeamId` <a name="resetOwnerTeamId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetOwnerTeamId"></a>

```java
public void resetOwnerTeamId()
```

##### `resetRepeat` <a name="resetRepeat" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetRepeat"></a>

```java
public void resetRepeat()
```

##### `resetRules` <a name="resetRules" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.resetRules"></a>

```java
public void resetRules()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.isConstruct">isConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.isTerraformElement">isTerraformElement</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.isTerraformDataSource">isTerraformDataSource</a></code> | *No description.* |

---

##### `isConstruct` <a name="isConstruct" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.isConstruct"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.data_opsgenie_escalation.DataOpsgenieEscalation;

DataOpsgenieEscalation.isConstruct(java.lang.Object x)
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

- *Type:* java.lang.Object

Any object.

---

##### `isTerraformElement` <a name="isTerraformElement" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.isTerraformElement"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.data_opsgenie_escalation.DataOpsgenieEscalation;

DataOpsgenieEscalation.isTerraformElement(java.lang.Object x)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.isTerraformElement.parameter.x"></a>

- *Type:* java.lang.Object

---

##### `isTerraformDataSource` <a name="isTerraformDataSource" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.isTerraformDataSource"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.data_opsgenie_escalation.DataOpsgenieEscalation;

DataOpsgenieEscalation.isTerraformDataSource(java.lang.Object x)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.isTerraformDataSource.parameter.x"></a>

- *Type:* java.lang.Object

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.node">node</a></code> | <code>software.constructs.Node</code> | The tree node. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.cdktfStack">cdktfStack</a></code> | <code>com.hashicorp.cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.friendlyUniqueId">friendlyUniqueId</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.terraformMetaArguments">terraformMetaArguments</a></code> | <code>java.util.Map<java.lang.String, java.lang.Object></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.terraformResourceType">terraformResourceType</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.terraformGeneratorMetadata">terraformGeneratorMetadata</a></code> | <code>com.hashicorp.cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.count">count</a></code> | <code>java.lang.Number OR com.hashicorp.cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.dependsOn">dependsOn</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.forEach">forEach</a></code> | <code>com.hashicorp.cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.lifecycle">lifecycle</a></code> | <code>com.hashicorp.cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.provider">provider</a></code> | <code>com.hashicorp.cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.repeat">repeat</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList">DataOpsgenieEscalationRepeatList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.rules">rules</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList">DataOpsgenieEscalationRulesList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.descriptionInput">descriptionInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.idInput">idInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.nameInput">nameInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.ownerTeamIdInput">ownerTeamIdInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.repeatInput">repeatInput</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat">DataOpsgenieEscalationRepeat</a>></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.rulesInput">rulesInput</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules">DataOpsgenieEscalationRules</a>></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.description">description</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.id">id</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.name">name</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.ownerTeamId">ownerTeamId</a></code> | <code>java.lang.String</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.node"></a>

```java
public Node getNode();
```

- *Type:* software.constructs.Node

The tree node.

---

##### `cdktfStack`<sup>Required</sup> <a name="cdktfStack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.cdktfStack"></a>

```java
public TerraformStack getCdktfStack();
```

- *Type:* com.hashicorp.cdktf.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `friendlyUniqueId`<sup>Required</sup> <a name="friendlyUniqueId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.friendlyUniqueId"></a>

```java
public java.lang.String getFriendlyUniqueId();
```

- *Type:* java.lang.String

---

##### `terraformMetaArguments`<sup>Required</sup> <a name="terraformMetaArguments" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.terraformMetaArguments"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getTerraformMetaArguments();
```

- *Type:* java.util.Map<java.lang.String, java.lang.Object>

---

##### `terraformResourceType`<sup>Required</sup> <a name="terraformResourceType" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.terraformResourceType"></a>

```java
public java.lang.String getTerraformResourceType();
```

- *Type:* java.lang.String

---

##### `terraformGeneratorMetadata`<sup>Optional</sup> <a name="terraformGeneratorMetadata" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.terraformGeneratorMetadata"></a>

```java
public TerraformProviderGeneratorMetadata getTerraformGeneratorMetadata();
```

- *Type:* com.hashicorp.cdktf.TerraformProviderGeneratorMetadata

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.count"></a>

```java
public java.lang.Object getCount();
```

- *Type:* java.lang.Number OR com.hashicorp.cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.dependsOn"></a>

```java
public java.util.List<java.lang.String> getDependsOn();
```

- *Type:* java.util.List<java.lang.String>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.forEach"></a>

```java
public ITerraformIterator getForEach();
```

- *Type:* com.hashicorp.cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.lifecycle"></a>

```java
public TerraformResourceLifecycle getLifecycle();
```

- *Type:* com.hashicorp.cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.provider"></a>

```java
public TerraformProvider getProvider();
```

- *Type:* com.hashicorp.cdktf.TerraformProvider

---

##### `repeat`<sup>Required</sup> <a name="repeat" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.repeat"></a>

```java
public DataOpsgenieEscalationRepeatList getRepeat();
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList">DataOpsgenieEscalationRepeatList</a>

---

##### `rules`<sup>Required</sup> <a name="rules" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.rules"></a>

```java
public DataOpsgenieEscalationRulesList getRules();
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList">DataOpsgenieEscalationRulesList</a>

---

##### `descriptionInput`<sup>Optional</sup> <a name="descriptionInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.descriptionInput"></a>

```java
public java.lang.String getDescriptionInput();
```

- *Type:* java.lang.String

---

##### `idInput`<sup>Optional</sup> <a name="idInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.idInput"></a>

```java
public java.lang.String getIdInput();
```

- *Type:* java.lang.String

---

##### `nameInput`<sup>Optional</sup> <a name="nameInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.nameInput"></a>

```java
public java.lang.String getNameInput();
```

- *Type:* java.lang.String

---

##### `ownerTeamIdInput`<sup>Optional</sup> <a name="ownerTeamIdInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.ownerTeamIdInput"></a>

```java
public java.lang.String getOwnerTeamIdInput();
```

- *Type:* java.lang.String

---

##### `repeatInput`<sup>Optional</sup> <a name="repeatInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.repeatInput"></a>

```java
public java.lang.Object getRepeatInput();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat">DataOpsgenieEscalationRepeat</a>>

---

##### `rulesInput`<sup>Optional</sup> <a name="rulesInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.rulesInput"></a>

```java
public java.lang.Object getRulesInput();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules">DataOpsgenieEscalationRules</a>>

---

##### `description`<sup>Required</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.description"></a>

```java
public java.lang.String getDescription();
```

- *Type:* java.lang.String

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.id"></a>

```java
public java.lang.String getId();
```

- *Type:* java.lang.String

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.name"></a>

```java
public java.lang.String getName();
```

- *Type:* java.lang.String

---

##### `ownerTeamId`<sup>Required</sup> <a name="ownerTeamId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.ownerTeamId"></a>

```java
public java.lang.String getOwnerTeamId();
```

- *Type:* java.lang.String

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.tfResourceType">tfResourceType</a></code> | <code>java.lang.String</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalation.property.tfResourceType"></a>

```java
public java.lang.String getTfResourceType();
```

- *Type:* java.lang.String

---

## Structs <a name="Structs" id="Structs"></a>

### DataOpsgenieEscalationConfig <a name="DataOpsgenieEscalationConfig" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.data_opsgenie_escalation.DataOpsgenieEscalationConfig;

DataOpsgenieEscalationConfig.builder()
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
//  .description(java.lang.String)
//  .id(java.lang.String)
//  .ownerTeamId(java.lang.String)
//  .repeat(IResolvable)
//  .repeat(java.util.List<DataOpsgenieEscalationRepeat>)
//  .rules(IResolvable)
//  .rules(java.util.List<DataOpsgenieEscalationRules>)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.connection">connection</a></code> | <code>com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.count">count</a></code> | <code>java.lang.Number OR com.hashicorp.cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.dependsOn">dependsOn</a></code> | <code>java.util.List<com.hashicorp.cdktf.ITerraformDependable></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.forEach">forEach</a></code> | <code>com.hashicorp.cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.lifecycle">lifecycle</a></code> | <code>com.hashicorp.cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.provider">provider</a></code> | <code>com.hashicorp.cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.provisioners">provisioners</a></code> | <code>java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.name">name</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#name DataOpsgenieEscalation#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.description">description</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#description DataOpsgenieEscalation#description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.id">id</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#id DataOpsgenieEscalation#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.ownerTeamId">ownerTeamId</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#owner_team_id DataOpsgenieEscalation#owner_team_id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.repeat">repeat</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat">DataOpsgenieEscalationRepeat</a>></code> | repeat block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.rules">rules</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules">DataOpsgenieEscalationRules</a>></code> | rules block. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.connection"></a>

```java
public java.lang.Object getConnection();
```

- *Type:* com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.count"></a>

```java
public java.lang.Object getCount();
```

- *Type:* java.lang.Number OR com.hashicorp.cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.dependsOn"></a>

```java
public java.util.List<ITerraformDependable> getDependsOn();
```

- *Type:* java.util.List<com.hashicorp.cdktf.ITerraformDependable>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.forEach"></a>

```java
public ITerraformIterator getForEach();
```

- *Type:* com.hashicorp.cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.lifecycle"></a>

```java
public TerraformResourceLifecycle getLifecycle();
```

- *Type:* com.hashicorp.cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.provider"></a>

```java
public TerraformProvider getProvider();
```

- *Type:* com.hashicorp.cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.provisioners"></a>

```java
public java.lang.Object getProvisioners();
```

- *Type:* java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner>

---

##### `name`<sup>Required</sup> <a name="name" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.name"></a>

```java
public java.lang.String getName();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#name DataOpsgenieEscalation#name}.

---

##### `description`<sup>Optional</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.description"></a>

```java
public java.lang.String getDescription();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#description DataOpsgenieEscalation#description}.

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.id"></a>

```java
public java.lang.String getId();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#id DataOpsgenieEscalation#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `ownerTeamId`<sup>Optional</sup> <a name="ownerTeamId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.ownerTeamId"></a>

```java
public java.lang.String getOwnerTeamId();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#owner_team_id DataOpsgenieEscalation#owner_team_id}.

---

##### `repeat`<sup>Optional</sup> <a name="repeat" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.repeat"></a>

```java
public java.lang.Object getRepeat();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat">DataOpsgenieEscalationRepeat</a>>

repeat block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#repeat DataOpsgenieEscalation#repeat}

---

##### `rules`<sup>Optional</sup> <a name="rules" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationConfig.property.rules"></a>

```java
public java.lang.Object getRules();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules">DataOpsgenieEscalationRules</a>>

rules block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#rules DataOpsgenieEscalation#rules}

---

### DataOpsgenieEscalationRepeat <a name="DataOpsgenieEscalationRepeat" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.data_opsgenie_escalation.DataOpsgenieEscalationRepeat;

DataOpsgenieEscalationRepeat.builder()
//  .closeAlertAfterAll(java.lang.Boolean)
//  .closeAlertAfterAll(IResolvable)
//  .count(java.lang.Number)
//  .resetRecipientStates(java.lang.Boolean)
//  .resetRecipientStates(IResolvable)
//  .waitInterval(java.lang.Number)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat.property.closeAlertAfterAll">closeAlertAfterAll</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#close_alert_after_all DataOpsgenieEscalation#close_alert_after_all}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat.property.count">count</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#count DataOpsgenieEscalation#count}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat.property.resetRecipientStates">resetRecipientStates</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#reset_recipient_states DataOpsgenieEscalation#reset_recipient_states}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat.property.waitInterval">waitInterval</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#wait_interval DataOpsgenieEscalation#wait_interval}. |

---

##### `closeAlertAfterAll`<sup>Optional</sup> <a name="closeAlertAfterAll" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat.property.closeAlertAfterAll"></a>

```java
public java.lang.Object getCloseAlertAfterAll();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#close_alert_after_all DataOpsgenieEscalation#close_alert_after_all}.

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat.property.count"></a>

```java
public java.lang.Number getCount();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#count DataOpsgenieEscalation#count}.

---

##### `resetRecipientStates`<sup>Optional</sup> <a name="resetRecipientStates" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat.property.resetRecipientStates"></a>

```java
public java.lang.Object getResetRecipientStates();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#reset_recipient_states DataOpsgenieEscalation#reset_recipient_states}.

---

##### `waitInterval`<sup>Optional</sup> <a name="waitInterval" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat.property.waitInterval"></a>

```java
public java.lang.Number getWaitInterval();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#wait_interval DataOpsgenieEscalation#wait_interval}.

---

### DataOpsgenieEscalationRules <a name="DataOpsgenieEscalationRules" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.data_opsgenie_escalation.DataOpsgenieEscalationRules;

DataOpsgenieEscalationRules.builder()
    .condition(java.lang.String)
    .delay(java.lang.Number)
    .notifyType(java.lang.String)
    .recipient(IResolvable)
    .recipient(java.util.List<DataOpsgenieEscalationRulesRecipient>)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules.property.condition">condition</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#condition DataOpsgenieEscalation#condition}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules.property.delay">delay</a></code> | <code>java.lang.Number</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#delay DataOpsgenieEscalation#delay}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules.property.notifyType">notifyType</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#notify_type DataOpsgenieEscalation#notify_type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules.property.recipient">recipient</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient">DataOpsgenieEscalationRulesRecipient</a>></code> | recipient block. |

---

##### `condition`<sup>Required</sup> <a name="condition" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules.property.condition"></a>

```java
public java.lang.String getCondition();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#condition DataOpsgenieEscalation#condition}.

---

##### `delay`<sup>Required</sup> <a name="delay" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules.property.delay"></a>

```java
public java.lang.Number getDelay();
```

- *Type:* java.lang.Number

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#delay DataOpsgenieEscalation#delay}.

---

##### `notifyType`<sup>Required</sup> <a name="notifyType" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules.property.notifyType"></a>

```java
public java.lang.String getNotifyType();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#notify_type DataOpsgenieEscalation#notify_type}.

---

##### `recipient`<sup>Required</sup> <a name="recipient" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules.property.recipient"></a>

```java
public java.lang.Object getRecipient();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient">DataOpsgenieEscalationRulesRecipient</a>>

recipient block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#recipient DataOpsgenieEscalation#recipient}

---

### DataOpsgenieEscalationRulesRecipient <a name="DataOpsgenieEscalationRulesRecipient" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.data_opsgenie_escalation.DataOpsgenieEscalationRulesRecipient;

DataOpsgenieEscalationRulesRecipient.builder()
//  .id(java.lang.String)
//  .type(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient.property.id">id</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#id DataOpsgenieEscalation#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient.property.type">type</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#type DataOpsgenieEscalation#type}. |

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient.property.id"></a>

```java
public java.lang.String getId();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#id DataOpsgenieEscalation#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `type`<sup>Optional</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient.property.type"></a>

```java
public java.lang.String getType();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/escalation#type DataOpsgenieEscalation#type}.

---

## Classes <a name="Classes" id="Classes"></a>

### DataOpsgenieEscalationRepeatList <a name="DataOpsgenieEscalationRepeatList" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.data_opsgenie_escalation.DataOpsgenieEscalationRepeatList;

new DataOpsgenieEscalationRepeatList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.get"></a>

```java
public DataOpsgenieEscalationRepeatOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat">DataOpsgenieEscalationRepeat</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatList.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat">DataOpsgenieEscalationRepeat</a>>

---


### DataOpsgenieEscalationRepeatOutputReference <a name="DataOpsgenieEscalationRepeatOutputReference" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.data_opsgenie_escalation.DataOpsgenieEscalationRepeatOutputReference;

new DataOpsgenieEscalationRepeatOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetCloseAlertAfterAll` <a name="resetCloseAlertAfterAll" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resetCloseAlertAfterAll"></a>

```java
public void resetCloseAlertAfterAll()
```

##### `resetCount` <a name="resetCount" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resetCount"></a>

```java
public void resetCount()
```

##### `resetResetRecipientStates` <a name="resetResetRecipientStates" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resetResetRecipientStates"></a>

```java
public void resetResetRecipientStates()
```

##### `resetWaitInterval` <a name="resetWaitInterval" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.resetWaitInterval"></a>

```java
public void resetWaitInterval()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.closeAlertAfterAllInput">closeAlertAfterAllInput</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.countInput">countInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.resetRecipientStatesInput">resetRecipientStatesInput</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.waitIntervalInput">waitIntervalInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.closeAlertAfterAll">closeAlertAfterAll</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.count">count</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.resetRecipientStates">resetRecipientStates</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.waitInterval">waitInterval</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat">DataOpsgenieEscalationRepeat</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `closeAlertAfterAllInput`<sup>Optional</sup> <a name="closeAlertAfterAllInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.closeAlertAfterAllInput"></a>

```java
public java.lang.Object getCloseAlertAfterAllInput();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

---

##### `countInput`<sup>Optional</sup> <a name="countInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.countInput"></a>

```java
public java.lang.Number getCountInput();
```

- *Type:* java.lang.Number

---

##### `resetRecipientStatesInput`<sup>Optional</sup> <a name="resetRecipientStatesInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.resetRecipientStatesInput"></a>

```java
public java.lang.Object getResetRecipientStatesInput();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

---

##### `waitIntervalInput`<sup>Optional</sup> <a name="waitIntervalInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.waitIntervalInput"></a>

```java
public java.lang.Number getWaitIntervalInput();
```

- *Type:* java.lang.Number

---

##### `closeAlertAfterAll`<sup>Required</sup> <a name="closeAlertAfterAll" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.closeAlertAfterAll"></a>

```java
public java.lang.Object getCloseAlertAfterAll();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

---

##### `count`<sup>Required</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.count"></a>

```java
public java.lang.Number getCount();
```

- *Type:* java.lang.Number

---

##### `resetRecipientStates`<sup>Required</sup> <a name="resetRecipientStates" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.resetRecipientStates"></a>

```java
public java.lang.Object getResetRecipientStates();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

---

##### `waitInterval`<sup>Required</sup> <a name="waitInterval" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.waitInterval"></a>

```java
public java.lang.Number getWaitInterval();
```

- *Type:* java.lang.Number

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeatOutputReference.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRepeat">DataOpsgenieEscalationRepeat</a>

---


### DataOpsgenieEscalationRulesList <a name="DataOpsgenieEscalationRulesList" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.data_opsgenie_escalation.DataOpsgenieEscalationRulesList;

new DataOpsgenieEscalationRulesList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.get"></a>

```java
public DataOpsgenieEscalationRulesOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules">DataOpsgenieEscalationRules</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesList.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules">DataOpsgenieEscalationRules</a>>

---


### DataOpsgenieEscalationRulesOutputReference <a name="DataOpsgenieEscalationRulesOutputReference" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.data_opsgenie_escalation.DataOpsgenieEscalationRulesOutputReference;

new DataOpsgenieEscalationRulesOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `putRecipient` <a name="putRecipient" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.putRecipient"></a>

```java
public void putRecipient(IResolvable OR java.util.List<DataOpsgenieEscalationRulesRecipient> value)
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.putRecipient.parameter.value"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient">DataOpsgenieEscalationRulesRecipient</a>>

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.recipient">recipient</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList">DataOpsgenieEscalationRulesRecipientList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.conditionInput">conditionInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.delayInput">delayInput</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.notifyTypeInput">notifyTypeInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.recipientInput">recipientInput</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient">DataOpsgenieEscalationRulesRecipient</a>></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.condition">condition</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.delay">delay</a></code> | <code>java.lang.Number</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.notifyType">notifyType</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules">DataOpsgenieEscalationRules</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `recipient`<sup>Required</sup> <a name="recipient" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.recipient"></a>

```java
public DataOpsgenieEscalationRulesRecipientList getRecipient();
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList">DataOpsgenieEscalationRulesRecipientList</a>

---

##### `conditionInput`<sup>Optional</sup> <a name="conditionInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.conditionInput"></a>

```java
public java.lang.String getConditionInput();
```

- *Type:* java.lang.String

---

##### `delayInput`<sup>Optional</sup> <a name="delayInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.delayInput"></a>

```java
public java.lang.Number getDelayInput();
```

- *Type:* java.lang.Number

---

##### `notifyTypeInput`<sup>Optional</sup> <a name="notifyTypeInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.notifyTypeInput"></a>

```java
public java.lang.String getNotifyTypeInput();
```

- *Type:* java.lang.String

---

##### `recipientInput`<sup>Optional</sup> <a name="recipientInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.recipientInput"></a>

```java
public java.lang.Object getRecipientInput();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient">DataOpsgenieEscalationRulesRecipient</a>>

---

##### `condition`<sup>Required</sup> <a name="condition" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.condition"></a>

```java
public java.lang.String getCondition();
```

- *Type:* java.lang.String

---

##### `delay`<sup>Required</sup> <a name="delay" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.delay"></a>

```java
public java.lang.Number getDelay();
```

- *Type:* java.lang.Number

---

##### `notifyType`<sup>Required</sup> <a name="notifyType" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.notifyType"></a>

```java
public java.lang.String getNotifyType();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesOutputReference.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRules">DataOpsgenieEscalationRules</a>

---


### DataOpsgenieEscalationRulesRecipientList <a name="DataOpsgenieEscalationRulesRecipientList" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.data_opsgenie_escalation.DataOpsgenieEscalationRulesRecipientList;

new DataOpsgenieEscalationRulesRecipientList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.get"></a>

```java
public DataOpsgenieEscalationRulesRecipientOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient">DataOpsgenieEscalationRulesRecipient</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientList.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient">DataOpsgenieEscalationRulesRecipient</a>>

---


### DataOpsgenieEscalationRulesRecipientOutputReference <a name="DataOpsgenieEscalationRulesRecipientOutputReference" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.data_opsgenie_escalation.DataOpsgenieEscalationRulesRecipientOutputReference;

new DataOpsgenieEscalationRulesRecipientOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetId` <a name="resetId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.resetId"></a>

```java
public void resetId()
```

##### `resetType` <a name="resetType" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.resetType"></a>

```java
public void resetType()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.idInput">idInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.typeInput">typeInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.id">id</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.type">type</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient">DataOpsgenieEscalationRulesRecipient</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `idInput`<sup>Optional</sup> <a name="idInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.idInput"></a>

```java
public java.lang.String getIdInput();
```

- *Type:* java.lang.String

---

##### `typeInput`<sup>Optional</sup> <a name="typeInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.typeInput"></a>

```java
public java.lang.String getTypeInput();
```

- *Type:* java.lang.String

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.id"></a>

```java
public java.lang.String getId();
```

- *Type:* java.lang.String

---

##### `type`<sup>Required</sup> <a name="type" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.type"></a>

```java
public java.lang.String getType();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipientOutputReference.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieEscalation.DataOpsgenieEscalationRulesRecipient">DataOpsgenieEscalationRulesRecipient</a>

---



