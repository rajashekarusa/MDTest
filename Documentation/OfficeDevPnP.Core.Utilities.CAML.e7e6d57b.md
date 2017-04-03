# CAML.FieldValue Method  
Creates both a <FieldRef> and <Value> nodes combination for Where clauses.  

**Namespace:** [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static string FieldValue(Guid fieldId,String fieldValueType,String value,String additionalFieldRefParams)
```
### Parameters
*fieldId*  
&emsp;&emsp;Type: [System.Guid] 
&emsp;&emsp;  
  
*fieldValueType*  
&emsp;&emsp;Type: [System.String] 
&emsp;&emsp;  
  
*value*  
&emsp;&emsp;Type: [System.String] 
&emsp;&emsp;  
  
*(optional) additionalFieldRefParams*  
&emsp;&emsp;Type: [System.String] 
&emsp;&emsp;  
  
### Return Value
Type: [System.String]  


## Examples
```C#
 CAML.ViewQuery( CAML.Where( CAML.And( CAML.Eq(CAML.FieldValue("Project", "Integer", "{0}")), CAML.Geq(CAML.FieldValue("StartDate","DateTime", CAML.Today())) ) ), CAML.OrderBy( new OrderByField("StartDate", false), new OrderByField("Title") ), rowLimit: 5 ); 
```

## See also
- [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)
