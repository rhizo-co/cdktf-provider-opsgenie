# `opsgenie_service_incident_rule`

Refer to the Terraform Registory for docs: [`opsgenie_service_incident_rule`](https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule).

# `serviceIncidentRule` Submodule <a name="`serviceIncidentRule` Submodule" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### ServiceIncidentRule <a name="ServiceIncidentRule" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule"></a>

Represents a {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule opsgenie_service_incident_rule}.

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.service_incident_rule.ServiceIncidentRule;

ServiceIncidentRule.Builder.create(Construct scope, java.lang.String id)
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
    .incidentRule(IResolvable)
    .incidentRule(java.util.List<ServiceIncidentRuleIncidentRule>)
    .serviceId(java.lang.String)
//  .id(java.lang.String)
    .build();
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.scope">scope</a></code> | <code>software.constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.id">id</a></code> | <code>java.lang.String</code> | The scoped construct ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.connection">connection</a></code> | <code>com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.count">count</a></code> | <code>java.lang.Number OR com.hashicorp.cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.dependsOn">dependsOn</a></code> | <code>java.util.List<com.hashicorp.cdktf.ITerraformDependable></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.forEach">forEach</a></code> | <code>com.hashicorp.cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.lifecycle">lifecycle</a></code> | <code>com.hashicorp.cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.provider">provider</a></code> | <code>com.hashicorp.cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.provisioners">provisioners</a></code> | <code>java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.incidentRule">incidentRule</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule">ServiceIncidentRuleIncidentRule</a>></code> | incident_rule block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.serviceId">serviceId</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#service_id ServiceIncidentRule#service_id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.id">id</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#id ServiceIncidentRule#id}. |

---

##### `scope`<sup>Required</sup> <a name="scope" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.scope"></a>

- *Type:* software.constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.id"></a>

- *Type:* java.lang.String

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.connection"></a>

- *Type:* com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.count"></a>

- *Type:* java.lang.Number OR com.hashicorp.cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.dependsOn"></a>

- *Type:* java.util.List<com.hashicorp.cdktf.ITerraformDependable>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.forEach"></a>

- *Type:* com.hashicorp.cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.lifecycle"></a>

- *Type:* com.hashicorp.cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.provider"></a>

- *Type:* com.hashicorp.cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.provisioners"></a>

- *Type:* java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner>

---

##### `incidentRule`<sup>Required</sup> <a name="incidentRule" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.incidentRule"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule">ServiceIncidentRuleIncidentRule</a>>

incident_rule block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#incident_rule ServiceIncidentRule#incident_rule}

---

##### `serviceId`<sup>Required</sup> <a name="serviceId" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.serviceId"></a>

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#service_id ServiceIncidentRule#service_id}.

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.Initializer.parameter.id"></a>

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#id ServiceIncidentRule#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

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

```java
public java.lang.String toString()
```

Returns a string representation of this construct.

##### `addOverride` <a name="addOverride" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.addOverride"></a>

```java
public void addOverride(java.lang.String path, java.lang.Object value)
```

###### `path`<sup>Required</sup> <a name="path" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.addOverride.parameter.path"></a>

- *Type:* java.lang.String

---

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.addOverride.parameter.value"></a>

- *Type:* java.lang.Object

---

##### `overrideLogicalId` <a name="overrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.overrideLogicalId"></a>

```java
public void overrideLogicalId(java.lang.String newLogicalId)
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* java.lang.String

The new logical ID to use for this stack element.

---

##### `resetOverrideLogicalId` <a name="resetOverrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.resetOverrideLogicalId"></a>

```java
public void resetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `toMetadata` <a name="toMetadata" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.toMetadata"></a>

```java
public java.lang.Object toMetadata()
```

##### `toTerraform` <a name="toTerraform" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.toTerraform"></a>

```java
public java.lang.Object toTerraform()
```

Adds this resource to the terraform JSON output.

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `putIncidentRule` <a name="putIncidentRule" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.putIncidentRule"></a>

```java
public void putIncidentRule(IResolvable OR java.util.List<ServiceIncidentRuleIncidentRule> value)
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.putIncidentRule.parameter.value"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule">ServiceIncidentRuleIncidentRule</a>>

---

##### `resetId` <a name="resetId" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.resetId"></a>

```java
public void resetId()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isConstruct">isConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isTerraformElement">isTerraformElement</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isTerraformResource">isTerraformResource</a></code> | *No description.* |

---

##### `isConstruct` <a name="isConstruct" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isConstruct"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.service_incident_rule.ServiceIncidentRule;

ServiceIncidentRule.isConstruct(java.lang.Object x)
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

