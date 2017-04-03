# TaxonomyExtensions.WireUpTaxonomyField Method  
Wires up MMS field to the specified term set.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static void WireUpTaxonomyField(Web web,Field field,String mmsGroupName,String mmsTermSetName,Boolean multiValue)
```
### Parameters
*web*  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.Web  
&emsp;&emsp;Site to be processed - can be root web or sub site  
  
*field*  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.Field  
&emsp;&emsp;Field to be wired up  
  
*mmsGroupName*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;Taxonomy group  
  
*mmsTermSetName*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;Term set name  
  
*(optional) multiValue*  
&emsp;&emsp;Type: System.Boolean  
&emsp;&emsp;If true, create a multivalue field  
  
### Return Value
Type: [System.Void]  

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)