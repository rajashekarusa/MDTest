# WebExtensions.GetPropertyBagValueString Method  
Get string typed property bag value. If does not contain, returns given default value.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static string GetPropertyBagValueString(Web web,String key,String defaultValue)
```
### Parameters
*web*  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.Web  
&emsp;&emsp;Web to read the property bag value from  
  
*key*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;Key of the property bag entry to return  
  
*defaultValue*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;  
  
### Return Value
Type: [System.String]  
Value of the property bag entry as string

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)