- *Type:* java.lang.Object

Any object.

---

##### `isTerraformElement` <a name="isTerraformElement" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isTerraformElement"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.service_incident_rule.ServiceIncidentRule;

ServiceIncidentRule.isTerraformElement(java.lang.Object x)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isTerraformElement.parameter.x"></a>

- *Type:* java.lang.Object

---

##### `isTerraformResource` <a name="isTerraformResource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isTerraformResource"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.service_incident_rule.ServiceIncidentRule;

ServiceIncidentRule.isTerraformResource(java.lang.Object x)
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.isTerraformResource.parameter.x"></a>

- *Type:* java.lang.Object

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.node">node</a></code> | <code>software.constructs.Node</code> | The tree node. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.cdktfStack">cdktfStack</a></code> | <code>com.hashicorp.cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.friendlyUniqueId">friendlyUniqueId</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.terraformMetaArguments">terraformMetaArguments</a></code> | <code>java.util.Map<java.lang.String, java.lang.Object></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.terraformResourceType">terraformResourceType</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.terraformGeneratorMetadata">terraformGeneratorMetadata</a></code> | <code>com.hashicorp.cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.connection">connection</a></code> | <code>com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.count">count</a></code> | <code>java.lang.Number OR com.hashicorp.cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.dependsOn">dependsOn</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.forEach">forEach</a></code> | <code>com.hashicorp.cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.lifecycle">lifecycle</a></code> | <code>com.hashicorp.cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.provider">provider</a></code> | <code>com.hashicorp.cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.provisioners">provisioners</a></code> | <code>java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.incidentRule">incidentRule</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList">ServiceIncidentRuleIncidentRuleList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.idInput">idInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.incidentRuleInput">incidentRuleInput</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule">ServiceIncidentRuleIncidentRule</a>></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.serviceIdInput">serviceIdInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.id">id</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.serviceId">serviceId</a></code> | <code>java.lang.String</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.node"></a>

```java
public Node getNode();
```

- *Type:* software.constructs.Node

The tree node.

---

##### `cdktfStack`<sup>Required</sup> <a name="cdktfStack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.cdktfStack"></a>

```java
public TerraformStack getCdktfStack();
```

- *Type:* com.hashicorp.cdktf.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `friendlyUniqueId`<sup>Required</sup> <a name="friendlyUniqueId" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.friendlyUniqueId"></a>

```java
public java.lang.String getFriendlyUniqueId();
```

- *Type:* java.lang.String

---

##### `terraformMetaArguments`<sup>Required</sup> <a name="terraformMetaArguments" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.terraformMetaArguments"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getTerraformMetaArguments();
```

- *Type:* java.util.Map<java.lang.String, java.lang.Object>

---

##### `terraformResourceType`<sup>Required</sup> <a name="terraformResourceType" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.terraformResourceType"></a>

```java
public java.lang.String getTerraformResourceType();
```

- *Type:* java.lang.String

---

##### `terraformGeneratorMetadata`<sup>Optional</sup> <a name="terraformGeneratorMetadata" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.terraformGeneratorMetadata"></a>

```java
public TerraformProviderGeneratorMetadata getTerraformGeneratorMetadata();
```

- *Type:* com.hashicorp.cdktf.TerraformProviderGeneratorMetadata

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.connection"></a>

```java
public java.lang.Object getConnection();
```

- *Type:* com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.count"></a>

```java
public java.lang.Object getCount();
```

- *Type:* java.lang.Number OR com.hashicorp.cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.dependsOn"></a>

```java
public java.util.List<java.lang.String> getDependsOn();
```

- *Type:* java.util.List<java.lang.String>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.forEach"></a>

```java
public ITerraformIterator getForEach();
```

- *Type:* com.hashicorp.cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.lifecycle"></a>

```java
public TerraformResourceLifecycle getLifecycle();
```

- *Type:* com.hashicorp.cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.provider"></a>

```java
public TerraformProvider getProvider();
```

- *Type:* com.hashicorp.cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.provisioners"></a>

```java
public java.lang.Object getProvisioners();
```

- *Type:* java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner>

---

##### `incidentRule`<sup>Required</sup> <a name="incidentRule" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.incidentRule"></a>

```java
public ServiceIncidentRuleIncidentRuleList getIncidentRule();
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList">ServiceIncidentRuleIncidentRuleList</a>

---

##### `idInput`<sup>Optional</sup> <a name="idInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.idInput"></a>

```java
public java.lang.String getIdInput();
```

- *Type:* java.lang.String

---

##### `incidentRuleInput`<sup>Optional</sup> <a name="incidentRuleInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.incidentRuleInput"></a>

