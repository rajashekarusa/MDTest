# WorkflowExtensions.AddWorkflowSubscription Method  
**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static guid AddWorkflowSubscription(List list, String workflowDefinitionName, String subscriptionName, Boolean startManually, Boolean startOnCreate, Boolean startOnChange, String historyListName, String taskListName, Dictionary<String, String> associationValues)
```
### Parameters
*list*  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.List  
&emsp;&emsp;  
  
*workflowDefinitionName*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;  
  
*subscriptionName*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;  
  
*startManually*  
&emsp;&emsp;Type: System.Boolean  
&emsp;&emsp;  
  
*startOnCreate*  
&emsp;&emsp;Type: System.Boolean  
&emsp;&emsp;  
  
*startOnChange*  
&emsp;&emsp;Type: System.Boolean  
&emsp;&emsp;  
  
*historyListName*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;  
  
*taskListName*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;  
  
*(optional) associationValues*  
&emsp;&emsp;Type: System.Collections.Generic.Dictionary<System.String,System.String>  
&emsp;&emsp;  
  
### Return Value
Type: System.Guid  

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
