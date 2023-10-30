# `data_opsgenie_heartbeat`

Refer to the Terraform Registory for docs: [`data_opsgenie_heartbeat`](https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat).

# `dataOpsgenieHeartbeat` Submodule <a name="`dataOpsgenieHeartbeat` Submodule" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### DataOpsgenieHeartbeat <a name="DataOpsgenieHeartbeat" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat"></a>

Represents a {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat opsgenie_heartbeat}.

#### Initializers <a name="Initializers" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/dataopsgenieheartbeat"

dataopsgenieheartbeat.NewDataOpsgenieHeartbeat(scope Construct, id *string, config DataOpsgenieHeartbeatConfig) DataOpsgenieHeartbeat
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.scope">scope</a></code> | <code>github.com/aws/constructs-go/constructs/v10.Construct</code> | The scope in which to define this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.id">id</a></code> | <code>*string</code> | The scoped construct ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.config">config</a></code> | <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig">DataOpsgenieHeartbeatConfig</a></code> | *No description.* |

---

##### `scope`<sup>Required</sup> <a name="scope" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.scope"></a>

- *Type:* github.com/aws/constructs-go/constructs/v10.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.id"></a>

- *Type:* *string

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Required</sup> <a name="config" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.Initializer.parameter.config"></a>

- *Type:* <a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig">DataOpsgenieHeartbeatConfig</a>

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.toString">ToString</a></code> | Returns a string representation of this construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.addOverride">AddOverride</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.overrideLogicalId">OverrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetOverrideLogicalId">ResetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.toMetadata">ToMetadata</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.toTerraform">ToTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getAnyMapAttribute">GetAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getBooleanAttribute">GetBooleanAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getBooleanMapAttribute">GetBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getListAttribute">GetListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberAttribute">GetNumberAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberListAttribute">GetNumberListAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberMapAttribute">GetNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getStringAttribute">GetStringAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getStringMapAttribute">GetStringMapAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.interpolationForAttribute">InterpolationForAttribute</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetAlertMessage">ResetAlertMessage</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetAlertPriority">ResetAlertPriority</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetAlertTags">ResetAlertTags</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetDescription">ResetDescription</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetEnabled">ResetEnabled</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetId">ResetId</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetInterval">ResetInterval</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetIntervalUnit">ResetIntervalUnit</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetOwnerTeamId">ResetOwnerTeamId</a></code> | *No description.* |

---

##### `ToString` <a name="ToString" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.toString"></a>

```go
func ToString() *string
```

Returns a string representation of this construct.

##### `AddOverride` <a name="AddOverride" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.addOverride"></a>

```go
func AddOverride(path *string, value interface{})
```

###### `path`<sup>Required</sup> <a name="path" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.addOverride.parameter.path"></a>

- *Type:* *string

---

###### `value`<sup>Required</sup> <a name="value" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.addOverride.parameter.value"></a>

- *Type:* interface{}

---

##### `OverrideLogicalId` <a name="OverrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.overrideLogicalId"></a>

```go
func OverrideLogicalId(newLogicalId *string)
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* *string

The new logical ID to use for this stack element.

---

##### `ResetOverrideLogicalId` <a name="ResetOverrideLogicalId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetOverrideLogicalId"></a>

```go
func ResetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `ToMetadata` <a name="ToMetadata" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.toMetadata"></a>

```go
func ToMetadata() interface{}
```

##### `ToTerraform` <a name="ToTerraform" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.toTerraform"></a>

```go
func ToTerraform() interface{}
```

Adds this resource to the terraform JSON output.

##### `GetAnyMapAttribute` <a name="GetAnyMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getAnyMapAttribute"></a>

```go
func GetAnyMapAttribute(terraformAttribute *string) *map[string]interface{}
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanAttribute` <a name="GetBooleanAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getBooleanAttribute"></a>

```go
func GetBooleanAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetBooleanMapAttribute` <a name="GetBooleanMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getBooleanMapAttribute"></a>

```go
func GetBooleanMapAttribute(terraformAttribute *string) *map[string]*bool
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetListAttribute` <a name="GetListAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getListAttribute"></a>