```java
public java.lang.Object getIncidentRuleInput();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule">ServiceIncidentRuleIncidentRule</a>>

---

##### `serviceIdInput`<sup>Optional</sup> <a name="serviceIdInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.serviceIdInput"></a>

```java
public java.lang.String getServiceIdInput();
```

- *Type:* java.lang.String

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.id"></a>

```java
public java.lang.String getId();
```

- *Type:* java.lang.String

---

##### `serviceId`<sup>Required</sup> <a name="serviceId" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.serviceId"></a>

```java
public java.lang.String getServiceId();
```

- *Type:* java.lang.String

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.tfResourceType">tfResourceType</a></code> | <code>java.lang.String</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRule.property.tfResourceType"></a>

```java
public java.lang.String getTfResourceType();
```

- *Type:* java.lang.String

---

## Structs <a name="Structs" id="Structs"></a>

### ServiceIncidentRuleConfig <a name="ServiceIncidentRuleConfig" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.service_incident_rule.ServiceIncidentRuleConfig;

ServiceIncidentRuleConfig.builder()
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
    .incidentRule(IResolvable)
    .incidentRule(java.util.List<ServiceIncidentRuleIncidentRule>)
    .serviceId(java.lang.String)
//  .id(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.connection">connection</a></code> | <code>com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.count">count</a></code> | <code>java.lang.Number OR com.hashicorp.cdktf.TerraformCount</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.dependsOn">dependsOn</a></code> | <code>java.util.List<com.hashicorp.cdktf.ITerraformDependable></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.forEach">forEach</a></code> | <code>com.hashicorp.cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.lifecycle">lifecycle</a></code> | <code>com.hashicorp.cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.provider">provider</a></code> | <code>com.hashicorp.cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.provisioners">provisioners</a></code> | <code>java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.incidentRule">incidentRule</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule">ServiceIncidentRuleIncidentRule</a>></code> | incident_rule block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.serviceId">serviceId</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#service_id ServiceIncidentRule#service_id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.id">id</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#id ServiceIncidentRule#id}. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.connection"></a>

```java
public java.lang.Object getConnection();
```

- *Type:* com.hashicorp.cdktf.SSHProvisionerConnection OR com.hashicorp.cdktf.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.count"></a>

```java
public java.lang.Object getCount();
```

- *Type:* java.lang.Number OR com.hashicorp.cdktf.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.dependsOn"></a>

```java
public java.util.List<ITerraformDependable> getDependsOn();
```

- *Type:* java.util.List<com.hashicorp.cdktf.ITerraformDependable>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.forEach"></a>

```java
public ITerraformIterator getForEach();
```

- *Type:* com.hashicorp.cdktf.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.lifecycle"></a>

```java
public TerraformResourceLifecycle getLifecycle();
```

- *Type:* com.hashicorp.cdktf.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.provider"></a>

```java
public TerraformProvider getProvider();
```

- *Type:* com.hashicorp.cdktf.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.provisioners"></a>

```java
public java.lang.Object getProvisioners();
```

- *Type:* java.util.List<com.hashicorp.cdktf.FileProvisioner OR com.hashicorp.cdktf.LocalExecProvisioner OR com.hashicorp.cdktf.RemoteExecProvisioner>

---

##### `incidentRule`<sup>Required</sup> <a name="incidentRule" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.incidentRule"></a>

```java
public java.lang.Object getIncidentRule();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule">ServiceIncidentRuleIncidentRule</a>>

incident_rule block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#incident_rule ServiceIncidentRule#incident_rule}

---

##### `serviceId`<sup>Required</sup> <a name="serviceId" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.serviceId"></a>

```java
public java.lang.String getServiceId();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#service_id ServiceIncidentRule#service_id}.

---

##### `id`<sup>Optional</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleConfig.property.id"></a>

```java
public java.lang.String getId();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#id ServiceIncidentRule#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

### ServiceIncidentRuleIncidentRule <a name="ServiceIncidentRuleIncidentRule" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.service_incident_rule.ServiceIncidentRuleIncidentRule;

ServiceIncidentRuleIncidentRule.builder()
    .incidentProperties(IResolvable)
    .incidentProperties(java.util.List<ServiceIncidentRuleIncidentRuleIncidentProperties>)
//  .conditionMatchType(java.lang.String)
//  .conditions(IResolvable)
//  .conditions(java.util.List<ServiceIncidentRuleIncidentRuleConditions>)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule.property.incidentProperties">incidentProperties</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties">ServiceIncidentRuleIncidentRuleIncidentProperties</a>></code> | incident_properties block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule.property.conditionMatchType">conditionMatchType</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#condition_match_type ServiceIncidentRule#condition_match_type}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule.property.conditions">conditions</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions">ServiceIncidentRuleIncidentRuleConditions</a>></code> | conditions block. |

