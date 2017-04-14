# ExternalSharingExtensions.ResolvePeoplePickerValueForEmail Method  
 Can be used to get needed people picker search result value for given email account. See &lt;a href="https://msdn.microsoft.com/en-us/library/office/jj179690.aspx"&gt;MSDN&lt;/a&gt;  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static string ResolvePeoplePickerValueForEmail(Web web, String emailAddress)
```
### Parameters
#### web  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.Web  
&emsp;&emsp;Web for the context used for people picker search  

  

#### emailAddress  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;Email address to be used as the query parameter. Should be pointing to unique person which is then searched using people picker capability programatically.  

  

### Return Value
Type: string  
Resolves people picker value which can be used for sharing objects in the SharePoint site  


## Remarks
  
## See also
- [ExternalSharingExtensions](Microsoft.SharePoint.Client.ExternalSharingExtensions.md) 
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md) 
