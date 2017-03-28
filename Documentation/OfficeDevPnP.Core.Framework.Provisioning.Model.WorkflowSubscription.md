# WorkflowSubscription
Defines a Workflow Subscription to provision  

**Namespace:** [OfficeDevPnP.Core.Framework.Provisioning.Model](OfficeDevPnP.Core.Framework.Provisioning.Model.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Classes
System.Object  
-- [OfficeDevPnP.Core.Framework.Provisioning.Model.BaseModel](OfficeDevPnP.Core.Framework.Provisioning.Model.BaseModel.md)
## Syntax
```C#
public class WorkflowSubscription: BaseModel
```
## Constructors
|**Name**|**Description**|
|:-----|:-----|
| [WorkflowSubscription()](WorkflowSubscriptionconstructor1details.md) | 
| [WorkflowSubscription(Collections.Generic.Dictionary2<String,String>)](WorkflowSubscriptionconstructor1details.md) | 
## Properties
|**Name**|**Description**|
|:-----|:-----|
| [PropertyDefinitions](WorkflowSubscription.PropertyDefinitions.md) | Defines the Property Definitions of the Workflows to provision
| [DefinitionId](WorkflowSubscription.DefinitionId.md) | Defines the ID of the Workflow Definition for the current Subscription
| [ListId](WorkflowSubscription.ListId.md) | Defines the ID of the target list/library for the current Subscription,
| [Enabled](WorkflowSubscription.Enabled.md) | Defines if the Workflow Definition is enabled for the current Subscription
| [EventSourceId](WorkflowSubscription.EventSourceId.md) | Defines the ID of the Event Source for the current Subscription
| [EventTypes](WorkflowSubscription.EventTypes.md) | Defines the list of events that will start the workflow instance
| [ManualStartBypassesActivationLimit](WorkflowSubscription.ManualStartBypassesActivationLimit.md) | Defines if the Workflow can be manually started bypassing the activation limit
| [Name](WorkflowSubscription.Name.md) | Defines the Name of the Workflow Subscription
| [ParentContentTypeId](WorkflowSubscription.ParentContentTypeId.md) | Defines the Parent ContentType Id of the Workflow Subscription
| [StatusFieldName](WorkflowSubscription.StatusFieldName.md) | Defines the Status Field Name of the Workflow Subscription
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [GetHashCode()](WorkflowSubscriptionGetHashCode.md) | 
| [Equals(Object)](WorkflowSubscriptionEqualsObject.md) | 
| [Equals(WorkflowSubscription)](WorkflowSubscriptionEqualsWorkflowSubscription.md) | 
## See also
- [OfficeDevPnP.Core.Framework.Provisioning.Model](OfficeDevPnP.Core.Framework.Provisioning.Model.md)
