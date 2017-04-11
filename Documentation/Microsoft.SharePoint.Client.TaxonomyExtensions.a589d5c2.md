# TaxonomyExtensions.WireUpTaxonomyField Method  
 Wires up MMS field to the specified term.   

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static void WireUpTaxonomyField(Web web, Field field, Term anchorTerm, Boolean multiValue)
```
### Parameters
#### web  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.Web  
&emsp;&emsp;Site to be processed - can be root web or sub site  

  

#### field  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.Field  
&emsp;&emsp;Field to be wired up  

  

#### anchorTerm  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.Taxonomy.Term  
&emsp;&emsp;Taxonomy Term  

  

#### (optional) multiValue  
&emsp;&emsp;Type: System.Boolean  
&emsp;&emsp;If true, create a multivalue field  

  

### Return Value
Type: void  

## See also
- [TaxonomyExtensions](Microsoft.SharePoint.Client.TaxonomyExtensions.md) 
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md) 
