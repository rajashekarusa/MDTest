# WorkflowExtensions
Class for deprecated workflow extension methods  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Inheritance Hierarchy
System.Object  
## Syntax
```C#
public static class WorkflowExtensions
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [GetWorkflowSubscription(Web, String)](Microsoft.SharePoint.Client.WorkflowExtensions.GetWorkflowSubscriptionWebString.md) | Returns a workflow subscription for a site.
| [GetWorkflowSubscription(Web, Guid)](Microsoft.SharePoint.Client.WorkflowExtensions.GetWorkflowSubscriptionWebGuid.md) | Returns a workflow subscription
| [GetWorkflowSubscription(List, String)](Microsoft.SharePoint.Client.WorkflowExtensions.GetWorkflowSubscriptionListString.md) | Returns a workflow subscription (associations) for a list
| [GetWorkflowSubscriptions(Web)](Microsoft.SharePoint.Client.WorkflowExtensions.GetWorkflowSubscriptionsWeb.md) | Returns all the workflow subscriptions (associations) for the web and the lists of that web
| [AddWorkflowSubscription(List, String, String, Boolean, Boolean, Boolean, String, String, Collections.Generic.Dictionary<String,String>)](Microsoft.SharePoint.Client.WorkflowExtensions.AddWorkflowSubscriptionListStringStringBooleanBooleanBooleanStringStringCollections.Generic.Dictionary<String,String>.md) | 
| [AddWorkflowSubscription(List, WorkflowServices.WorkflowDefinition, String, Boolean, Boolean, Boolean, String, String, Collections.Generic.Dictionary<String,String>)](Microsoft.SharePoint.Client.WorkflowExtensions.AddWorkflowSubscriptionListWorkflowServices.WorkflowDefinitionStringBooleanBooleanBooleanStringStringCollections.Generic.Dictionary<String,String>.md) | 
| [Delete(WorkflowServices.WorkflowSubscription)](Microsoft.SharePoint.Client.WorkflowExtensions.DeleteWorkflowServices.WorkflowSubscription.md) | Deletes the subscription
| [GetWorkflowDefinition(Web, String, Boolean)](Microsoft.SharePoint.Client.WorkflowExtensions.GetWorkflowDefinitionWebStringBoolean.md) | Returns a workflow definition for a site
| [GetWorkflowDefinition(Web, Guid)](Microsoft.SharePoint.Client.WorkflowExtensions.GetWorkflowDefinitionWebGuid.md) | Returns a workflow definition
| [GetWorkflowDefinitions(Web, Boolean)](Microsoft.SharePoint.Client.WorkflowExtensions.GetWorkflowDefinitionsWebBoolean.md) | Returns all the workflow definitions
| [AddWorkflowDefinition(Web, WorkflowServices.WorkflowDefinition, Boolean)](Microsoft.SharePoint.Client.WorkflowExtensions.AddWorkflowDefinitionWebWorkflowServices.WorkflowDefinitionBoolean.md) | 
| [Delete(WorkflowServices.WorkflowDefinition)](Microsoft.SharePoint.Client.WorkflowExtensions.DeleteWorkflowServices.WorkflowDefinition.md) | Deletes a workflow definition
| [GetWorkflowInstances(Web)](Microsoft.SharePoint.Client.WorkflowExtensions.GetWorkflowInstancesWeb.md) | Returns alls workflow instances for a site
| [GetWorkflowInstances(Web, ListItem)](Microsoft.SharePoint.Client.WorkflowExtensions.GetWorkflowInstancesWebListItem.md) | Returns alls workflow instances for a list item
| [GetInstances(WorkflowServices.WorkflowSubscription)](Microsoft.SharePoint.Client.WorkflowExtensions.GetInstancesWorkflowServices.WorkflowSubscription.md) | Returns all instances of a workflow for this subscription
| [CancelWorkFlow(WorkflowServices.WorkflowInstance)](Microsoft.SharePoint.Client.WorkflowExtensions.CancelWorkFlowWorkflowServices.WorkflowInstance.md) | Cancels a workflow instance
| [ResumeWorkflow(WorkflowServices.WorkflowInstance)](Microsoft.SharePoint.Client.WorkflowExtensions.ResumeWorkflowWorkflowServices.WorkflowInstance.md) | Resumes a workflow
| [PublishCustomEvent(WorkflowServices.WorkflowInstance, String, String)](Microsoft.SharePoint.Client.WorkflowExtensions.PublishCustomEventWorkflowServices.WorkflowInstanceStringString.md) | Publish a custom event to a target workflow instance
| [StartWorkflowInstance(Web, String, Collections.Generic.IDictionary<String,Object>)](Microsoft.SharePoint.Client.WorkflowExtensions.StartWorkflowInstanceWebStringCollections.Generic.IDictionary<String,Object>.md) | 
| [StartWorkflowInstance(Web, Guid, Collections.Generic.IDictionary<String,Object>)](Microsoft.SharePoint.Client.WorkflowExtensions.StartWorkflowInstanceWebGuidCollections.Generic.IDictionary<String,Object>.md) | 
| [StartWorkflowInstance(ListItem, String, Collections.Generic.IDictionary<String,Object>)](Microsoft.SharePoint.Client.WorkflowExtensions.StartWorkflowInstanceListItemStringCollections.Generic.IDictionary<String,Object>.md) | 
| [StartWorkflowInstance(ListItem, Guid, Collections.Generic.IDictionary<String,Object>)](Microsoft.SharePoint.Client.WorkflowExtensions.StartWorkflowInstanceListItemGuidCollections.Generic.IDictionary<String,Object>.md) | 
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
