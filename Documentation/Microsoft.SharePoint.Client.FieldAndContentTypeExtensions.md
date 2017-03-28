# FieldAndContentTypeExtensions
This class holds deprecated extension methods that will help you work with fields and content types.
**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Classes
System.Object  
## Syntax
```C#
public class FieldAndContentTypeExtensions
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [CreateField(Web, OfficeDevPnP.Core.Entities.FieldCreationInformation, Boolean)](FieldAndContentTypeExtensionsCreateFieldWebOfficeDevPnP.Core.Entities.FieldCreationInformationBoolean.md) | Create field to web remotely
| [CreateField(Web, OfficeDevPnP.Core.Entities.FieldCreationInformation, Boolean)](FieldAndContentTypeExtensionsCreateFieldWebOfficeDevPnP.Core.Entities.FieldCreationInformationBoolean.md) | 
| [CreateField(Web, String, Boolean)](FieldAndContentTypeExtensionsCreateFieldWebStringBoolean.md) | Create field to web remotely
| [RemoveFieldByInternalName(Web, String)](FieldAndContentTypeExtensionsRemoveFieldByInternalNameWebString.md) | Removes a field by specifying its internal name
| [RemoveFieldById(Web, String)](FieldAndContentTypeExtensionsRemoveFieldByIdWebString.md) | Removes a field by specifying its ID
| [CreateFieldsFromXMLFile(Web, String)](FieldAndContentTypeExtensionsCreateFieldsFromXMLFileWebString.md) | Creates fields from feature element xml file schema. XML file can contain one or many field definitions created using classic feature framework structure.
| [CreateFieldsFromXMLString(Web, String)](FieldAndContentTypeExtensionsCreateFieldsFromXMLStringWebString.md) | Creates fields from feature element xml file schema. XML file can contain one or many field definitions created using classic feature framework structure.
| [CreateFieldsFromXML(Web, Xml.Linq.XDocument)](FieldAndContentTypeExtensionsCreateFieldsFromXMLWebXml.Linq.XDocument.md) | Creates field from xml structure which follows the classic feature framework structure
| [FieldExistsById(Web, Guid, Boolean)](FieldAndContentTypeExtensionsFieldExistsByIdWebGuidBoolean.md) | Returns if the field is found
| [GetFieldById(Web, Guid, Boolean)](FieldAndContentTypeExtensionsGetFieldByIdWebGuidBoolean.md) | Returns the field if it exists. Null if it does not exist.
| [GetFieldById(Web, Guid, Boolean)](FieldAndContentTypeExtensionsGetFieldByIdWebGuidBoolean.md) | 
| [GetFieldById(List, Guid)](FieldAndContentTypeExtensionsGetFieldByIdListGuid.md) | Returns the field if it exists. Null if it does not exist.
| [GetFieldById(List, Guid)](FieldAndContentTypeExtensionsGetFieldByIdListGuid.md) | 
| [GetFieldByInternalName(Web, String, Boolean)](FieldAndContentTypeExtensionsGetFieldByInternalNameWebStringBoolean.md) | Returns the field if it exists. Null if does not exist.
| [GetFieldByName(FieldCollection, String)](FieldAndContentTypeExtensionsGetFieldByNameFieldCollectionString.md) | Returns the field if it exists. Null if it does not exist.
| [GetFieldByName(FieldCollection, String)](FieldAndContentTypeExtensionsGetFieldByNameFieldCollectionString.md) | 
| [GetFieldByInternalName(FieldCollection, String)](FieldAndContentTypeExtensionsGetFieldByInternalNameFieldCollectionString.md) | Returns the field if it exists. Null if it does not exist.
| [GetFieldByInternalName(FieldCollection, String)](FieldAndContentTypeExtensionsGetFieldByInternalNameFieldCollectionString.md) | 
| [FieldExistsByName(Web, String, Boolean)](FieldAndContentTypeExtensionsFieldExistsByNameWebStringBoolean.md) | Returns if the field is found
| [FieldExistsById(Web, String, Boolean)](FieldAndContentTypeExtensionsFieldExistsByIdWebStringBoolean.md) | Does field exist in web
| [FieldExistsByNameInContentType(Web, String, String)](FieldAndContentTypeExtensionsFieldExistsByNameInContentTypeWebStringString.md) | Field exists in content type
| [FieldExistsByNameInContentType(ContentType, String)](FieldAndContentTypeExtensionsFieldExistsByNameInContentTypeContentTypeString.md) | Checks if a field exists in a content type by id
| [SetJsLinkCustomizations(Field, String)](FieldAndContentTypeExtensionsSetJsLinkCustomizationsFieldString.md) | Adds jsLink to a field.
| [CreateField(List, OfficeDevPnP.Core.Entities.FieldCreationInformation, Boolean)](FieldAndContentTypeExtensionsCreateFieldListOfficeDevPnP.Core.Entities.FieldCreationInformationBoolean.md) | Adds field to a list
| [CreateField(List, OfficeDevPnP.Core.Entities.FieldCreationInformation, Boolean)](FieldAndContentTypeExtensionsCreateFieldListOfficeDevPnP.Core.Entities.FieldCreationInformationBoolean.md) | 
| [CreateFieldBase(FieldCollection, OfficeDevPnP.Core.Entities.FieldCreationInformation, Boolean)](FieldAndContentTypeExtensionsCreateFieldBaseFieldCollectionOfficeDevPnP.Core.Entities.FieldCreationInformationBoolean.md) | Base implementation for creating fields
| [FormatFieldXml(OfficeDevPnP.Core.Entities.FieldCreationInformation)](FieldAndContentTypeExtensionsFormatFieldXmlOfficeDevPnP.Core.Entities.FieldCreationInformation.md) | Formats a fieldcreationinformation object into Field CAML xml.
| [CreateField(List, String, Boolean)](FieldAndContentTypeExtensionsCreateFieldListStringBoolean.md) | Adds a field to a list
| [FieldExistsById(List, Guid)](FieldAndContentTypeExtensionsFieldExistsByIdListGuid.md) | Returns if the field is found
| [FieldExistsById(List, String)](FieldAndContentTypeExtensionsFieldExistsByIdListString.md) | Returns if the field is found, query based on the ID
| [FieldExistsByName(List, String)](FieldAndContentTypeExtensionsFieldExistsByNameListString.md) | Field exists in list by name
| [GetFields(List, String[])](FieldAndContentTypeExtensionsGetFieldsListString[].md) | Gets a list of fields from a list by names.
| [SetJsLinkCustomizations(List, String, String)](FieldAndContentTypeExtensionsSetJsLinkCustomizationsListStringString.md) | Adds jsLink to a list field.
| [ParseAdditionalAttributes(String)](FieldAndContentTypeExtensionsParseAdditionalAttributesString.md) | Helper method to parse Key="Value" strings into a keyvaluepair
| [AddContentTypeToListById(Web, String, String, Boolean, Boolean)](FieldAndContentTypeExtensionsAddContentTypeToListByIdWebStringStringBooleanBoolean.md) | Adds content type to list
| [AddContentTypeToListByName(Web, String, String, Boolean, Boolean)](FieldAndContentTypeExtensionsAddContentTypeToListByNameWebStringStringBooleanBoolean.md) | Adds content type to list
| [AddContentTypeToList(Web, String, ContentType, Boolean)](FieldAndContentTypeExtensionsAddContentTypeToListWebStringContentTypeBoolean.md) | Adds content type to list
| [AddContentTypeToListById(List, String, Boolean, Boolean)](FieldAndContentTypeExtensionsAddContentTypeToListByIdListStringBooleanBoolean.md) | Add content type to list
| [AddContentTypeToListByName(List, String, Boolean, Boolean)](FieldAndContentTypeExtensionsAddContentTypeToListByNameListStringBooleanBoolean.md) | Add content type to list
| [AddContentTypeToList(List, ContentType, Boolean)](FieldAndContentTypeExtensionsAddContentTypeToListListContentTypeBoolean.md) | Add content type to list
| [AddFieldById(ContentType, String, Boolean, Boolean)](FieldAndContentTypeExtensionsAddFieldByIdContentTypeStringBooleanBoolean.md) | Associates field to content type
| [AddFieldById(ContentType, Guid, Boolean, Boolean)](FieldAndContentTypeExtensionsAddFieldByIdContentTypeGuidBooleanBoolean.md) | Associates field to content type
| [AddFieldByName(ContentType, String, Boolean, Boolean)](FieldAndContentTypeExtensionsAddFieldByNameContentTypeStringBooleanBoolean.md) | Associates field to content type
| [AddFieldToContentTypeById(Web, String, String, Boolean, Boolean)](FieldAndContentTypeExtensionsAddFieldToContentTypeByIdWebStringStringBooleanBoolean.md) | Associates field to content type
| [AddFieldToContentTypeByName(Web, String, Guid, Boolean, Boolean)](FieldAndContentTypeExtensionsAddFieldToContentTypeByNameWebStringGuidBooleanBoolean.md) | Associates field to content type
| [AddFieldToContentType(Web, ContentType, Field, Boolean, Boolean)](FieldAndContentTypeExtensionsAddFieldToContentTypeWebContentTypeFieldBooleanBoolean.md) | Associates field to content type
| [BestMatchContentTypeId(List, String)](FieldAndContentTypeExtensionsBestMatchContentTypeIdListString.md) | Searches the list content types and returns the content type identifier (ID) that is the nearest match to the specified content type ID.
| [BestMatchContentTypeIdImplementation(List, String)](FieldAndContentTypeExtensionsBestMatchContentTypeIdImplementationListString.md) | 
| [ContentTypeExistsById(Web, String, Boolean)](FieldAndContentTypeExtensionsContentTypeExistsByIdWebStringBoolean.md) | Does content type exists in the web
| [ContentTypeExistsByName(Web, String, Boolean)](FieldAndContentTypeExtensionsContentTypeExistsByNameWebStringBoolean.md) | Does content type exists in the web
| [ContentTypeExistsById(Web, String, String)](FieldAndContentTypeExtensionsContentTypeExistsByIdWebStringString.md) | Does content type exist in web
| [ContentTypeExistsById(List, String)](FieldAndContentTypeExtensionsContentTypeExistsByIdListString.md) | Does content type exist in list
| [ContentTypeExistsByName(Web, String, String)](FieldAndContentTypeExtensionsContentTypeExistsByNameWebStringString.md) | Does content type exist in web
| [ContentTypeExistsByName(List, String)](FieldAndContentTypeExtensionsContentTypeExistsByNameListString.md) | Does content type exist in list
| [CreateContentTypeFromXMLFile(Web, String)](FieldAndContentTypeExtensionsCreateContentTypeFromXMLFileWebString.md) | Create a content type based on the classic feature framework structure.
| [CreateContentTypeFromXMLString(Web, String)](FieldAndContentTypeExtensionsCreateContentTypeFromXMLStringWebString.md) | Create a content type based on the classic feature framework structure.
| [CreateContentTypeFromXML(Web, Xml.Linq.XDocument)](FieldAndContentTypeExtensionsCreateContentTypeFromXMLWebXml.Linq.XDocument.md) | Create a content type based on the classic feature framework structure.
| [CreateContentType(Web, String, String, String)](FieldAndContentTypeExtensionsCreateContentTypeWebStringStringString.md) | Create new content type to web
| [CreateContentType(Web, String, String, String, String, ContentType)](FieldAndContentTypeExtensionsCreateContentTypeWebStringStringStringStringContentType.md) | Create new content type to web
| [DeleteContentTypeByName(Web, String)](FieldAndContentTypeExtensionsDeleteContentTypeByNameWebString.md) | Deletes a content type from the web by name
| [DeleteContentTypeById(Web, String)](FieldAndContentTypeExtensionsDeleteContentTypeByIdWebString.md) | Deletes a content type from the web by id
| [GetContentTypeByName(Web, String, Boolean)](FieldAndContentTypeExtensionsGetContentTypeByNameWebStringBoolean.md) | Return content type by name
| [GetContentTypeById(Web, String, Boolean)](FieldAndContentTypeExtensionsGetContentTypeByIdWebStringBoolean.md) | Return content type by Id
| [GetContentTypeByName(List, String)](FieldAndContentTypeExtensionsGetContentTypeByNameListString.md) | Return content type by name
| [GetContentTypeById(List, String)](FieldAndContentTypeExtensionsGetContentTypeByIdListString.md) | Return content type by Id
| [BestMatch(ContentTypeCollection, String)](FieldAndContentTypeExtensionsBestMatchContentTypeCollectionString.md) | Searches for the content type with the closest match to the value of the specified content type ID. If the search finds two matches, the shorter ID is returned.
| [RemoveContentTypeFromListByName(Web, String, String)](FieldAndContentTypeExtensionsRemoveContentTypeFromListByNameWebStringString.md) | Removes content type from list
| [RemoveContentTypeFromListByName(Web, List, String)](FieldAndContentTypeExtensionsRemoveContentTypeFromListByNameWebListString.md) | Removes content type from list
| [RemoveContentTypeFromListById(Web, String, String)](FieldAndContentTypeExtensionsRemoveContentTypeFromListByIdWebStringString.md) | Removes content type from a list
| [RemoveContentTypeFromListById(Web, List, String)](FieldAndContentTypeExtensionsRemoveContentTypeFromListByIdWebListString.md) | Removes content type from a list
| [RemoveContentTypeFromList(Web, List, ContentType)](FieldAndContentTypeExtensionsRemoveContentTypeFromListWebListContentType.md) | Removes content type from a list
| [SetDefaultContentTypeToList(Web, List, String)](FieldAndContentTypeExtensionsSetDefaultContentTypeToListWebListString.md) | Set default content type to list
| [SetDefaultContentTypeToList(Web, List, ContentType)](FieldAndContentTypeExtensionsSetDefaultContentTypeToListWebListContentType.md) | Set default content type to list
| [SetDefaultContentTypeToList(Web, String, String)](FieldAndContentTypeExtensionsSetDefaultContentTypeToListWebStringString.md) | Set default content type to list
| [SetDefaultContentTypeToList(Web, String, ContentType)](FieldAndContentTypeExtensionsSetDefaultContentTypeToListWebStringContentType.md) | Set's default content type list.
| [SetDefaultContentTypeToList(List, String)](FieldAndContentTypeExtensionsSetDefaultContentTypeToListListString.md) | Set's default content type list.
| [SetDefaultContentTypeToList(List, ContentType)](FieldAndContentTypeExtensionsSetDefaultContentTypeToListListContentType.md) | Set default content type to list
| [ReorderContentTypes(List, Collections.Generic.IEnumerable1<String>)](FieldAndContentTypeExtensionsReorderContentTypesListCollections.Generic.IEnumerable1<String>.md) | 
| [SetLocalizationForContentType(Web, String, String, String, String)](FieldAndContentTypeExtensionsSetLocalizationForContentTypeWebStringStringStringString.md) | Set localized labels for content type
| [SetLocalizationForContentType(List, String, String, String, String)](FieldAndContentTypeExtensionsSetLocalizationForContentTypeListStringStringStringString.md) | Set localized labels for content type
| [SetLocalizationForContentType(ContentType, String, String, String)](FieldAndContentTypeExtensionsSetLocalizationForContentTypeContentTypeStringStringString.md) | Set localized labels for content type
| [SetLocalizationForField(Web, Guid, String, String, String)](FieldAndContentTypeExtensionsSetLocalizationForFieldWebGuidStringStringString.md) | Set localized labels for field
| [SetLocalizationForField(Web, String, String, String, String)](FieldAndContentTypeExtensionsSetLocalizationForFieldWebStringStringStringString.md) | Set localized labels for field
| [SetLocalizationForField(Web, Field, String, String, String)](FieldAndContentTypeExtensionsSetLocalizationForFieldWebFieldStringStringString.md) | Set localized labels for field
| [SetLocalizationForField(List, Guid, String, String, String)](FieldAndContentTypeExtensionsSetLocalizationForFieldListGuidStringStringString.md) | Set localized labels for field
| [SetLocalizationForField(List, String, String, String, String)](FieldAndContentTypeExtensionsSetLocalizationForFieldListStringStringStringString.md) | Set localized labels for field
| [SetLocalizationForField(List, Field, String, String, String)](FieldAndContentTypeExtensionsSetLocalizationForFieldListFieldStringStringString.md) | Set localized labels for field
| [SetLocalizationForField(Field, String, String, String)](FieldAndContentTypeExtensionsSetLocalizationForFieldFieldStringStringString.md) | Set localized labels for field
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
