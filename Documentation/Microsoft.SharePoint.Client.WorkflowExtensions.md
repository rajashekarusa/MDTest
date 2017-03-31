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
| [GetWorkflowSubscription(Web, String)](Microsoft.SharePoint.Client.WorkflowExtensions.250DCC40.md) | Returns a workflow subscription for a site.
| [GetWorkflowSubscription(Web, Guid)](Microsoft.SharePoint.Client.WorkflowExtensions.CD867166.md) | Returns a workflow subscription
| [GetWorkflowSubscription(List, String)](Microsoft.SharePoint.Client.WorkflowExtensions.7FA8D0C5.md) | Returns a workflow subscription (associations) for a list
| [GetWorkflowSubscriptions(Web)](Microsoft.SharePoint.Client.WorkflowExtensions.74365DEC.md) | Returns all the workflow subscriptions (associations) for the web and the lists of that web
| [AddWorkflowSubscription(List, String, String, Boolean, Boolean, Boolean, String, String, Dictionary<String, String>)](Microsoft.SharePoint.Client.WorkflowExtensions.DB48BC3.md) | 
| [AddWorkflowSubscription(List, WorkflowDefinition, String, Boolean, Boolean, Boolean, String, String, Dictionary<String, String>)](Microsoft.SharePoint.Client.WorkflowExtensions.22152967.md) | 
| [Delete(WorkflowSubscription)](Microsoft.SharePoint.Client.WorkflowExtensions.7B09533.md) | Deletes the subscription
| [GetWorkflowDefinition(Web, String, Boolean)](Microsoft.SharePoint.Client.WorkflowExtensions.89D3977B.md) | Returns a workflow definition for a site
| [GetWorkflowDefinition(Web, Guid)](Microsoft.SharePoint.Client.WorkflowExtensions.1A9B07C5.md) | Returns a workflow definition
| [GetWorkflowDefinitions(Web, Boolean)](Microsoft.SharePoint.Client.WorkflowExtensions.7692B016.md) | Returns all the workflow definitions
| [AddWorkflowDefinition(Web, WorkflowDefinition, Boolean)](Microsoft.SharePoint.Client.WorkflowExtensions.ED3D4BD4.md) | 
| [Delete(WorkflowDefinition)](Microsoft.SharePoint.Client.WorkflowExtensions.FA0BC740.md) | Deletes a workflow definition
| [GetWorkflowInstances(Web)](Microsoft.SharePoint.Client.WorkflowExtensions.57799136.md) | Returns alls workflow instances for a site
| [GetWorkflowInstances(Web, ListItem)](Microsoft.SharePoint.Client.WorkflowExtensions.D66B2FCC.md) | Returns alls workflow instances for a list item
| [GetInstances(WorkflowSubscription)](Microsoft.SharePoint.Client.WorkflowExtensions.41117FBE.md) | Returns all instances of a workflow for this subscription
| [CancelWorkFlow(WorkflowInstance)](Microsoft.SharePoint.Client.WorkflowExtensions.1AFB83C2.md) | Cancels a workflow instance
| [ResumeWorkflow(WorkflowInstance)](Microsoft.SharePoint.Client.WorkflowExtensions.64C0F0E1.md) | Resumes a workflow
| [PublishCustomEvent(WorkflowInstance, String, String)](Microsoft.SharePoint.Client.WorkflowExtensions.41011483.md) | Publish a custom event to a target workflow instance
| [StartWorkflowInstance(Web, String, IDictionary<String, Object>)](Microsoft.SharePoint.Client.WorkflowExtensions.1AF92FBA.md) | 
| [StartWorkflowInstance(Web, Guid, IDictionary<String, Object>)](Microsoft.SharePoint.Client.WorkflowExtensions.F1316769.md) | 
| [StartWorkflowInstance(ListItem, String, IDictionary<String, Object>)](Microsoft.SharePoint.Client.WorkflowExtensions.B77B236E.md) | 
| [StartWorkflowInstance(ListItem, Guid, IDictionary<String, Object>)](Microsoft.SharePoint.Client.WorkflowExtensions.F71820E3.md) | 
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
