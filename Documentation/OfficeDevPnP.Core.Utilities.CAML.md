# CAML
Use this class to build your CAML xml and avoid XML issues.  

**Namespace:** [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Inheritance Hierarchy
System.Object  
## Syntax
```C#
public static class CAML
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [Today(Nullable<Int32>)](OfficeDevPnP.Core.Utilities.CAML.TodayNullable<Int32>.md) | 
| [ViewQuery(String, String, Int32)](OfficeDevPnP.Core.Utilities.CAML.ViewQueryStringStringInt32.md) | Root <View> and <Query> nodes.
| [ViewQuery(Microsoft.SharePoint.Client.ViewScope, String, String, String, Int32)](OfficeDevPnP.Core.Utilities.CAML.ViewQueryMicrosoft.SharePoint.Client.ViewScopeStringStringStringInt32.md) | Root <View> and <Query> nodes.
| [FieldValue(String, String, String, String)](OfficeDevPnP.Core.Utilities.CAML.FieldValueStringStringStringString.md) | Creates both a <FieldRef> and <Value> nodes combination for Where clauses.
| [FieldValue(Guid, String, String, String)](OfficeDevPnP.Core.Utilities.CAML.FieldValueGuidStringStringString.md) | Creates both a <FieldRef> and <Value> nodes combination for Where clauses.
| [FieldRef(String)](OfficeDevPnP.Core.Utilities.CAML.FieldRefString.md) | Creates a <FieldRef> node for ViewFields clause
| [OrderBy(OrderByField[])](OfficeDevPnP.Core.Utilities.CAML.OrderByOrderByField[].md) | 
| [Where(String)](OfficeDevPnP.Core.Utilities.CAML.WhereString.md) | 
| [ViewFields(String[])](OfficeDevPnP.Core.Utilities.CAML.ViewFieldsString[].md) | 
| [And(String, String[])](OfficeDevPnP.Core.Utilities.CAML.AndStringString[].md) | 
| [Or(String, String[])](OfficeDevPnP.Core.Utilities.CAML.OrStringString[].md) | 
| [BeginsWith(String)](OfficeDevPnP.Core.Utilities.CAML.BeginsWithString.md) | 
| [Contains(String)](OfficeDevPnP.Core.Utilities.CAML.ContainsString.md) | 
| [DateRangesOverlap(String)](OfficeDevPnP.Core.Utilities.CAML.DateRangesOverlapString.md) | 
| [Eq(String)](OfficeDevPnP.Core.Utilities.CAML.EqString.md) | 
| [Geq(String)](OfficeDevPnP.Core.Utilities.CAML.GeqString.md) | 
| [Gt(String)](OfficeDevPnP.Core.Utilities.CAML.GtString.md) | 
| [In(String)](OfficeDevPnP.Core.Utilities.CAML.InString.md) | 
| [Includes(String)](OfficeDevPnP.Core.Utilities.CAML.IncludesString.md) | 
| [IsNotNull(String)](OfficeDevPnP.Core.Utilities.CAML.IsNotNullString.md) | 
| [IsNull(String)](OfficeDevPnP.Core.Utilities.CAML.IsNullString.md) | 
| [Leq(String)](OfficeDevPnP.Core.Utilities.CAML.LeqString.md) | 
| [Lt(String)](OfficeDevPnP.Core.Utilities.CAML.LtString.md) | 
| [Neq(String)](OfficeDevPnP.Core.Utilities.CAML.NeqString.md) | 
| [NotIncludes(String)](OfficeDevPnP.Core.Utilities.CAML.NotIncludesString.md) | 
| [Comparison(CAML/CamlComparisions, String)](OfficeDevPnP.Core.Utilities.CAML.ComparisonCAML/CamlComparisionsString.md) | 
| [Condition(CAML/CamlConditions, String, String[])](OfficeDevPnP.Core.Utilities.CAML.ConditionCAML/CamlConditionsStringString[].md) | 
## Examples
```C#
 CAML.ViewQuery( CAML.Where( CAML.And( CAML.Eq(CAML.FieldValue("Project", "Integer", "{0}")), CAML.Geq(CAML.FieldValue("StartDate","DateTime", CAML.Today())) ) ), CAML.OrderBy( new OrderByField("StartDate", false), new OrderByField("Title") ), rowLimit: 5 ); 
```
## See also
- [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)
