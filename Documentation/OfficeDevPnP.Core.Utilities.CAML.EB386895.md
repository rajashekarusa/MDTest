ViewScope, String, String, String, Int32# CAML.ViewQuery members
Root <View> and <Query> nodes.  

**Namespace:** [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static string ViewQuery(ViewScope, String, String, String, Int32)
```
### Parameters
#### scope
Type: [Microsoft.SharePoint.Client.ViewScope](Microsoft.SharePoint.Client.ViewScope.md) 
#### 
#### (optional) whereClause
Type: [System.String](System.String.md) 
#### 
#### (optional) orderByClause
Type: [System.String](System.String.md) 
#### 
#### (optional) viewFields
Type: [System.String](System.String.md) 
#### 
#### (optional) rowLimit
Type: [System.Int32](System.Int32.md) 
#### 
### Return Value
Type: [System.String](System.String.md)String to be used in CAML queries
## Examples
```C#
 CAML.ViewQuery( CAML.Where( CAML.And( CAML.Eq(CAML.FieldValue("Project", "Integer", "{0}")), CAML.Geq(CAML.FieldValue("StartDate","DateTime", CAML.Today())) ) ), CAML.OrderBy( new OrderByField("StartDate", false), new OrderByField("Title") ), rowLimit: 5 ); 
```
## See also
- [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)
