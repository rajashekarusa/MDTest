# ClientObjectExtensions.ToUntypedPropertyExpression Method  
Converts generic  Expression<Func<TInput, TOutput>>  to Expression with object return type -  Expression<Func<TInput, object>>  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static linq.expressions.expression<system.func<tinput,system.object>> ToUntypedPropertyExpression(Expression<Func<TInput, TOutput>> expression)
```
### Parameters
*expression*  
&emsp;&emsp;Type: [System.Linq.Expressions.Expression<System.Func<TInput,TOutput>>] 
&emsp;&emsp; to convert   
  
### Return Value
Type: [System.Linq.Expressions.Expression<System.Func<TInput,System.Object>>]  
New Expression where return type is object and not generic

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
