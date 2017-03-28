# TaxonomyExtensions
Class for deprecated taxonomy extension methods
**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Classes
System.Object  
## Syntax
```C#
public class TaxonomyExtensions
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [CreateTermGroup(Taxonomy.TermStore, String, Guid, String)](TaxonomyExtensionsCreateTermGroupTaxonomy.TermStoreStringGuidString.md) | Creates a new term group, in the specified term store.
| [EnsureTermGroup(Site, String, Guid, String)](TaxonomyExtensionsEnsureTermGroupSiteStringGuidString.md) | Ensures the named group exists, returning a reference to the group, and creating or updating as necessary.
| [EnsureTermSet(Taxonomy.TermGroup, String, Guid, Nullable1<Int32>, String, Nullable1<Boolean>, String, String)](TaxonomyExtensionsEnsureTermSetTaxonomy.TermGroupStringGuidNullable1<Int32>StringNullable1<Boolean>StringString.md) | 
| [GetDefaultTermStore(Web)](TaxonomyExtensionsGetDefaultTermStoreWeb.md) | Private method used for resolving taxonomy term set for taxonomy field
| [GetTaxonomySession(Site)](TaxonomyExtensionsGetTaxonomySessionSite.md) | Returns a new taxonomy session for the current site
| [GetDefaultKeywordsTermStore(Site)](TaxonomyExtensionsGetDefaultKeywordsTermStoreSite.md) | Returns the default keywords termstore for the current site
| [GetDefaultSiteCollectionTermStore(Site)](TaxonomyExtensionsGetDefaultSiteCollectionTermStoreSite.md) | Returns the default site collection termstore
| [GetTermSetsByName(Site, String, Int32)](TaxonomyExtensionsGetTermSetsByNameSiteStringInt32.md) | Finds a termset by name
| [GetTermGroupByName(Site, String)](TaxonomyExtensionsGetTermGroupByNameSiteString.md) | Finds a termgroup by name
| [GetTermGroupByName(Taxonomy.TermStore, String)](TaxonomyExtensionsGetTermGroupByNameTaxonomy.TermStoreString.md) | Gets the named term group, if it exists in the term store.
| [GetTermGroupById(Site, Guid)](TaxonomyExtensionsGetTermGroupByIdSiteGuid.md) | Finds a termgroup by its ID
| [GetTermByName(Site, Guid, String)](TaxonomyExtensionsGetTermByNameSiteGuidString.md) | Gets a Taxonomy Term by Name
| [AddTermToTermset(Site, Guid, String)](TaxonomyExtensionsAddTermToTermsetSiteGuidString.md) | Adds a term to a given termset
| [AddTermToTermset(Site, Guid, String, Guid)](TaxonomyExtensionsAddTermToTermsetSiteGuidStringGuid.md) | Adds a term to a given termset
| [ImportTerms(Site, String[], Int32, String, Boolean)](TaxonomyExtensionsImportTermsSiteString[]Int32StringBoolean.md) | Imports an array of | delimited strings into the deafult site collection termstore. Specify strings in this format: TermGroup|TermSet|Term E.g. "Locations|Nordics|Sweden"
| [ImportTerms(Site, String[], Int32, Taxonomy.TermStore, String, Boolean)](TaxonomyExtensionsImportTermsSiteString[]Int32Taxonomy.TermStoreStringBoolean.md) | Imports an array of | delimited strings into the deafult site collection termstore. Specify strings in this format: TermGroup|TermSet|Term E.g. "Locations|Nordics|Sweden"
| [AddTermToTerm(Taxonomy.Term, Int32, String, Guid)](TaxonomyExtensionsAddTermToTermTaxonomy.TermInt32StringGuid.md) | 
| [ImportTermSet(Taxonomy.TermGroup, String, Guid, Boolean, Nullable1<Boolean>, String, String)](TaxonomyExtensionsImportTermSetTaxonomy.TermGroupStringGuidBooleanNullable1<Boolean>StringString.md) | 
| [ImportTermSet(Taxonomy.TermGroup, IO.Stream, Guid, Boolean, Nullable1<Boolean>, String, String)](TaxonomyExtensionsImportTermSetTaxonomy.TermGroupIO.StreamGuidBooleanNullable1<Boolean>StringString.md) | 
| [ImportTermSetImplementation(Taxonomy.TermGroup, IO.TextReader, Guid, Collections.Generic.IDictionary2<Guid,Object>, Nullable1<Boolean>, String, String, Boolean&)](TaxonomyExtensionsImportTermSetImplementationTaxonomy.TermGroupIO.TextReaderGuidCollections.Generic.IDictionary2<Guid,Object>Nullable1<Boolean>StringStringBoolean&.md) | 
| [ImportTermSetLineImport(Collections.Generic.IList1<String>, Taxonomy.TermSet, Int32, Int32, Collections.Generic.IDictionary2<Guid,Object>)](TaxonomyExtensionsImportTermSetLineImportCollections.Generic.IList1<String>Taxonomy.TermSetInt32Int32Collections.Generic.IDictionary2<Guid,Object>.md) | 
| [ImportTermSetLineParse(String)](TaxonomyExtensionsImportTermSetLineParseString.md) | 
| [ImportTermSetRemoveExtraTerms(Taxonomy.TermSet, Collections.Generic.IDictionary2<Guid,Object>)](TaxonomyExtensionsImportTermSetRemoveExtraTermsTaxonomy.TermSetCollections.Generic.IDictionary2<Guid,Object>.md) | 
| [ExportTermSet(Site, Guid, Boolean, String)](TaxonomyExtensionsExportTermSetSiteGuidBooleanString.md) | Exports the full list of terms from all termsets in all termstores.
| [ExportTermSet(Site, Guid, Boolean, Taxonomy.TermStore, String)](TaxonomyExtensionsExportTermSetSiteGuidBooleanTaxonomy.TermStoreString.md) | Exports the full list of terms from all termsets in all termstores.
| [ExportAllTerms(Site, Boolean, String)](TaxonomyExtensionsExportAllTermsSiteBooleanString.md) | Exports the full list of terms from all termsets in all termstores.
| [ParseSubTerms(String, Taxonomy.Term, Boolean, String, ClientRuntimeContext)](TaxonomyExtensionsParseSubTermsStringTaxonomy.TermBooleanStringClientRuntimeContext.md) | 
| [NormalizeName(String)](TaxonomyExtensionsNormalizeNameString.md) | 
| [DenormalizeName(String)](TaxonomyExtensionsDenormalizeNameString.md) | 
| [GetTaxonomyItemByPath(Site, String, String)](TaxonomyExtensionsGetTaxonomyItemByPathSiteStringString.md) | Returns a taxonomy item by it's path, e.g. Group|Set|Term
| [ValidateDescription(String, String)](TaxonomyExtensionsValidateDescriptionStringString.md) | 
| [ValidateName(String, String)](TaxonomyExtensionsValidateNameStringString.md) | 
| [SetTaxonomyFieldValueByTermPath(ListItem, String, Guid)](TaxonomyExtensionsSetTaxonomyFieldValueByTermPathListItemStringGuid.md) | Sets a value in a taxonomy field
| [SetTaxonomyFieldValue(ListItem, Guid, String, Guid)](TaxonomyExtensionsSetTaxonomyFieldValueListItemGuidStringGuid.md) | Sets a value of a taxonomy field
| [SetTaxonomyFieldValues(ListItem, Guid, Collections.Generic.IEnumerable1<Collections.Generic.KeyValuePair2<Guid,String>>)](TaxonomyExtensionsSetTaxonomyFieldValuesListItemGuidCollections.Generic.IEnumerable1<Collections.Generic.KeyValuePair2<Guid,String>>.md) | 
| [CleanupTaxonomyHiddenField(Web, FieldCollection, OfficeDevPnP.Core.Entities.TaxonomyFieldCreationInformation)](TaxonomyExtensionsCleanupTaxonomyHiddenFieldWebFieldCollectionOfficeDevPnP.Core.Entities.TaxonomyFieldCreationInformation.md) | 
| [CreateTaxonomyField(Web, OfficeDevPnP.Core.Entities.TaxonomyFieldCreationInformation)](TaxonomyExtensionsCreateTaxonomyFieldWebOfficeDevPnP.Core.Entities.TaxonomyFieldCreationInformation.md) | Can be used to create taxonomy field remotely to web.
| [RemoveTaxonomyFieldByInternalName(Web, String)](TaxonomyExtensionsRemoveTaxonomyFieldByInternalNameWebString.md) | Removes a taxonomy field (site column) and its associated hidden field by internal name
| [RemoveTaxonomyFieldById(Web, Guid)](TaxonomyExtensionsRemoveTaxonomyFieldByIdWebGuid.md) | Removes a taxonomy field (site column) and its associated hidden field by id
| [CreateTaxonomyField(List, OfficeDevPnP.Core.Entities.TaxonomyFieldCreationInformation)](TaxonomyExtensionsCreateTaxonomyFieldListOfficeDevPnP.Core.Entities.TaxonomyFieldCreationInformation.md) | Can be used to create taxonomy field remotely in a list.
| [WireUpTaxonomyField(Web, Field, String, String, Boolean)](TaxonomyExtensionsWireUpTaxonomyFieldWebFieldStringStringBoolean.md) | Wires up MMS field to the specified term set.
| [WireUpTaxonomyField(Web, Field, Taxonomy.TermSet, Boolean)](TaxonomyExtensionsWireUpTaxonomyFieldWebFieldTaxonomy.TermSetBoolean.md) | Wires up MMS field to the specified term set.
| [WireUpTaxonomyField(Web, Field, Taxonomy.Term, Boolean)](TaxonomyExtensionsWireUpTaxonomyFieldWebFieldTaxonomy.TermBoolean.md) | Wires up MMS field to the specified term.
| [WireUpTaxonomyField(Web, Guid, String, String, Boolean)](TaxonomyExtensionsWireUpTaxonomyFieldWebGuidStringStringBoolean.md) | Wires up MMS field to the specified term set.
| [WireUpTaxonomyField(List, Field, Taxonomy.TermSet, Boolean)](TaxonomyExtensionsWireUpTaxonomyFieldListFieldTaxonomy.TermSetBoolean.md) | Wires up MMS field to the specified term set.
| [WireUpTaxonomyField(List, Field, Taxonomy.Term, Boolean)](TaxonomyExtensionsWireUpTaxonomyFieldListFieldTaxonomy.TermBoolean.md) | Wires up MMS field to the specified term.
| [WireUpTaxonomyField(List, Field, String, String, Boolean)](TaxonomyExtensionsWireUpTaxonomyFieldListFieldStringStringBoolean.md) | Wires up MMS field to the specified term set.
| [WireUpTaxonomyField(List, Guid, String, String, Boolean)](TaxonomyExtensionsWireUpTaxonomyFieldListGuidStringStringBoolean.md) | Wires up MMS field to the specified term set.
| [WireUpTaxonomyFieldInternal(Field, Taxonomy.TaxonomyItem, Boolean)](TaxonomyExtensionsWireUpTaxonomyFieldInternalFieldTaxonomy.TaxonomyItemBoolean.md) | Wires up MMS field to the specified term set or term.
| [GetWssIdForTerm(Web, Taxonomy.Term)](TaxonomyExtensionsGetWssIdForTermWebTaxonomy.Term.md) | Returns the Id for a term if present in the TaxonomyHiddenList. Otherwise returns -1;
| [SetTaxonomyFieldDefaultValue(Field, Taxonomy.TaxonomyItem, String, Boolean)](TaxonomyExtensionsSetTaxonomyFieldDefaultValueFieldTaxonomy.TaxonomyItemStringBoolean.md) | Sets the default value for a managed metadata field
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
