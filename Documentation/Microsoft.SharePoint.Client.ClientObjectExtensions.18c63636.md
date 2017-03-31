# ClientObjectExtensions.IsPropertyAvailable Method  
Check if a property is available on a object  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static boolean IsPropertyAvailable(T clientObject,Expression<Func<T, Object>> propertySelector)
```
### Parameters
*clientObject*  
&emsp;&emsp;Type: [T](T.md) 
&emsp;&emsp;  
  
*propertySelector*  
&emsp;&emsp;Type: [System.Linq.Expressions.Expression<System.Func<T,System.Object>>](System.Linq.Expressions.Expression<System.Func<T,System.Object>>.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Boolean](System.Boolean.md)  
True if the property is available, false otherwise

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