```go
func GetListAttribute(terraformAttribute *string) *[]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberAttribute` <a name="GetNumberAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberAttribute"></a>

```go
func GetNumberAttribute(terraformAttribute *string) *f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberListAttribute` <a name="GetNumberListAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberListAttribute"></a>

```go
func GetNumberListAttribute(terraformAttribute *string) *[]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetNumberMapAttribute` <a name="GetNumberMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberMapAttribute"></a>

```go
func GetNumberMapAttribute(terraformAttribute *string) *map[string]*f64
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringAttribute` <a name="GetStringAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getStringAttribute"></a>

```go
func GetStringAttribute(terraformAttribute *string) *string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `GetStringMapAttribute` <a name="GetStringMapAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getStringMapAttribute"></a>

```go
func GetStringMapAttribute(terraformAttribute *string) *map[string]*string
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `InterpolationForAttribute` <a name="InterpolationForAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.interpolationForAttribute"></a>

```go
func InterpolationForAttribute(terraformAttribute *string) IResolvable
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* *string

---

##### `ResetAlertMessage` <a name="ResetAlertMessage" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetAlertMessage"></a>

```go
func ResetAlertMessage()
```

##### `ResetAlertPriority` <a name="ResetAlertPriority" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetAlertPriority"></a>

```go
func ResetAlertPriority()
```

##### `ResetAlertTags` <a name="ResetAlertTags" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetAlertTags"></a>

```go
func ResetAlertTags()
```

##### `ResetDescription` <a name="ResetDescription" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetDescription"></a>

```go
func ResetDescription()
```

##### `ResetEnabled` <a name="ResetEnabled" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetEnabled"></a>

```go
func ResetEnabled()
```

##### `ResetId` <a name="ResetId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetId"></a>

```go
func ResetId()
```

##### `ResetInterval` <a name="ResetInterval" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetInterval"></a>

```go
func ResetInterval()
```

##### `ResetIntervalUnit` <a name="ResetIntervalUnit" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetIntervalUnit"></a>

```go
func ResetIntervalUnit()
```

##### `ResetOwnerTeamId` <a name="ResetOwnerTeamId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.resetOwnerTeamId"></a>

```go
func ResetOwnerTeamId()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isConstruct">IsConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isTerraformElement">IsTerraformElement</a></code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isTerraformDataSource">IsTerraformDataSource</a></code> | *No description.* |

---

##### `IsConstruct` <a name="IsConstruct" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isConstruct"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/dataopsgenieheartbeat"

dataopsgenieheartbeat.DataOpsgenieHeartbeat_IsConstruct(x interface{}) *bool
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

- *Type:* interface{}

Any object.

---

##### `IsTerraformElement` <a name="IsTerraformElement" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isTerraformElement"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/dataopsgenieheartbeat"

dataopsgenieheartbeat.DataOpsgenieHeartbeat_IsTerraformElement(x interface{}) *bool
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isTerraformElement.parameter.x"></a>

- *Type:* interface{}

---

##### `IsTerraformDataSource` <a name="IsTerraformDataSource" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isTerraformDataSource"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/dataopsgenieheartbeat"

dataopsgenieheartbeat.DataOpsgenieHeartbeat_IsTerraformDataSource(x interface{}) *bool
```

###### `x`<sup>Required</sup> <a name="x" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.isTerraformDataSource.parameter.x"></a>

- *Type:* interface{}

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.node">Node</a></code> | <code>github.com/aws/constructs-go/constructs/v10.Node</code> | The tree node. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.cdktfStack">CdktfStack</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformStack</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.fqn">Fqn</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.friendlyUniqueId">FriendlyUniqueId</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.terraformMetaArguments">TerraformMetaArguments</a></code> | <code>*map[string]interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.terraformResourceType">TerraformResourceType</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.terraformGeneratorMetadata">TerraformGeneratorMetadata</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.count">Count</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.dependsOn">DependsOn</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.forEach">ForEach</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.lifecycle">Lifecycle</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.provider">Provider</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertMessageInput">AlertMessageInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertPriorityInput">AlertPriorityInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertTagsInput">AlertTagsInput</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.descriptionInput">DescriptionInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.enabledInput">EnabledInput</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.idInput">IdInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.intervalInput">IntervalInput</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.intervalUnitInput">IntervalUnitInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.nameInput">NameInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.ownerTeamIdInput">OwnerTeamIdInput</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertMessage">AlertMessage</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertPriority">AlertPriority</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertTags">AlertTags</a></code> | <code>*[]*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.description">Description</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.enabled">Enabled</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.id">Id</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.interval">Interval</a></code> | <code>*f64</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.intervalUnit">IntervalUnit</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.name">Name</a></code> | <code>*string</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.ownerTeamId">OwnerTeamId</a></code> | <code>*string</code> | *No description.* |

---

##### `Node`<sup>Required</sup> <a name="Node" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.node"></a>

```go
func Node() Node
```

- *Type:* github.com/aws/constructs-go/constructs/v10.Node

The tree node.

---

##### `CdktfStack`<sup>Required</sup> <a name="CdktfStack" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.cdktfStack"></a>

```go
func CdktfStack() TerraformStack
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformStack

