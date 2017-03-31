# WebExtensions.GetWeb Method  
Returns the child Web site with the specified leaf URL.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  GetWeb(Web parentWeb,String leafUrl)
```
### Parameters
*parentWeb*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Web](Microsoft.SharePoint.Client.Web.md) 
&emsp;&emsp;  
  
*leafUrl*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
### Return Value
Type: [Microsoft.SharePoint.Client.Web](Microsoft.SharePoint.Client.Web.md 
)The requested Web, if it exists, otherwise null.

## Remarks 

            The ServerRelativeUrl property of the retrieved Web is instantiated.
            
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
