# WorkflowExtensions.AddWorkflowSubscription Method  
**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static guid AddWorkflowSubscription(List list,String workflowDefinitionName,String subscriptionName,Boolean startManually,Boolean startOnCreate,Boolean startOnChange,String historyListName,String taskListName,Dictionary<String, String> associationValues)
```
### Parameters
*list*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.List](Microsoft.SharePoint.Client.List.md) 
&emsp;&emsp;  
  
*workflowDefinitionName*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*subscriptionName*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*startManually*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
*startOnCreate*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
*startOnChange*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
*historyListName*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*taskListName*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*(optional) associationValues*  
&emsp;&emsp;Type: [System.Collections.Generic.Dictionary<System.String,System.String>](System.Collections.Generic.Dictionary<System.String,System.String>.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Guid](System.Guid.md 
)
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