---

##### `incidentProperties`<sup>Required</sup> <a name="incidentProperties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule.property.incidentProperties"></a>

```java
public java.lang.Object getIncidentProperties();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties">ServiceIncidentRuleIncidentRuleIncidentProperties</a>>

incident_properties block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#incident_properties ServiceIncidentRule#incident_properties}

---

##### `conditionMatchType`<sup>Optional</sup> <a name="conditionMatchType" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule.property.conditionMatchType"></a>

```java
public java.lang.String getConditionMatchType();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#condition_match_type ServiceIncidentRule#condition_match_type}.

---

##### `conditions`<sup>Optional</sup> <a name="conditions" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule.property.conditions"></a>

```java
public java.lang.Object getConditions();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions">ServiceIncidentRuleIncidentRuleConditions</a>>

conditions block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#conditions ServiceIncidentRule#conditions}

---

### ServiceIncidentRuleIncidentRuleConditions <a name="ServiceIncidentRuleIncidentRuleConditions" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.service_incident_rule.ServiceIncidentRuleIncidentRuleConditions;

ServiceIncidentRuleIncidentRuleConditions.builder()
    .field(java.lang.String)
    .operation(java.lang.String)
//  .expectedValue(java.lang.String)
//  .key(java.lang.String)
//  .not(java.lang.Boolean)
//  .not(IResolvable)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.field">field</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#field ServiceIncidentRule#field}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.operation">operation</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#operation ServiceIncidentRule#operation}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.expectedValue">expectedValue</a></code> | <code>java.lang.String</code> | User defined value that will be compared with alert field according to the operation. Default value is empty string. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.key">key</a></code> | <code>java.lang.String</code> | If 'field' is set as 'extra-properties', key could be used for key-value pair. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.not">not</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | Indicates behaviour of the given operation. Default value is false. |

---

##### `field`<sup>Required</sup> <a name="field" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.field"></a>

```java
public java.lang.String getField();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#field ServiceIncidentRule#field}.

---

##### `operation`<sup>Required</sup> <a name="operation" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.operation"></a>

```java
public java.lang.String getOperation();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#operation ServiceIncidentRule#operation}.

---

##### `expectedValue`<sup>Optional</sup> <a name="expectedValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.expectedValue"></a>

```java
public java.lang.String getExpectedValue();
```

- *Type:* java.lang.String

User defined value that will be compared with alert field according to the operation. Default value is empty string.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#expected_value ServiceIncidentRule#expected_value}

---

##### `key`<sup>Optional</sup> <a name="key" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.key"></a>

```java
public java.lang.String getKey();
```

- *Type:* java.lang.String

If 'field' is set as 'extra-properties', key could be used for key-value pair.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#key ServiceIncidentRule#key}

---

##### `not`<sup>Optional</sup> <a name="not" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions.property.not"></a>

```java
public java.lang.Object getNot();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

Indicates behaviour of the given operation. Default value is false.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#not ServiceIncidentRule#not}

---

### ServiceIncidentRuleIncidentRuleIncidentProperties <a name="ServiceIncidentRuleIncidentRuleIncidentProperties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.service_incident_rule.ServiceIncidentRuleIncidentRuleIncidentProperties;

ServiceIncidentRuleIncidentRuleIncidentProperties.builder()
    .message(java.lang.String)
    .priority(java.lang.String)
    .stakeholderProperties(IResolvable)
    .stakeholderProperties(java.util.List<ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties>)
//  .description(java.lang.String)
//  .details(java.util.Map<java.lang.String, java.lang.String>)
//  .tags(java.util.List<java.lang.String>)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.message">message</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#message ServiceIncidentRule#message}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.priority">priority</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#priority ServiceIncidentRule#priority}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.stakeholderProperties">stakeholderProperties</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties">ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties</a>></code> | stakeholder_properties block. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.description">description</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#description ServiceIncidentRule#description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.details">details</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#details ServiceIncidentRule#details}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.tags">tags</a></code> | <code>java.util.List<java.lang.String></code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#tags ServiceIncidentRule#tags}. |

---

##### `message`<sup>Required</sup> <a name="message" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.message"></a>

```java
public java.lang.String getMessage();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#message ServiceIncidentRule#message}.

---

##### `priority`<sup>Required</sup> <a name="priority" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.priority"></a>

```java
public java.lang.String getPriority();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#priority ServiceIncidentRule#priority}.

