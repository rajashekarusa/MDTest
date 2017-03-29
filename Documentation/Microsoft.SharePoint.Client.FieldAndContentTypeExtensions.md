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
| [CreateField(Web, OfficeDevPnP.Core.Entities.FieldCreationInformation, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.CreateFieldWebOfficeDevPnP.Core.Entities.FieldCreationInformationBoolean.md) | Create field to web remotely
| [CreateField(Web, OfficeDevPnP.Core.Entities.FieldCreationInformation, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.CreateFieldWebOfficeDevPnP.Core.Entities.FieldCreationInformationBoolean.md) | 
| [CreateField(Web, String, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.CreateFieldWebStringBoolean.md) | Create field to web remotely
| [RemoveFieldByInternalName(Web, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.RemoveFieldByInternalNameWebString.md) | Removes a field by specifying its internal name
| [RemoveFieldById(Web, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.RemoveFieldByIdWebString.md) | Removes a field by specifying its ID
| [CreateFieldsFromXMLFile(Web, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.CreateFieldsFromXMLFileWebString.md) | Creates fields from feature element xml file schema. XML file can contain one or many field definitions created using classic feature framework structure.
| [CreateFieldsFromXMLString(Web, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.CreateFieldsFromXMLStringWebString.md) | Creates fields from feature element xml file schema. XML file can contain one or many field definitions created using classic feature framework structure.
| [CreateFieldsFromXML(Web, Xml.Linq.XDocument)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.CreateFieldsFromXMLWebXml.Linq.XDocument.md) | Creates field from xml structure which follows the classic feature framework structure
| [FieldExistsById(Web, Guid, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.FieldExistsByIdWebGuidBoolean.md) | Returns if the field is found
| [GetFieldById(Web, Guid, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.GetFieldByIdWebGuidBoolean.md) | Returns the field if it exists. Null if it does not exist.
| [GetFieldById(Web, Guid, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.GetFieldByIdWebGuidBoolean.md) | 
| [GetFieldById(List, Guid)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.GetFieldByIdListGuid.md) | Returns the field if it exists. Null if it does not exist.
| [GetFieldById(List, Guid)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.GetFieldByIdListGuid.md) | 
| [GetFieldByInternalName(Web, String, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.GetFieldByInternalNameWebStringBoolean.md) | Returns the field if it exists. Null if does not exist.
| [GetFieldByName(FieldCollection, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.GetFieldByNameFieldCollectionString.md) | Returns the field if it exists. Null if it does not exist.
| [GetFieldByName(FieldCollection, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.GetFieldByNameFieldCollectionString.md) | 
| [GetFieldByInternalName(FieldCollection, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.GetFieldByInternalNameFieldCollectionString.md) | Returns the field if it exists. Null if it does not exist.
| [GetFieldByInternalName(FieldCollection, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.GetFieldByInternalNameFieldCollectionString.md) | 
| [FieldExistsByName(Web, String, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.FieldExistsByNameWebStringBoolean.md) | Returns if the field is found
| [FieldExistsById(Web, String, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.FieldExistsByIdWebStringBoolean.md) | Does field exist in web
| [FieldExistsByNameInContentType(Web, String, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.FieldExistsByNameInContentTypeWebStringString.md) | Field exists in content type
| [FieldExistsByNameInContentType(ContentType, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.FieldExistsByNameInContentTypeContentTypeString.md) | Checks if a field exists in a content type by id
| [SetJsLinkCustomizations(Field, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.SetJsLinkCustomizationsFieldString.md) | Adds jsLink to a field.
| [CreateField(List, OfficeDevPnP.Core.Entities.FieldCreationInformation, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.CreateFieldListOfficeDevPnP.Core.Entities.FieldCreationInformationBoolean.md) | Adds field to a list
| [CreateField(List, OfficeDevPnP.Core.Entities.FieldCreationInformation, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.CreateFieldListOfficeDevPnP.Core.Entities.FieldCreationInformationBoolean.md) | 
| [CreateFieldBase(FieldCollection, OfficeDevPnP.Core.Entities.FieldCreationInformation, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.CreateFieldBaseFieldCollectionOfficeDevPnP.Core.Entities.FieldCreationInformationBoolean.md) | Base implementation for creating fields
| [FormatFieldXml(OfficeDevPnP.Core.Entities.FieldCreationInformation)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.FormatFieldXmlOfficeDevPnP.Core.Entities.FieldCreationInformation.md) | Formats a fieldcreationinformation object into Field CAML xml.
| [CreateField(List, String, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.CreateFieldListStringBoolean.md) | Adds a field to a list
| [FieldExistsById(List, Guid)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.FieldExistsByIdListGuid.md) | Returns if the field is found
| [FieldExistsById(List, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.FieldExistsByIdListString.md) | Returns if the field is found, query based on the ID
| [FieldExistsByName(List, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.FieldExistsByNameListString.md) | Field exists in list by name
| [GetFields(List, String[])](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.GetFieldsListString[].md) | Gets a list of fields from a list by names.
| [SetJsLinkCustomizations(List, String, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.SetJsLinkCustomizationsListStringString.md) | Adds jsLink to a list field.
| [ParseAdditionalAttributes(String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.ParseAdditionalAttributesString.md) | Helper method to parse Key="Value" strings into a keyvaluepair
| [AddContentTypeToListById(Web, String, String, Boolean, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.AddContentTypeToListByIdWebStringStringBooleanBoolean.md) | Adds content type to list
| [AddContentTypeToListByName(Web, String, String, Boolean, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.AddContentTypeToListByNameWebStringStringBooleanBoolean.md) | Adds content type to list
| [AddContentTypeToList(Web, String, ContentType, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.AddContentTypeToListWebStringContentTypeBoolean.md) | Adds content type to list
| [AddContentTypeToListById(List, String, Boolean, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.AddContentTypeToListByIdListStringBooleanBoolean.md) | Add content type to list
| [AddContentTypeToListByName(List, String, Boolean, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.AddContentTypeToListByNameListStringBooleanBoolean.md) | Add content type to list
| [AddContentTypeToList(List, ContentType, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.AddContentTypeToListListContentTypeBoolean.md) | Add content type to list
| [AddFieldById(ContentType, String, Boolean, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.AddFieldByIdContentTypeStringBooleanBoolean.md) | Associates field to content type
| [AddFieldById(ContentType, Guid, Boolean, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.AddFieldByIdContentTypeGuidBooleanBoolean.md) | Associates field to content type
| [AddFieldByName(ContentType, String, Boolean, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.AddFieldByNameContentTypeStringBooleanBoolean.md) | Associates field to content type
| [AddFieldToContentTypeById(Web, String, String, Boolean, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.AddFieldToContentTypeByIdWebStringStringBooleanBoolean.md) | Associates field to content type
| [AddFieldToContentTypeByName(Web, String, Guid, Boolean, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.AddFieldToContentTypeByNameWebStringGuidBooleanBoolean.md) | Associates field to content type
| [AddFieldToContentType(Web, ContentType, Field, Boolean, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.AddFieldToContentTypeWebContentTypeFieldBooleanBoolean.md) | Associates field to content type
| [BestMatchContentTypeId(List, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.BestMatchContentTypeIdListString.md) | Searches the list content types and returns the content type identifier (ID) that is the nearest match to the specified content type ID.
| [BestMatchContentTypeIdImplementation(List, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.BestMatchContentTypeIdImplementationListString.md) | 
| [ContentTypeExistsById(Web, String, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.ContentTypeExistsByIdWebStringBoolean.md) | Does content type exists in the web
| [ContentTypeExistsByName(Web, String, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.ContentTypeExistsByNameWebStringBoolean.md) | Does content type exists in the web
| [ContentTypeExistsById(Web, String, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.ContentTypeExistsByIdWebStringString.md) | Does content type exist in web
| [ContentTypeExistsById(List, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.ContentTypeExistsByIdListString.md) | Does content type exist in list
| [ContentTypeExistsByName(Web, String, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.ContentTypeExistsByNameWebStringString.md) | Does content type exist in web
| [ContentTypeExistsByName(List, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.ContentTypeExistsByNameListString.md) | Does content type exist in list
| [CreateContentTypeFromXMLFile(Web, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.CreateContentTypeFromXMLFileWebString.md) | Create a content type based on the classic feature framework structure.
| [CreateContentTypeFromXMLString(Web, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.CreateContentTypeFromXMLStringWebString.md) | Create a content type based on the classic feature framework structure.
| [CreateContentTypeFromXML(Web, Xml.Linq.XDocument)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.CreateContentTypeFromXMLWebXml.Linq.XDocument.md) | Create a content type based on the classic feature framework structure.
| [CreateContentType(Web, String, String, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.CreateContentTypeWebStringStringString.md) | Create new content type to web
| [CreateContentType(Web, String, String, String, String, ContentType)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.CreateContentTypeWebStringStringStringStringContentType.md) | Create new content type to web
| [DeleteContentTypeByName(Web, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.DeleteContentTypeByNameWebString.md) | Deletes a content type from the web by name
| [DeleteContentTypeById(Web, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.DeleteContentTypeByIdWebString.md) | Deletes a content type from the web by id
| [GetContentTypeByName(Web, String, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.GetContentTypeByNameWebStringBoolean.md) | Return content type by name
| [GetContentTypeById(Web, String, Boolean)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.GetContentTypeByIdWebStringBoolean.md) | Return content type by Id
| [GetContentTypeByName(List, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.GetContentTypeByNameListString.md) | Return content type by name
| [GetContentTypeById(List, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.GetContentTypeByIdListString.md) | Return content type by Id
| [BestMatch(ContentTypeCollection, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.BestMatchContentTypeCollectionString.md) | Searches for the content type with the closest match to the value of the specified content type ID. If the search finds two matches, the shorter ID is returned.
| [RemoveContentTypeFromListByName(Web, String, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.RemoveContentTypeFromListByNameWebStringString.md) | Removes content type from list
| [RemoveContentTypeFromListByName(Web, List, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.RemoveContentTypeFromListByNameWebListString.md) | Removes content type from list
| [RemoveContentTypeFromListById(Web, String, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.RemoveContentTypeFromListByIdWebStringString.md) | Removes content type from a list
| [RemoveContentTypeFromListById(Web, List, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.RemoveContentTypeFromListByIdWebListString.md) | Removes content type from a list
| [RemoveContentTypeFromList(Web, List, ContentType)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.RemoveContentTypeFromListWebListContentType.md) | Removes content type from a list
| [SetDefaultContentTypeToList(Web, List, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.SetDefaultContentTypeToListWebListString.md) | Set default content type to list
| [SetDefaultContentTypeToList(Web, List, ContentType)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.SetDefaultContentTypeToListWebListContentType.md) | Set default content type to list
| [SetDefaultContentTypeToList(Web, String, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.SetDefaultContentTypeToListWebStringString.md) | Set default content type to list
| [SetDefaultContentTypeToList(Web, String, ContentType)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.SetDefaultContentTypeToListWebStringContentType.md) | Set's default content type list.
| [SetDefaultContentTypeToList(List, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.SetDefaultContentTypeToListListString.md) | Set's default content type list.
| [SetDefaultContentTypeToList(List, ContentType)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.SetDefaultContentTypeToListListContentType.md) | Set default content type to list
| [ReorderContentTypes(List, Collections.Generic.IEnumerable<String>)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.ReorderContentTypesListCollections.Generic.IEnumerable<String>.md) | 
| [SetLocalizationForContentType(Web, String, String, String, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.SetLocalizationForContentTypeWebStringStringStringString.md) | Set localized labels for content type
| [SetLocalizationForContentType(List, String, String, String, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.SetLocalizationForContentTypeListStringStringStringString.md) | Set localized labels for content type
| [SetLocalizationForContentType(ContentType, String, String, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.SetLocalizationForContentTypeContentTypeStringStringString.md) | Set localized labels for content type
| [SetLocalizationForField(Web, Guid, String, String, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.SetLocalizationForFieldWebGuidStringStringString.md) | Set localized labels for field
| [SetLocalizationForField(Web, String, String, String, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.SetLocalizationForFieldWebStringStringStringString.md) | Set localized labels for field
| [SetLocalizationForField(Web, Field, String, String, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.SetLocalizationForFieldWebFieldStringStringString.md) | Set localized labels for field
| [SetLocalizationForField(List, Guid, String, String, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.SetLocalizationForFieldListGuidStringStringString.md) | Set localized labels for field
| [SetLocalizationForField(List, String, String, String, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.SetLocalizationForFieldListStringStringStringString.md) | Set localized labels for field
| [SetLocalizationForField(List, Field, String, String, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.SetLocalizationForFieldListFieldStringStringString.md) | Set localized labels for field
| [SetLocalizationForField(Field, String, String, String)](Microsoft.SharePoint.Client.FieldAndContentTypeExtensions.SetLocalizationForFieldFieldStringStringString.md) | Set localized labels for field
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
