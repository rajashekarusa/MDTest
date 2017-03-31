String# CAML.IsNotNull members
  

**Namespace:** [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static string IsNotNull(String)
```
### Parameters
#### fieldValue
Type: [System.String](System.String.md) 
#### 
### Return Value
Type: [System.String](System.String.md)## Examples
```C#
 CAML.ViewQuery( CAML.Where( CAML.And( CAML.Eq(CAML.FieldValue("Project", "Integer", "{0}")), CAML.Geq(CAML.FieldValue("StartDate","DateTime", CAML.Today())) ) ), CAML.OrderBy( new OrderByField("StartDate", false), new OrderByField("Title") ), rowLimit: 5 ); 
```
## See also
- [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)