---

##### `stakeholderProperties`<sup>Required</sup> <a name="stakeholderProperties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.stakeholderProperties"></a>

```java
public java.lang.Object getStakeholderProperties();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties">ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties</a>>

stakeholder_properties block.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#stakeholder_properties ServiceIncidentRule#stakeholder_properties}

---

##### `description`<sup>Optional</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.description"></a>

```java
public java.lang.String getDescription();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#description ServiceIncidentRule#description}.

---

##### `details`<sup>Optional</sup> <a name="details" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.details"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getDetails();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#details ServiceIncidentRule#details}.

---

##### `tags`<sup>Optional</sup> <a name="tags" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties.property.tags"></a>

```java
public java.util.List<java.lang.String> getTags();
```

- *Type:* java.util.List<java.lang.String>

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#tags ServiceIncidentRule#tags}.

---

### ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties <a name="ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.service_incident_rule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties;

ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties.builder()
    .message(java.lang.String)
//  .description(java.lang.String)
//  .enable(java.lang.Boolean)
//  .enable(IResolvable)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties.property.message">message</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#message ServiceIncidentRule#message}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties.property.description">description</a></code> | <code>java.lang.String</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#description ServiceIncidentRule#description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties.property.enable">enable</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#enable ServiceIncidentRule#enable}. |

---

##### `message`<sup>Required</sup> <a name="message" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties.property.message"></a>

```java
public java.lang.String getMessage();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#message ServiceIncidentRule#message}.

---

##### `description`<sup>Optional</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties.property.description"></a>

```java
public java.lang.String getDescription();
```

- *Type:* java.lang.String

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#description ServiceIncidentRule#description}.

---

##### `enable`<sup>Optional</sup> <a name="enable" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties.property.enable"></a>

```java
public java.lang.Object getEnable();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/resources/service_incident_rule#enable ServiceIncidentRule#enable}.

---

## Classes <a name="Classes" id="Classes"></a>

### ServiceIncidentRuleIncidentRuleConditionsList <a name="ServiceIncidentRuleIncidentRuleConditionsList" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.service_incident_rule.ServiceIncidentRuleIncidentRuleConditionsList;

new ServiceIncidentRuleIncidentRuleConditionsList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.get"></a>

```java
public ServiceIncidentRuleIncidentRuleConditionsOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions">ServiceIncidentRuleIncidentRuleConditions</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions">ServiceIncidentRuleIncidentRuleConditions</a>>

---


### ServiceIncidentRuleIncidentRuleConditionsOutputReference <a name="ServiceIncidentRuleIncidentRuleConditionsOutputReference" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.service_incident_rule.ServiceIncidentRuleIncidentRuleConditionsOutputReference;

new ServiceIncidentRuleIncidentRuleConditionsOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetExpectedValue` <a name="resetExpectedValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.resetExpectedValue"></a>

```java
public void resetExpectedValue()
```

##### `resetKey` <a name="resetKey" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.resetKey"></a>

```java
public void resetKey()
```

##### `resetNot` <a name="resetNot" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.resetNot"></a>

```java
public void resetNot()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.expectedValueInput">expectedValueInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.fieldInput">fieldInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.keyInput">keyInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.notInput">notInput</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.operationInput">operationInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.expectedValue">expectedValue</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.field">field</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.key">key</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.not">not</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.operation">operation</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions">ServiceIncidentRuleIncidentRuleConditions</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `expectedValueInput`<sup>Optional</sup> <a name="expectedValueInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.expectedValueInput"></a>

```java
public java.lang.String getExpectedValueInput();
```

- *Type:* java.lang.String

---

##### `fieldInput`<sup>Optional</sup> <a name="fieldInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.fieldInput"></a>

```java
public java.lang.String getFieldInput();
```

- *Type:* java.lang.String

---

##### `keyInput`<sup>Optional</sup> <a name="keyInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.keyInput"></a>

```java
public java.lang.String getKeyInput();
```

- *Type:* java.lang.String

---

##### `notInput`<sup>Optional</sup> <a name="notInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.notInput"></a>

```java
public java.lang.Object getNotInput();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

---

##### `operationInput`<sup>Optional</sup> <a name="operationInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.operationInput"></a>

```java
public java.lang.String getOperationInput();
```

- *Type:* java.lang.String

---

##### `expectedValue`<sup>Required</sup> <a name="expectedValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.expectedValue"></a>

```java
public java.lang.String getExpectedValue();
```

- *Type:* java.lang.String

---

##### `field`<sup>Required</sup> <a name="field" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.field"></a>

