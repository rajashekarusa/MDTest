# ListExtensions.GetDefaultColumnValues Method  
 <para>Gets default values for column values.</para> <para></para> <para>The returned list contains one dictionary per default setting per folder.</para> <para>Each dictionary has the following keys set: Path, Field, Value</para> <para></para> <para>Path: Relative path to the library/folder</para> <para>Field: Internal name of the field which has a default value</para> <para>Value: The default value for the field</para>   

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static List<Dictionary<String, String>> GetDefaultColumnValues(List list)
```
### Parameters
*list*  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.List  
### Return Value
Type: List<Dictionary<String,  String>>  

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
