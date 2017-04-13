# ListExtensions.SetDefaultColumnValues Method  
 <para>Sets default values for column values.</para> <para>In order to for instance set the default Enterprise Metadata keyword field to a term, add the enterprise metadata keyword to a library (internal name "TaxKeyword")</para> <para></para> <para>Column values are defined by the DefaultColumnValue class that has 3 properties:</para> <para>RelativeFolderPath : / to set a default value for the root of the document library, or /foldername to specify a subfolder</para> <para>FieldInternalName : The name of the field to set. For instance "TaxKeyword" to set the Enterprise Metadata field</para> <para>Terms : A collection of Taxonomy terms to set</para> <para></para> <para>Supported column types: Metadata, Text, Choice, MultiChoice, People, Boolean, DateTime, Number, Currency</para>   

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static void SetDefaultColumnValues(List list, IEnumerable<IDefaultColumnValue> columnValues)
```
### Parameters
#### list  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.List  
&emsp;&emsp; <para>Sets default values for column values.</para> <para>In order to for instance set the default Enterprise Metadata keyword field to a term, add the enterprise metadata keyword to a library (internal name "TaxKeyword")</para> <para></para> <para>Column values are defined by the DefaultColumnValue class that has 3 properties:</para> <para>RelativeFolderPath : / to set a default value for the root of the document library, or /foldername to specify a subfolder</para> <para>FieldInternalName : The name of the field to set. For instance "TaxKeyword" to set the Enterprise Metadata field</para> <para>Terms : A collection of Taxonomy terms to set</para> <para></para> <para>Supported column types: Metadata, Text, Choice, MultiChoice, People, Boolean, DateTime, Number, Currency</para>   

  

#### columnValues  
&emsp;&emsp;Type: System.Collections.Generic.IEnumerable<OfficeDevPnP.Core.Entities.IDefaultColumnValue>  
&emsp;&emsp; <para>Sets default values for column values.</para> <para>In order to for instance set the default Enterprise Metadata keyword field to a term, add the enterprise metadata keyword to a library (internal name "TaxKeyword")</para> <para></para> <para>Column values are defined by the DefaultColumnValue class that has 3 properties:</para> <para>RelativeFolderPath : / to set a default value for the root of the document library, or /foldername to specify a subfolder</para> <para>FieldInternalName : The name of the field to set. For instance "TaxKeyword" to set the Enterprise Metadata field</para> <para>Terms : A collection of Taxonomy terms to set</para> <para></para> <para>Supported column types: Metadata, Text, Choice, MultiChoice, People, Boolean, DateTime, Number, Currency</para>   

  

### Return Value
Type: void  

## Remarks
  
## See also
- [ListExtensions](Microsoft.SharePoint.Client.ListExtensions.md) 
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md) 
