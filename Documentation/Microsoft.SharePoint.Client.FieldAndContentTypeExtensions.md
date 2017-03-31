# FieldAndContentTypeExtensions
This class holds deprecated extension methods that will help you work with fields and content types.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Inheritance Hierarchy
System.Object  
## Syntax
```C#
public static class FieldAndContentTypeExtensions
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [CreateField(Web, FieldCreationInformation, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.C9F9B03F.md) | Create field to web remotely
| [CreateField(Web, FieldCreationInformation, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.C9F9B03F.md) | 
| [CreateField(Web, String, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.8BE6143A.md) | Create field to web remotely
| [RemoveFieldByInternalName(Web, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.D0B69CCA.md) | Removes a field by specifying its internal name
| [RemoveFieldById(Web, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.7F3BCD91.md) | Removes a field by specifying its ID
| [CreateFieldsFromXMLFile(Web, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.C7CD2CF8.md) | Creates fields from feature element xml file schema. XML file can contain one or many field definitions created using classic feature framework structure.
| [CreateFieldsFromXMLString(Web, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.ABEB1E95.md) | Creates fields from feature element xml file schema. XML file can contain one or many field definitions created using classic feature framework structure.
| [CreateFieldsFromXML(Web, XDocument)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.9BC8D719.md) | Creates field from xml structure which follows the classic feature framework structure
| [FieldExistsById(Web, Guid, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.7B2D21BF.md) | Returns if the field is found
| [GetFieldById(Web, Guid, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.A552175C.md) | Returns the field if it exists. Null if it does not exist.
| [GetFieldById(Web, Guid, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.A552175C.md) | 
| [GetFieldById(List, Guid)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.F00C000F.md) | Returns the field if it exists. Null if it does not exist.
| [GetFieldById(List, Guid)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.F00C000F.md) | 
| [GetFieldByInternalName(Web, String, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.3CA86595.md) | Returns the field if it exists. Null if does not exist.
| [GetFieldByName(FieldCollection, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.DB62D2BC.md) | Returns the field if it exists. Null if it does not exist.
| [GetFieldByName(FieldCollection, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.DB62D2BC.md) | 
| [GetFieldByInternalName(FieldCollection, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.A6B12C6.md) | Returns the field if it exists. Null if it does not exist.
| [GetFieldByInternalName(FieldCollection, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.A6B12C6.md) | 
| [FieldExistsByName(Web, String, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.2D7862F8.md) | Returns if the field is found
| [FieldExistsById(Web, String, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.D7FD74D3.md) | Does field exist in web
| [FieldExistsByNameInContentType(Web, String, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.6B483DF3.md) | Field exists in content type
| [FieldExistsByNameInContentType(ContentType, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.470AE95F.md) | Checks if a field exists in a content type by id
| [SetJsLinkCustomizations(Field, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.5F46C9A2.md) | Adds jsLink to a field.
| [CreateField(List, FieldCreationInformation, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.9167A54E.md) | Adds field to a list
| [CreateField(List, FieldCreationInformation, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.9167A54E.md) | 
| [CreateFieldBase(FieldCollection, FieldCreationInformation, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.21B7C8F9.md) | Base implementation for creating fields
| [FormatFieldXml(FieldCreationInformation)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.F06BC135.md) | Formats a fieldcreationinformation object into Field CAML xml.
| [CreateField(List, String, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.DB895C0.md) | Adds a field to a list
| [FieldExistsById(List, Guid)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.E6F3BEC3.md) | Returns if the field is found
| [FieldExistsById(List, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.54A82652.md) | Returns if the field is found, query based on the ID
| [FieldExistsByName(List, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.67FF82CE.md) | Field exists in list by name
| [GetFields(List, String[])](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.96A2398F.md) | Gets a list of fields from a list by names.
| [SetJsLinkCustomizations(List, String, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.AC751D3.md) | Adds jsLink to a list field.
| [ParseAdditionalAttributes(String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.70E4D573.md) | Helper method to parse Key="Value" strings into a keyvaluepair
| [AddContentTypeToListById(Web, String, String, Boolean, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.55771F16.md) | Adds content type to list
| [AddContentTypeToListByName(Web, String, String, Boolean, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.4BEE1F7D.md) | Adds content type to list
| [AddContentTypeToList(Web, String, ContentType, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.8015FDD1.md) | Adds content type to list
| [AddContentTypeToListById(List, String, Boolean, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.D2E9CBAA.md) | Add content type to list
| [AddContentTypeToListByName(List, String, Boolean, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.5194E73A.md) | Add content type to list
| [AddContentTypeToList(List, ContentType, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.7070361C.md) | Add content type to list
| [AddFieldById(ContentType, String, Boolean, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.B2913BA1.md) | Associates field to content type
| [AddFieldById(ContentType, Guid, Boolean, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.8CC9483E.md) | Associates field to content type
| [AddFieldByName(ContentType, String, Boolean, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.7439EF2.md) | Associates field to content type
| [AddFieldToContentTypeById(Web, String, String, Boolean, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.960A9456.md) | Associates field to content type
| [AddFieldToContentTypeByName(Web, String, Guid, Boolean, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.539B980F.md) | Associates field to content type
| [AddFieldToContentType(Web, ContentType, Field, Boolean, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.3D349624.md) | Associates field to content type
| [BestMatchContentTypeId(List, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.EAB7E452.md) | Searches the list content types and returns the content type identifier (ID) that is the nearest match to the specified content type ID.
| [BestMatchContentTypeIdImplementation(List, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.25DE7023.md) | 
| [ContentTypeExistsById(Web, String, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.5EF3BFD6.md) | Does content type exists in the web
| [ContentTypeExistsByName(Web, String, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.3B90D49F.md) | Does content type exists in the web
| [ContentTypeExistsById(Web, String, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.A050753E.md) | Does content type exist in web
| [ContentTypeExistsById(List, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.12BEA999.md) | Does content type exist in list
| [ContentTypeExistsByName(Web, String, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.BBDA9D79.md) | Does content type exist in web
| [ContentTypeExistsByName(List, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.64884576.md) | Does content type exist in list
| [CreateContentTypeFromXMLFile(Web, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.521FEC1B.md) | Create a content type based on the classic feature framework structure.
| [CreateContentTypeFromXMLString(Web, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.5DF0E3E9.md) | Create a content type based on the classic feature framework structure.
| [CreateContentTypeFromXML(Web, XDocument)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.CCAFD6B.md) | Create a content type based on the classic feature framework structure.
| [CreateContentType(Web, String, String, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.63C9D5BF.md) | Create new content type to web
| [CreateContentType(Web, String, String, String, String, ContentType)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.838928A.md) | Create new content type to web
| [DeleteContentTypeByName(Web, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.76B85598.md) | Deletes a content type from the web by name
| [DeleteContentTypeById(Web, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.7DB8C43A.md) | Deletes a content type from the web by id
| [GetContentTypeByName(Web, String, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.DAC8C10A.md) | Return content type by name
| [GetContentTypeById(Web, String, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.9E769121.md) | Return content type by Id
| [GetContentTypeByName(List, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.7E65E981.md) | Return content type by name
| [GetContentTypeById(List, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.5BA34F83.md) | Return content type by Id
| [BestMatch(ContentTypeCollection, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.E1D069B0.md) | Searches for the content type with the closest match to the value of the specified content type ID. If the search finds two matches, the shorter ID is returned.
| [RemoveContentTypeFromListByName(Web, String, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.8333F667.md) | Removes content type from list
| [RemoveContentTypeFromListByName(Web, List, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.8AAC8612.md) | Removes content type from list
| [RemoveContentTypeFromListById(Web, String, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.8A877F1A.md) | Removes content type from a list
| [RemoveContentTypeFromListById(Web, List, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.88667CF4.md) | Removes content type from a list
| [RemoveContentTypeFromList(Web, List, ContentType)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.ED537A75.md) | Removes content type from a list
| [SetDefaultContentTypeToList(Web, List, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.6B5DCE6C.md) | Set default content type to list
| [SetDefaultContentTypeToList(Web, List, ContentType)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.156C371A.md) | Set default content type to list
| [SetDefaultContentTypeToList(Web, String, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.43DF7B04.md) | Set default content type to list
| [SetDefaultContentTypeToList(Web, String, ContentType)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.658DABC5.md) | Set's default content type list.
| [SetDefaultContentTypeToList(List, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.F809C93D.md) | Set's default content type list.
| [SetDefaultContentTypeToList(List, ContentType)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.DECEB25A.md) | Set default content type to list
| [ReorderContentTypes(List, IEnumerable<String>)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.215C7C05.md) | 
| [SetLocalizationForContentType(Web, String, String, String, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.C2130165.md) | Set localized labels for content type
| [SetLocalizationForContentType(List, String, String, String, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.4D67B41C.md) | Set localized labels for content type
| [SetLocalizationForContentType(ContentType, String, String, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.E7593ABE.md) | Set localized labels for content type
| [SetLocalizationForField(Web, Guid, String, String, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.D0922668.md) | Set localized labels for field
| [SetLocalizationForField(Web, String, String, String, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.23C901FD.md) | Set localized labels for field
| [SetLocalizationForField(Web, Field, String, String, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.4786FFE9.md) | Set localized labels for field
| [SetLocalizationForField(List, Guid, String, String, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.422FB615.md) | Set localized labels for field
| [SetLocalizationForField(List, String, String, String, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.791C339C.md) | Set localized labels for field
| [SetLocalizationForField(List, Field, String, String, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.BE84DE34.md) | Set localized labels for field
| [SetLocalizationForField(Field, String, String, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.2D7CCFFD.md) | Set localized labels for field
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
