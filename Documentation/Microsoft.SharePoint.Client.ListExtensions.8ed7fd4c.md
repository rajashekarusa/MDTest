# ListExtensions.SetLocalizationLabelsForList Method  
Can be used to set translations for different cultures.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static void SetLocalizationLabelsForList(List list,String cultureName,String titleResource,String descriptionResource)
```
### Parameters
*list*  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.List  
&emsp;&emsp;List to be processed   
  
*cultureName*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;Culture name like en-us or fi-fi  
  
*titleResource*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;Localized Title string  
  
*descriptionResource*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;Localized Description string  
  
### Return Value
Type: [System.Void]  

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)