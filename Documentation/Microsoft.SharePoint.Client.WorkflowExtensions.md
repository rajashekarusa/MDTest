# WorkflowExtensions
Class for deprecated workflow extension methods
**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
**Assembly:** OfficeDevPnP.Core.dll
## Classes
System.Object
## Syntax
```C#
public class WorkflowExtensions```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [GetWorkflowSubscription(Web, String)](WorkflowExtensionsGetWorkflowSubscriptionWebString.md) | Returns a workflow subscription for a site.
| [GetWorkflowSubscription(Web, Guid)](WorkflowExtensionsGetWorkflowSubscriptionWebGuid.md) | Returns a workflow subscription
| [GetWorkflowSubscription(List, String)](WorkflowExtensionsGetWorkflowSubscriptionListString.md) | Returns a workflow subscription (associations) for a list
| [GetWorkflowSubscriptions(Web)](WorkflowExtensionsGetWorkflowSubscriptionsWeb.md) | Returns all the workflow subscriptions (associations) for the web and the lists of that web
| [AddWorkflowSubscription(List, String, String, Boolean, Boolean, Boolean, String, String, Collections.Generic.Dictionary2<String,String>)](WorkflowExtensionsAddWorkflowSubscriptionListStringStringBooleanBooleanBooleanStringStringCollections.Generic.Dictionary2<String,String>.md) | 
| [AddWorkflowSubscription(List, WorkflowServices.WorkflowDefinition, String, Boolean, Boolean, Boolean, String, String, Collections.Generic.Dictionary2<String,String>)](WorkflowExtensionsAddWorkflowSubscriptionListWorkflowServices.WorkflowDefinitionStringBooleanBooleanBooleanStringStringCollections.Generic.Dictionary2<String,String>.md) | 
| [Delete(WorkflowServices.WorkflowSubscription)](WorkflowExtensionsDeleteWorkflowServices.WorkflowSubscription.md) | Deletes the subscription
| [GetWorkflowDefinition(Web, String, Boolean)](WorkflowExtensionsGetWorkflowDefinitionWebStringBoolean.md) | Returns a workflow definition for a site
| [GetWorkflowDefinition(Web, Guid)](WorkflowExtensionsGetWorkflowDefinitionWebGuid.md) | Returns a workflow definition
| [GetWorkflowDefinitions(Web, Boolean)](WorkflowExtensionsGetWorkflowDefinitionsWebBoolean.md) | Returns all the workflow definitions
| [AddWorkflowDefinition(Web, WorkflowServices.WorkflowDefinition, Boolean)](WorkflowExtensionsAddWorkflowDefinitionWebWorkflowServices.WorkflowDefinitionBoolean.md) | 
| [Delete(WorkflowServices.WorkflowDefinition)](WorkflowExtensionsDeleteWorkflowServices.WorkflowDefinition.md) | Deletes a workflow definition
| [GetWorkflowInstances(Web)](WorkflowExtensionsGetWorkflowInstancesWeb.md) | Returns alls workflow instances for a site
| [GetWorkflowInstances(Web, ListItem)](WorkflowExtensionsGetWorkflowInstancesWebListItem.md) | Returns alls workflow instances for a list item
| [GetInstances(WorkflowServices.WorkflowSubscription)](WorkflowExtensionsGetInstancesWorkflowServices.WorkflowSubscription.md) | Returns all instances of a workflow for this subscription
| [CancelWorkFlow(WorkflowServices.WorkflowInstance)](WorkflowExtensionsCancelWorkFlowWorkflowServices.WorkflowInstance.md) | Cancels a workflow instance
| [ResumeWorkflow(WorkflowServices.WorkflowInstance)](WorkflowExtensionsResumeWorkflowWorkflowServices.WorkflowInstance.md) | Resumes a workflow
| [PublishCustomEvent(WorkflowServices.WorkflowInstance, String, String)](WorkflowExtensionsPublishCustomEventWorkflowServices.WorkflowInstanceStringString.md) | Publish a custom event to a target workflow instance
| [StartWorkflowInstance(Web, String, Collections.Generic.IDictionary2<String,Object>)](WorkflowExtensionsStartWorkflowInstanceWebStringCollections.Generic.IDictionary2<String,Object>.md) | 
| [StartWorkflowInstance(Web, Guid, Collections.Generic.IDictionary2<String,Object>)](WorkflowExtensionsStartWorkflowInstanceWebGuidCollections.Generic.IDictionary2<String,Object>.md) | 
| [StartWorkflowInstance(ListItem, String, Collections.Generic.IDictionary2<String,Object>)](WorkflowExtensionsStartWorkflowInstanceListItemStringCollections.Generic.IDictionary2<String,Object>.md) | 
| [StartWorkflowInstance(ListItem, Guid, Collections.Generic.IDictionary2<String,Object>)](WorkflowExtensionsStartWorkflowInstanceListItemGuidCollections.Generic.IDictionary2<String,Object>.md) | 
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