```java
public java.lang.String getField();
```

- *Type:* java.lang.String

---

##### `key`<sup>Required</sup> <a name="key" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.key"></a>

```java
public java.lang.String getKey();
```

- *Type:* java.lang.String

---

##### `not`<sup>Required</sup> <a name="not" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.not"></a>

```java
public java.lang.Object getNot();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

---

##### `operation`<sup>Required</sup> <a name="operation" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.operation"></a>

```java
public java.lang.String getOperation();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsOutputReference.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions">ServiceIncidentRuleIncidentRuleConditions</a>

---


### ServiceIncidentRuleIncidentRuleIncidentPropertiesList <a name="ServiceIncidentRuleIncidentRuleIncidentPropertiesList" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.service_incident_rule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList;

new ServiceIncidentRuleIncidentRuleIncidentPropertiesList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.get"></a>

```java
public ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties">ServiceIncidentRuleIncidentRuleIncidentProperties</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties">ServiceIncidentRuleIncidentRuleIncidentProperties</a>>

---


### ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference <a name="ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.service_incident_rule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference;

new ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `putStakeholderProperties` <a name="putStakeholderProperties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.putStakeholderProperties"></a>

```java
public void putStakeholderProperties(IResolvable OR java.util.List<ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties> value)
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.putStakeholderProperties.parameter.value"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties">ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties</a>>

---

##### `resetDescription` <a name="resetDescription" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.resetDescription"></a>

```java
public void resetDescription()
```

##### `resetDetails` <a name="resetDetails" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.resetDetails"></a>

```java
public void resetDetails()
```

##### `resetTags` <a name="resetTags" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.resetTags"></a>

```java
public void resetTags()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.stakeholderProperties">stakeholderProperties</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList">ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.descriptionInput">descriptionInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.detailsInput">detailsInput</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.messageInput">messageInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.priorityInput">priorityInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.stakeholderPropertiesInput">stakeholderPropertiesInput</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties">ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties</a>></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.tagsInput">tagsInput</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.description">description</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.details">details</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.message">message</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.priority">priority</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.tags">tags</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties">ServiceIncidentRuleIncidentRuleIncidentProperties</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `stakeholderProperties`<sup>Required</sup> <a name="stakeholderProperties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.stakeholderProperties"></a>

```java
public ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList getStakeholderProperties();
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList">ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList</a>

---

##### `descriptionInput`<sup>Optional</sup> <a name="descriptionInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.descriptionInput"></a>

```java
public java.lang.String getDescriptionInput();
```

- *Type:* java.lang.String

---

##### `detailsInput`<sup>Optional</sup> <a name="detailsInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.detailsInput"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getDetailsInput();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

---

##### `messageInput`<sup>Optional</sup> <a name="messageInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.messageInput"></a>

```java
public java.lang.String getMessageInput();
```

- *Type:* java.lang.String

---

##### `priorityInput`<sup>Optional</sup> <a name="priorityInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.priorityInput"></a>

```java
public java.lang.String getPriorityInput();
```

- *Type:* java.lang.String

---

##### `stakeholderPropertiesInput`<sup>Optional</sup> <a name="stakeholderPropertiesInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.stakeholderPropertiesInput"></a>

```java
public java.lang.Object getStakeholderPropertiesInput();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties">ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties</a>>

---

##### `tagsInput`<sup>Optional</sup> <a name="tagsInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.tagsInput"></a>

```java
public java.util.List<java.lang.String> getTagsInput();
```

- *Type:* java.util.List<java.lang.String>

---

##### `description`<sup>Required</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.description"></a>

```java
public java.lang.String getDescription();
```

- *Type:* java.lang.String

---

##### `details`<sup>Required</sup> <a name="details" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.details"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getDetails();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

---

##### `message`<sup>Required</sup> <a name="message" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.message"></a>

```java
public java.lang.String getMessage();
```

- *Type:* java.lang.String

---

##### `priority`<sup>Required</sup> <a name="priority" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.priority"></a>

```java
public java.lang.String getPriority();
```

- *Type:* java.lang.String

---

##### `tags`<sup>Required</sup> <a name="tags" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.tags"></a>

```java
public java.util.List<java.lang.String> getTags();
```

- *Type:* java.util.List<java.lang.String>

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesOutputReference.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties">ServiceIncidentRuleIncidentRuleIncidentProperties</a>

---


### ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList <a name="ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.service_incident_rule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList;

new ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.get"></a>

```java
public ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties">ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesList.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties">ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties</a>>

---


### ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference <a name="ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.service_incident_rule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference;

new ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `resetDescription` <a name="resetDescription" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.resetDescription"></a>

```java
public void resetDescription()
```

##### `resetEnable` <a name="resetEnable" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.resetEnable"></a>

```java
public void resetEnable()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.descriptionInput">descriptionInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.enableInput">enableInput</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.messageInput">messageInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.description">description</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.enable">enable</a></code> | <code>java.lang.Boolean OR com.hashicorp.cdktf.IResolvable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.message">message</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties">ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `descriptionInput`<sup>Optional</sup> <a name="descriptionInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.descriptionInput"></a>

```java
public java.lang.String getDescriptionInput();
```

- *Type:* java.lang.String

---

##### `enableInput`<sup>Optional</sup> <a name="enableInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.enableInput"></a>

```java
public java.lang.Object getEnableInput();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

---

##### `messageInput`<sup>Optional</sup> <a name="messageInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.messageInput"></a>

```java
public java.lang.String getMessageInput();
```

- *Type:* java.lang.String

---

##### `description`<sup>Required</sup> <a name="description" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.description"></a>

```java
public java.lang.String getDescription();
```

- *Type:* java.lang.String

---

##### `enable`<sup>Required</sup> <a name="enable" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.enable"></a>

```java
public java.lang.Object getEnable();
```

- *Type:* java.lang.Boolean OR com.hashicorp.cdktf.IResolvable

---

##### `message`<sup>Required</sup> <a name="message" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.message"></a>

```java
public java.lang.String getMessage();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderPropertiesOutputReference.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties">ServiceIncidentRuleIncidentRuleIncidentPropertiesStakeholderProperties</a>

---


### ServiceIncidentRuleIncidentRuleList <a name="ServiceIncidentRuleIncidentRuleList" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.service_incident_rule.ServiceIncidentRuleIncidentRuleList;

new ServiceIncidentRuleIncidentRuleList(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Boolean wrapsSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.Initializer.parameter.wrapsSet">wrapsSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `wrapsSet`<sup>Required</sup> <a name="wrapsSet" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.Initializer.parameter.wrapsSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `get` <a name="get" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.get"></a>

```java
public ServiceIncidentRuleIncidentRuleOutputReference get(java.lang.Number index)
```

###### `index`<sup>Required</sup> <a name="index" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.get.parameter.index"></a>

- *Type:* java.lang.Number

the index of the item to return.

---


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule">ServiceIncidentRuleIncidentRule</a>></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleList.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule">ServiceIncidentRuleIncidentRule</a>>

---


### ServiceIncidentRuleIncidentRuleOutputReference <a name="ServiceIncidentRuleIncidentRuleOutputReference" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference"></a>

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer"></a>

```java
import com.hashicorp.cdktf.providers.opsgenie.service_incident_rule.ServiceIncidentRuleIncidentRuleOutputReference;

new ServiceIncidentRuleIncidentRuleOutputReference(IInterpolatingParent terraformResource, java.lang.String terraformAttribute, java.lang.Number complexObjectIndex, java.lang.Boolean complexObjectIsFromSet);
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.terraformResource">terraformResource</a></code> | <code>com.hashicorp.cdktf.IInterpolatingParent</code> | The parent resource. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.terraformAttribute">terraformAttribute</a></code> | <code>java.lang.String</code> | The attribute on the parent resource this class is referencing. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.complexObjectIndex">complexObjectIndex</a></code> | <code>java.lang.Number</code> | the index of this item in the list. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.complexObjectIsFromSet">complexObjectIsFromSet</a></code> | <code>java.lang.Boolean</code> | whether the list is wrapping a set (will add tolist() to be able to access an item via an index). |

---

##### `terraformResource`<sup>Required</sup> <a name="terraformResource" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.terraformResource"></a>

- *Type:* com.hashicorp.cdktf.IInterpolatingParent

The parent resource.

---

##### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

The attribute on the parent resource this class is referencing.

---

##### `complexObjectIndex`<sup>Required</sup> <a name="complexObjectIndex" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.complexObjectIndex"></a>

- *Type:* java.lang.Number

the index of this item in the list.

---

##### `complexObjectIsFromSet`<sup>Required</sup> <a name="complexObjectIsFromSet" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.Initializer.parameter.complexObjectIsFromSet"></a>

- *Type:* java.lang.Boolean

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

