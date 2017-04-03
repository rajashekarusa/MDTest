# ClientObjectExtensions.EnsureProperty Method  
  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  EnsureProperty(T clientObject,Expression<Func<T, TResult>> propertySelector)
```
### Parameters
*clientObject*  
&emsp;&emsp;Type: T  
&emsp;&emsp;  
  
*propertySelector*  
&emsp;&emsp;Type: System.Linq.Expressions.Expression<System.Func<T,TResult>>  
&emsp;&emsp;Lamda expression containing the property to ensure (e.g. w => w.HasUniqueRoleAssignments)  
  
### Return Value
Type: TResult  
Property value

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