---

##### `Fqn`<sup>Required</sup> <a name="Fqn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.fqn"></a>

```go
func Fqn() *string
```

- *Type:* *string

---

##### `FriendlyUniqueId`<sup>Required</sup> <a name="FriendlyUniqueId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.friendlyUniqueId"></a>

```go
func FriendlyUniqueId() *string
```

- *Type:* *string

---

##### `TerraformMetaArguments`<sup>Required</sup> <a name="TerraformMetaArguments" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.terraformMetaArguments"></a>

```go
func TerraformMetaArguments() *map[string]interface{}
```

- *Type:* *map[string]interface{}

---

##### `TerraformResourceType`<sup>Required</sup> <a name="TerraformResourceType" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.terraformResourceType"></a>

```go
func TerraformResourceType() *string
```

- *Type:* *string

---

##### `TerraformGeneratorMetadata`<sup>Optional</sup> <a name="TerraformGeneratorMetadata" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.terraformGeneratorMetadata"></a>

```go
func TerraformGeneratorMetadata() TerraformProviderGeneratorMetadata
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProviderGeneratorMetadata

---

##### `Count`<sup>Optional</sup> <a name="Count" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.count"></a>

```go
func Count() interface{}
```

- *Type:* interface{}

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.dependsOn"></a>

```go
func DependsOn() *[]*string
```

- *Type:* *[]*string

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.forEach"></a>

```go
func ForEach() ITerraformIterator
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.lifecycle"></a>

```go
func Lifecycle() TerraformResourceLifecycle
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.provider"></a>

```go
func Provider() TerraformProvider
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider

---

##### `AlertMessageInput`<sup>Optional</sup> <a name="AlertMessageInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertMessageInput"></a>

```go
func AlertMessageInput() *string
```

- *Type:* *string

---

##### `AlertPriorityInput`<sup>Optional</sup> <a name="AlertPriorityInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertPriorityInput"></a>

```go
func AlertPriorityInput() *string
```

- *Type:* *string

---

##### `AlertTagsInput`<sup>Optional</sup> <a name="AlertTagsInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertTagsInput"></a>

```go
func AlertTagsInput() *[]*string
```

- *Type:* *[]*string

---

##### `DescriptionInput`<sup>Optional</sup> <a name="DescriptionInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.descriptionInput"></a>

```go
func DescriptionInput() *string
```

- *Type:* *string

---

##### `EnabledInput`<sup>Optional</sup> <a name="EnabledInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.enabledInput"></a>

```go
func EnabledInput() interface{}
```

- *Type:* interface{}

---

##### `IdInput`<sup>Optional</sup> <a name="IdInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.idInput"></a>

```go
func IdInput() *string
```

- *Type:* *string

---

##### `IntervalInput`<sup>Optional</sup> <a name="IntervalInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.intervalInput"></a>

```go
func IntervalInput() *f64
```

- *Type:* *f64

---

##### `IntervalUnitInput`<sup>Optional</sup> <a name="IntervalUnitInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.intervalUnitInput"></a>

```go
func IntervalUnitInput() *string
```

- *Type:* *string

---

##### `NameInput`<sup>Optional</sup> <a name="NameInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.nameInput"></a>