```java
public java.lang.String computeFqn()
```

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String property)
```

###### `property`<sup>Required</sup> <a name="property" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.interpolationForAttribute.parameter.property"></a>

- *Type:* java.lang.String

---

##### `resolve` <a name="resolve" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.resolve"></a>

```java
public java.lang.Object resolve(IResolveContext _context)
```

Produce the Token's value at resolution time.

###### `_context`<sup>Required</sup> <a name="_context" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.resolve.parameter._context"></a>

- *Type:* com.hashicorp.cdktf.IResolveContext

---

##### `toString` <a name="toString" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.toString"></a>

```java
public java.lang.String toString()
```

Return a string representation of this resolvable object.

Returns a reversible string representation.

##### `putConditions` <a name="putConditions" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.putConditions"></a>

```java
public void putConditions(IResolvable OR java.util.List<ServiceIncidentRuleIncidentRuleConditions> value)
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.putConditions.parameter.value"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions">ServiceIncidentRuleIncidentRuleConditions</a>>

---

##### `putIncidentProperties` <a name="putIncidentProperties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.putIncidentProperties"></a>

```java
public void putIncidentProperties(IResolvable OR java.util.List<ServiceIncidentRuleIncidentRuleIncidentProperties> value)
```

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.putIncidentProperties.parameter.value"></a>

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties">ServiceIncidentRuleIncidentRuleIncidentProperties</a>>

---

##### `resetConditionMatchType` <a name="resetConditionMatchType" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.resetConditionMatchType"></a>

```java
public void resetConditionMatchType()
```

##### `resetConditions` <a name="resetConditions" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.resetConditions"></a>

```java
public void resetConditions()
```


#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.creationStack">creationStack</a></code> | <code>java.util.List<java.lang.String></code> | The creation stack of this resolvable which will be appended to errors thrown during resolution. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditions">conditions</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList">ServiceIncidentRuleIncidentRuleConditionsList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.incidentProperties">incidentProperties</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList">ServiceIncidentRuleIncidentRuleIncidentPropertiesList</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditionMatchTypeInput">conditionMatchTypeInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditionsInput">conditionsInput</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions">ServiceIncidentRuleIncidentRuleConditions</a>></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.incidentPropertiesInput">incidentPropertiesInput</a></code> | <code>com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties">ServiceIncidentRuleIncidentRuleIncidentProperties</a>></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditionMatchType">conditionMatchType</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.internalValue">internalValue</a></code> | <code>com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule">ServiceIncidentRuleIncidentRule</a></code> | *No description.* |

---

##### `creationStack`<sup>Required</sup> <a name="creationStack" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.creationStack"></a>

```java
public java.util.List<java.lang.String> getCreationStack();
```

- *Type:* java.util.List<java.lang.String>

The creation stack of this resolvable which will be appended to errors thrown during resolution.

If this returns an empty array the stack will not be attached.

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `conditions`<sup>Required</sup> <a name="conditions" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditions"></a>

```java
public ServiceIncidentRuleIncidentRuleConditionsList getConditions();
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditionsList">ServiceIncidentRuleIncidentRuleConditionsList</a>

---

##### `incidentProperties`<sup>Required</sup> <a name="incidentProperties" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.incidentProperties"></a>

```java
public ServiceIncidentRuleIncidentRuleIncidentPropertiesList getIncidentProperties();
```

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentPropertiesList">ServiceIncidentRuleIncidentRuleIncidentPropertiesList</a>

---

##### `conditionMatchTypeInput`<sup>Optional</sup> <a name="conditionMatchTypeInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditionMatchTypeInput"></a>

```java
public java.lang.String getConditionMatchTypeInput();
```

- *Type:* java.lang.String

---

##### `conditionsInput`<sup>Optional</sup> <a name="conditionsInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditionsInput"></a>

```java
public java.lang.Object getConditionsInput();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleConditions">ServiceIncidentRuleIncidentRuleConditions</a>>

---

##### `incidentPropertiesInput`<sup>Optional</sup> <a name="incidentPropertiesInput" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.incidentPropertiesInput"></a>

```java
public java.lang.Object getIncidentPropertiesInput();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR java.util.List<<a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleIncidentProperties">ServiceIncidentRuleIncidentRuleIncidentProperties</a>>

---

##### `conditionMatchType`<sup>Required</sup> <a name="conditionMatchType" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.conditionMatchType"></a>

```java
public java.lang.String getConditionMatchType();
```

- *Type:* java.lang.String

---

##### `internalValue`<sup>Optional</sup> <a name="internalValue" id="rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRuleOutputReference.property.internalValue"></a>

```java
public java.lang.Object getInternalValue();
```

- *Type:* com.hashicorp.cdktf.IResolvable OR <a href="#rhizo-co-terraform-provider-opsgenie.serviceIncidentRule.ServiceIncidentRuleIncidentRule">ServiceIncidentRuleIncidentRule</a>

---



