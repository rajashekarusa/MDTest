# ClientObjectExtensions.ToUntypedPropertyExpression Method  
Converts generic  Expression<Func<TInput, TOutput>>  to Expression with object return type -  Expression<Func<TInput, object>>  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static linq.expressions.expression`1<system.func`2<tinput,system.object>> ToUntypedPropertyExpression(Expression<Func<TInput, TOutput>> expression)
```
### Parameters
*expression*  
&emsp;&emsp;Type: [System.Linq.Expressions.Expression<System.Func<TInput,TOutput>>](System.Linq.Expressions.Expression<System.Func<TInput,TOutput>>.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Linq.Expressions.Expression`1<System.Func`2<TInput,System.Object>>](System.Linq.Expressions.Expression`1<System.Func`2<TInput,System.Object>>.md 
)New Expression where return type is object and not generic

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
