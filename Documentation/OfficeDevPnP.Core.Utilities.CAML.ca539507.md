# CAML.ViewQuery Method  
Root <View> and <Query> nodes.  

**Namespace:** [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static System.String ViewQuery(String whereClause, String orderByClause, Int32 rowLimit)
```
### Parameters
*(optional) whereClause*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;<Where> node.  
  
*(optional) orderByClause*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;<OrderBy> node.  
  
*(optional) rowLimit*  
&emsp;&emsp;Type: System.Int32  
&emsp;&emsp;<RowLimit> node.  
  
### Return Value
Type: System.String  
String to be used in CAML queries

## Examples
```C#
 CAML.ViewQuery( CAML.Where( CAML.And( CAML.Eq(CAML.FieldValue("Project", "Integer", "{0}")), CAML.Geq(CAML.FieldValue("StartDate","DateTime", CAML.Today())) ) ), CAML.OrderBy( new OrderByField("StartDate", false), new OrderByField("Title") ), rowLimit: 5 ); 
```

## See also
- [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)
