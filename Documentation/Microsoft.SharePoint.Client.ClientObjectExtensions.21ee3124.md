# ClientObjectExtensions.IsObjectPropertyInstantiated Method  
Check if a property is instantiated on a object  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static boolean IsObjectPropertyInstantiated(T clientObject,Expression<Func<T, Object>> propertySelector)
```
### Parameters
*clientObject*  
&emsp;&emsp;Type: [T](T.md) 
&emsp;&emsp;  
  
*propertySelector*  
&emsp;&emsp;Type: [System.Linq.Expressions.Expression<System.Func<T,System.Object>>](System.Linq.Expressions.Expression<System.Func<T,System.Object>>.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Boolean](System.Boolean.md 
)True if the property is instantiated, false otherwise

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
