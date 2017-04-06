# WorkflowExtensions.AddWorkflowSubscription Method  
  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static Guid AddWorkflowSubscription(List list, String workflowDefinitionName, String subscriptionName, Boolean startManually, Boolean startOnCreate, Boolean startOnChange, String historyListName, String taskListName, Dictionary<String, String> associationValues)
```
### Parameters
*list*  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.List  
*workflowDefinitionName*  
&emsp;&emsp;Type: System.String  
*subscriptionName*  
&emsp;&emsp;Type: System.String  
*startManually*  
&emsp;&emsp;Type: System.Boolean  
*startOnCreate*  
&emsp;&emsp;Type: System.Boolean  
*startOnChange*  
&emsp;&emsp;Type: System.Boolean  
*historyListName*  
&emsp;&emsp;Type: System.String  
*taskListName*  
&emsp;&emsp;Type: System.String  
*(optional) associationValues*  
&emsp;&emsp;Type: System.Collections.Generic.Dictionary<System.String, System.String>  
### Return Value
Type: Guid  

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
