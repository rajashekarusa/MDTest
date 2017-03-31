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
| [Today(Nullable<Int32>)](OfficeDevPnP.Core.Utilities.CAML.964AA169.md) | 
| [ViewQuery(String, String, Int32)](OfficeDevPnP.Core.Utilities.CAML.CA539507.md) | Root <View> and <Query> nodes.
| [ViewQuery(ViewScope, String, String, String, Int32)](OfficeDevPnP.Core.Utilities.CAML.EB386895.md) | Root <View> and <Query> nodes.
| [FieldValue(String, String, String, String)](OfficeDevPnP.Core.Utilities.CAML.D591550D.md) | Creates both a <FieldRef> and <Value> nodes combination for Where clauses.
| [FieldValue(Guid, String, String, String)](OfficeDevPnP.Core.Utilities.CAML.E7E6D57B.md) | Creates both a <FieldRef> and <Value> nodes combination for Where clauses.
| [FieldRef(String)](OfficeDevPnP.Core.Utilities.CAML.145EB1C6.md) | Creates a <FieldRef> node for ViewFields clause
| [OrderBy(OrderByField[])](OfficeDevPnP.Core.Utilities.CAML.E8E4DF3.md) | 
| [Where(String)](OfficeDevPnP.Core.Utilities.CAML.93C72EEA.md) | 
| [ViewFields(String[])](OfficeDevPnP.Core.Utilities.CAML.4F215FE4.md) | 
| [And(String, String[])](OfficeDevPnP.Core.Utilities.CAML.2163F362.md) | 
| [Or(String, String[])](OfficeDevPnP.Core.Utilities.CAML.D687337D.md) | 
| [BeginsWith(String)](OfficeDevPnP.Core.Utilities.CAML.98C94C83.md) | 
| [Contains(String)](OfficeDevPnP.Core.Utilities.CAML.30C4004E.md) | 
| [DateRangesOverlap(String)](OfficeDevPnP.Core.Utilities.CAML.3B844EC8.md) | 
| [Eq(String)](OfficeDevPnP.Core.Utilities.CAML.B61163FE.md) | 
| [Geq(String)](OfficeDevPnP.Core.Utilities.CAML.EE6386E1.md) | 
| [Gt(String)](OfficeDevPnP.Core.Utilities.CAML.B5706338.md) | 
| [In(String)](OfficeDevPnP.Core.Utilities.CAML.B4B6656A.md) | 
| [Includes(String)](OfficeDevPnP.Core.Utilities.CAML.675847AC.md) | 
| [IsNotNull(String)](OfficeDevPnP.Core.Utilities.CAML.24458B05.md) | 
| [IsNull(String)](OfficeDevPnP.Core.Utilities.CAML.F92D91C8.md) | 
| [Leq(String)](OfficeDevPnP.Core.Utilities.CAML.EE63BADE.md) | 
| [Lt(String)](OfficeDevPnP.Core.Utilities.CAML.B57064C7.md) | 
| [Neq(String)](OfficeDevPnP.Core.Utilities.CAML.EE63A4F8.md) | 
| [NotIncludes(String)](OfficeDevPnP.Core.Utilities.CAML.1518F754.md) | 
| [Comparison(CAML/CamlComparisions, String)](OfficeDevPnP.Core.Utilities.CAML.869F7F6E.md) | 
| [Condition(CAML/CamlConditions, String, String[])](OfficeDevPnP.Core.Utilities.CAML.BFD0636.md) | 
## Examples
```C#
 CAML.ViewQuery( CAML.Where( CAML.And( CAML.Eq(CAML.FieldValue("Project", "Integer", "{0}")), CAML.Geq(CAML.FieldValue("StartDate","DateTime", CAML.Today())) ) ), CAML.OrderBy( new OrderByField("StartDate", false), new OrderByField("Title") ), rowLimit: 5 ); 
```
## See also
- [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)