```go
func NameInput() *string
```

- *Type:* *string

---

##### `OwnerTeamIdInput`<sup>Optional</sup> <a name="OwnerTeamIdInput" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.ownerTeamIdInput"></a>

```go
func OwnerTeamIdInput() *string
```

- *Type:* *string

---

##### `AlertMessage`<sup>Required</sup> <a name="AlertMessage" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertMessage"></a>

```go
func AlertMessage() *string
```

- *Type:* *string

---

##### `AlertPriority`<sup>Required</sup> <a name="AlertPriority" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertPriority"></a>

```go
func AlertPriority() *string
```

- *Type:* *string

---

##### `AlertTags`<sup>Required</sup> <a name="AlertTags" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.alertTags"></a>

```go
func AlertTags() *[]*string
```

- *Type:* *[]*string

---

##### `Description`<sup>Required</sup> <a name="Description" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.description"></a>

```go
func Description() *string
```

- *Type:* *string

---

##### `Enabled`<sup>Required</sup> <a name="Enabled" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.enabled"></a>

```go
func Enabled() interface{}
```

- *Type:* interface{}

---

##### `Id`<sup>Required</sup> <a name="Id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.id"></a>

```go
func Id() *string
```

- *Type:* *string

---

##### `Interval`<sup>Required</sup> <a name="Interval" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.interval"></a>

```go
func Interval() *f64
```

- *Type:* *f64

---

##### `IntervalUnit`<sup>Required</sup> <a name="IntervalUnit" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.intervalUnit"></a>

```go
func IntervalUnit() *string
```

- *Type:* *string

---

##### `Name`<sup>Required</sup> <a name="Name" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.name"></a>

```go
func Name() *string
```

- *Type:* *string

---

##### `OwnerTeamId`<sup>Required</sup> <a name="OwnerTeamId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.ownerTeamId"></a>

```go
func OwnerTeamId() *string
```

- *Type:* *string

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.tfResourceType">TfResourceType</a></code> | <code>*string</code> | *No description.* |

---

##### `TfResourceType`<sup>Required</sup> <a name="TfResourceType" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeat.property.tfResourceType"></a>

```go
func TfResourceType() *string
```

- *Type:* *string

---

## Structs <a name="Structs" id="Structs"></a>

### DataOpsgenieHeartbeatConfig <a name="DataOpsgenieHeartbeatConfig" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig"></a>

#### Initializer <a name="Initializer" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.Initializer"></a>

```go
import "github.com/rhizo-co/cdktf-provider-opsgenie-go/opsgenie/dataopsgenieheartbeat"

&dataopsgenieheartbeat.DataOpsgenieHeartbeatConfig {
	Connection: interface{},
	Count: interface{},
	DependsOn: *[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable,
	ForEach: github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator,
	Lifecycle: github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle,
	Provider: github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider,
	Provisioners: *[]interface{},
	Name: *string,
	AlertMessage: *string,
	AlertPriority: *string,
	AlertTags: *[]*string,
	Description: *string,
	Enabled: interface{},
	Id: *string,
	Interval: *f64,
	IntervalUnit: *string,
	OwnerTeamId: *string,
}
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.connection">Connection</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.count">Count</a></code> | <code>interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.dependsOn">DependsOn</a></code> | <code>*[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.forEach">ForEach</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.lifecycle">Lifecycle</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.provider">Provider</a></code> | <code>github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.provisioners">Provisioners</a></code> | <code>*[]interface{}</code> | *No description.* |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.name">Name</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#name DataOpsgenieHeartbeat#name}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.alertMessage">AlertMessage</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_message DataOpsgenieHeartbeat#alert_message}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.alertPriority">AlertPriority</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_priority DataOpsgenieHeartbeat#alert_priority}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.alertTags">AlertTags</a></code> | <code>*[]*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_tags DataOpsgenieHeartbeat#alert_tags}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.description">Description</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#description DataOpsgenieHeartbeat#description}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.enabled">Enabled</a></code> | <code>interface{}</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#enabled DataOpsgenieHeartbeat#enabled}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.id">Id</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#id DataOpsgenieHeartbeat#id}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.interval">Interval</a></code> | <code>*f64</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#interval DataOpsgenieHeartbeat#interval}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.intervalUnit">IntervalUnit</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#interval_unit DataOpsgenieHeartbeat#interval_unit}. |
| <code><a href="#rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.ownerTeamId">OwnerTeamId</a></code> | <code>*string</code> | Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#owner_team_id DataOpsgenieHeartbeat#owner_team_id}. |

---

##### `Connection`<sup>Optional</sup> <a name="Connection" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.connection"></a>

```go
Connection interface{}
```

- *Type:* interface{}

---

##### `Count`<sup>Optional</sup> <a name="Count" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.count"></a>

```go
Count interface{}
```

- *Type:* interface{}

---

##### `DependsOn`<sup>Optional</sup> <a name="DependsOn" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.dependsOn"></a>

```go
DependsOn *[]ITerraformDependable
```

- *Type:* *[]github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformDependable

---

##### `ForEach`<sup>Optional</sup> <a name="ForEach" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.forEach"></a>

```go
ForEach ITerraformIterator
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.ITerraformIterator

