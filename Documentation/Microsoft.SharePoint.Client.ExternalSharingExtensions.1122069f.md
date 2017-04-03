# ExternalSharingExtensions.ShareDocumentWithPeoplePickerValue Method  
Share document with complex JSON string value.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  ShareDocumentWithPeoplePickerValue(Web web,String urlToDocument,String peoplePickerInput,ExternalSharingDocumentOption shareOption,Boolean sendEmail,String emailBody,Boolean useSimplifiedRoles)
```
### Parameters
*web*  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.Web  
&emsp;&emsp;Web for the context used for people picker search  
  
*urlToDocument*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;Full URL to the file which is shared  
  
*peoplePickerInput*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;People picker JSON string value containing the target person information  
  
*shareOption*  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.ExternalSharingDocumentOption  
&emsp;&emsp;View or Edit option  
  
*(optional) sendEmail*  
&emsp;&emsp;Type: System.Boolean  
&emsp;&emsp;Send email or not  
  
*(optional) emailBody*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;Text attached to the email sent for the person to whom the document is shared  
  
*(optional) useSimplifiedRoles*  
&emsp;&emsp;Type: System.Boolean  
&emsp;&emsp;Boolean value indicating whether to use the SharePoint simplified roles (Edit, View)  
  
### Return Value
Type: [Microsoft.SharePoint.Client.SharingResult]  

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)