---

##### `Lifecycle`<sup>Optional</sup> <a name="Lifecycle" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.lifecycle"></a>

```go
Lifecycle TerraformResourceLifecycle
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformResourceLifecycle

---

##### `Provider`<sup>Optional</sup> <a name="Provider" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.provider"></a>

```go
Provider TerraformProvider
```

- *Type:* github.com/hashicorp/terraform-cdk-go/cdktf.TerraformProvider

---

##### `Provisioners`<sup>Optional</sup> <a name="Provisioners" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.provisioners"></a>

```go
Provisioners *[]interface{}
```

- *Type:* *[]interface{}

---

##### `Name`<sup>Required</sup> <a name="Name" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.name"></a>

```go
Name *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#name DataOpsgenieHeartbeat#name}.

---

##### `AlertMessage`<sup>Optional</sup> <a name="AlertMessage" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.alertMessage"></a>

```go
AlertMessage *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_message DataOpsgenieHeartbeat#alert_message}.

---

##### `AlertPriority`<sup>Optional</sup> <a name="AlertPriority" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.alertPriority"></a>

```go
AlertPriority *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_priority DataOpsgenieHeartbeat#alert_priority}.

---

##### `AlertTags`<sup>Optional</sup> <a name="AlertTags" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.alertTags"></a>

```go
AlertTags *[]*string
```

- *Type:* *[]*string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#alert_tags DataOpsgenieHeartbeat#alert_tags}.

---

##### `Description`<sup>Optional</sup> <a name="Description" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.description"></a>

```go
Description *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#description DataOpsgenieHeartbeat#description}.

---

##### `Enabled`<sup>Optional</sup> <a name="Enabled" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.enabled"></a>

```go
Enabled interface{}
```

- *Type:* interface{}

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#enabled DataOpsgenieHeartbeat#enabled}.

---

##### `Id`<sup>Optional</sup> <a name="Id" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.id"></a>

```go
Id *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#id DataOpsgenieHeartbeat#id}.

Please be aware that the id field is automatically added to all resources in Terraform providers using a Terraform provider SDK version below 2.
If you experience problems setting this value it might not be settable. Please take a look at the provider documentation to ensure it should be settable.

---

##### `Interval`<sup>Optional</sup> <a name="Interval" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.interval"></a>

```go
Interval *f64
```

- *Type:* *f64

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#interval DataOpsgenieHeartbeat#interval}.

---

##### `IntervalUnit`<sup>Optional</sup> <a name="IntervalUnit" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.intervalUnit"></a>

```go
IntervalUnit *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#interval_unit DataOpsgenieHeartbeat#interval_unit}.

---

##### `OwnerTeamId`<sup>Optional</sup> <a name="OwnerTeamId" id="rhizo-co-terraform-provider-opsgenie.dataOpsgenieHeartbeat.DataOpsgenieHeartbeatConfig.property.ownerTeamId"></a>

```go
OwnerTeamId *string
```

- *Type:* *string

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/opsgenie/opsgenie/0.6.33/docs/data-sources/heartbeat#owner_team_id DataOpsgenieHeartbeat#owner_team_id}.

---



