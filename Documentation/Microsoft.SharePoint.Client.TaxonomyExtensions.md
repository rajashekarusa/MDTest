# TaxonomyExtensions
Class for deprecated taxonomy extension methods  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Inheritance Hierarchy
System.Object  
## Syntax
```C#
public static class TaxonomyExtensions
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [CreateTermGroup(Taxonomy.TermStore, String, Guid, String)](Microsoft.SharePoint.Client.TaxonomyExtensions.CreateTermGroupTaxonomy.TermStoreStringGuidString.md) | Creates a new term group, in the specified term store.
| [EnsureTermGroup(Site, String, Guid, String)](Microsoft.SharePoint.Client.TaxonomyExtensions.EnsureTermGroupSiteStringGuidString.md) | Ensures the named group exists, returning a reference to the group, and creating or updating as necessary.
| [EnsureTermSet(Taxonomy.TermGroup, String, Guid, Nullable<Int32>, String, Nullable<Boolean>, String, String)](Microsoft.SharePoint.Client.TaxonomyExtensions.EnsureTermSetTaxonomy.TermGroupStringGuidNullable<Int32>StringNullable<Boolean>StringString.md) | 
| [GetDefaultTermStore(Web)](Microsoft.SharePoint.Client.TaxonomyExtensions.GetDefaultTermStoreWeb.md) | Private method used for resolving taxonomy term set for taxonomy field
| [GetTaxonomySession(Site)](Microsoft.SharePoint.Client.TaxonomyExtensions.GetTaxonomySessionSite.md) | Returns a new taxonomy session for the current site
| [GetDefaultKeywordsTermStore(Site)](Microsoft.SharePoint.Client.TaxonomyExtensions.GetDefaultKeywordsTermStoreSite.md) | Returns the default keywords termstore for the current site
| [GetDefaultSiteCollectionTermStore(Site)](Microsoft.SharePoint.Client.TaxonomyExtensions.GetDefaultSiteCollectionTermStoreSite.md) | Returns the default site collection termstore
| [GetTermSetsByName(Site, String, Int32)](Microsoft.SharePoint.Client.TaxonomyExtensions.GetTermSetsByNameSiteStringInt32.md) | Finds a termset by name
| [GetTermGroupByName(Site, String)](Microsoft.SharePoint.Client.TaxonomyExtensions.GetTermGroupByNameSiteString.md) | Finds a termgroup by name
| [GetTermGroupByName(Taxonomy.TermStore, String)](Microsoft.SharePoint.Client.TaxonomyExtensions.GetTermGroupByNameTaxonomy.TermStoreString.md) | Gets the named term group, if it exists in the term store.
| [GetTermGroupById(Site, Guid)](Microsoft.SharePoint.Client.TaxonomyExtensions.GetTermGroupByIdSiteGuid.md) | Finds a termgroup by its ID
| [GetTermByName(Site, Guid, String)](Microsoft.SharePoint.Client.TaxonomyExtensions.GetTermByNameSiteGuidString.md) | Gets a Taxonomy Term by Name
| [AddTermToTermset(Site, Guid, String)](Microsoft.SharePoint.Client.TaxonomyExtensions.AddTermToTermsetSiteGuidString.md) | Adds a term to a given termset
| [AddTermToTermset(Site, Guid, String, Guid)](Microsoft.SharePoint.Client.TaxonomyExtensions.AddTermToTermsetSiteGuidStringGuid.md) | Adds a term to a given termset
| [ImportTerms(Site, String[], Int32, String, Boolean)](Microsoft.SharePoint.Client.TaxonomyExtensions.ImportTermsSiteString[]Int32StringBoolean.md) | Imports an array of | delimited strings into the deafult site collection termstore. Specify strings in this format: TermGroup|TermSet|Term E.g. "Locations|Nordics|Sweden"
| [ImportTerms(Site, String[], Int32, Taxonomy.TermStore, String, Boolean)](Microsoft.SharePoint.Client.TaxonomyExtensions.ImportTermsSiteString[]Int32Taxonomy.TermStoreStringBoolean.md) | Imports an array of | delimited strings into the deafult site collection termstore. Specify strings in this format: TermGroup|TermSet|Term E.g. "Locations|Nordics|Sweden"
| [AddTermToTerm(Taxonomy.Term, Int32, String, Guid)](Microsoft.SharePoint.Client.TaxonomyExtensions.AddTermToTermTaxonomy.TermInt32StringGuid.md) | 
| [ImportTermSet(Taxonomy.TermGroup, String, Guid, Boolean, Nullable<Boolean>, String, String)](Microsoft.SharePoint.Client.TaxonomyExtensions.ImportTermSetTaxonomy.TermGroupStringGuidBooleanNullable<Boolean>StringString.md) | 
| [ImportTermSet(Taxonomy.TermGroup, IO.Stream, Guid, Boolean, Nullable<Boolean>, String, String)](Microsoft.SharePoint.Client.TaxonomyExtensions.ImportTermSetTaxonomy.TermGroupIO.StreamGuidBooleanNullable<Boolean>StringString.md) | 
| [ImportTermSetImplementation(Taxonomy.TermGroup, IO.TextReader, Guid, Collections.Generic.IDictionary<Guid,Object>, Nullable<Boolean>, String, String, Boolean&)](Microsoft.SharePoint.Client.TaxonomyExtensions.ImportTermSetImplementationTaxonomy.TermGroupIO.TextReaderGuidCollections.Generic.IDictionary<Guid,Object>Nullable<Boolean>StringStringBoolean&.md) | 
| [ImportTermSetLineImport(Collections.Generic.IList<String>, Taxonomy.TermSet, Int32, Int32, Collections.Generic.IDictionary<Guid,Object>)](Microsoft.SharePoint.Client.TaxonomyExtensions.ImportTermSetLineImportCollections.Generic.IList<String>Taxonomy.TermSetInt32Int32Collections.Generic.IDictionary<Guid,Object>.md) | 
| [ImportTermSetLineParse(String)](Microsoft.SharePoint.Client.TaxonomyExtensions.ImportTermSetLineParseString.md) | 
| [ImportTermSetRemoveExtraTerms(Taxonomy.TermSet, Collections.Generic.IDictionary<Guid,Object>)](Microsoft.SharePoint.Client.TaxonomyExtensions.ImportTermSetRemoveExtraTermsTaxonomy.TermSetCollections.Generic.IDictionary<Guid,Object>.md) | 
| [ExportTermSet(Site, Guid, Boolean, String)](Microsoft.SharePoint.Client.TaxonomyExtensions.ExportTermSetSiteGuidBooleanString.md) | Exports the full list of terms from all termsets in all termstores.
| [ExportTermSet(Site, Guid, Boolean, Taxonomy.TermStore, String)](Microsoft.SharePoint.Client.TaxonomyExtensions.ExportTermSetSiteGuidBooleanTaxonomy.TermStoreString.md) | Exports the full list of terms from all termsets in all termstores.
| [ExportAllTerms(Site, Boolean, String)](Microsoft.SharePoint.Client.TaxonomyExtensions.ExportAllTermsSiteBooleanString.md) | Exports the full list of terms from all termsets in all termstores.
| [ParseSubTerms(String, Taxonomy.Term, Boolean, String, ClientRuntimeContext)](Microsoft.SharePoint.Client.TaxonomyExtensions.ParseSubTermsStringTaxonomy.TermBooleanStringClientRuntimeContext.md) | 
| [NormalizeName(String)](Microsoft.SharePoint.Client.TaxonomyExtensions.NormalizeNameString.md) | 
| [DenormalizeName(String)](Microsoft.SharePoint.Client.TaxonomyExtensions.DenormalizeNameString.md) | 
| [GetTaxonomyItemByPath(Site, String, String)](Microsoft.SharePoint.Client.TaxonomyExtensions.GetTaxonomyItemByPathSiteStringString.md) | Returns a taxonomy item by it's path, e.g. Group|Set|Term
| [ValidateDescription(String, String)](Microsoft.SharePoint.Client.TaxonomyExtensions.ValidateDescriptionStringString.md) | 
| [ValidateName(String, String)](Microsoft.SharePoint.Client.TaxonomyExtensions.ValidateNameStringString.md) | 
| [SetTaxonomyFieldValueByTermPath(ListItem, String, Guid)](Microsoft.SharePoint.Client.TaxonomyExtensions.SetTaxonomyFieldValueByTermPathListItemStringGuid.md) | Sets a value in a taxonomy field
| [SetTaxonomyFieldValue(ListItem, Guid, String, Guid)](Microsoft.SharePoint.Client.TaxonomyExtensions.SetTaxonomyFieldValueListItemGuidStringGuid.md) | Sets a value of a taxonomy field
| [SetTaxonomyFieldValues(ListItem, Guid, Collections.Generic.IEnumerable<Collections.Generic.KeyValuePair<Guid,String>>)](Microsoft.SharePoint.Client.TaxonomyExtensions.SetTaxonomyFieldValuesListItemGuidCollections.Generic.IEnumerable<Collections.Generic.KeyValuePair<Guid,String>>.md) | 
| [CleanupTaxonomyHiddenField(Web, FieldCollection, OfficeDevPnP.Core.Entities.TaxonomyFieldCreationInformation)](Microsoft.SharePoint.Client.TaxonomyExtensions.CleanupTaxonomyHiddenFieldWebFieldCollectionOfficeDevPnP.Core.Entities.TaxonomyFieldCreationInformation.md) | 
| [CreateTaxonomyField(Web, OfficeDevPnP.Core.Entities.TaxonomyFieldCreationInformation)](Microsoft.SharePoint.Client.TaxonomyExtensions.CreateTaxonomyFieldWebOfficeDevPnP.Core.Entities.TaxonomyFieldCreationInformation.md) | Can be used to create taxonomy field remotely to web.
| [RemoveTaxonomyFieldByInternalName(Web, String)](Microsoft.SharePoint.Client.TaxonomyExtensions.RemoveTaxonomyFieldByInternalNameWebString.md) | Removes a taxonomy field (site column) and its associated hidden field by internal name
| [RemoveTaxonomyFieldById(Web, Guid)](Microsoft.SharePoint.Client.TaxonomyExtensions.RemoveTaxonomyFieldByIdWebGuid.md) | Removes a taxonomy field (site column) and its associated hidden field by id
| [CreateTaxonomyField(List, OfficeDevPnP.Core.Entities.TaxonomyFieldCreationInformation)](Microsoft.SharePoint.Client.TaxonomyExtensions.CreateTaxonomyFieldListOfficeDevPnP.Core.Entities.TaxonomyFieldCreationInformation.md) | Can be used to create taxonomy field remotely in a list.
| [WireUpTaxonomyField(Web, Field, String, String, Boolean)](Microsoft.SharePoint.Client.TaxonomyExtensions.WireUpTaxonomyFieldWebFieldStringStringBoolean.md) | Wires up MMS field to the specified term set.
| [WireUpTaxonomyField(Web, Field, Taxonomy.TermSet, Boolean)](Microsoft.SharePoint.Client.TaxonomyExtensions.WireUpTaxonomyFieldWebFieldTaxonomy.TermSetBoolean.md) | Wires up MMS field to the specified term set.
| [WireUpTaxonomyField(Web, Field, Taxonomy.Term, Boolean)](Microsoft.SharePoint.Client.TaxonomyExtensions.WireUpTaxonomyFieldWebFieldTaxonomy.TermBoolean.md) | Wires up MMS field to the specified term.
| [WireUpTaxonomyField(Web, Guid, String, String, Boolean)](Microsoft.SharePoint.Client.TaxonomyExtensions.WireUpTaxonomyFieldWebGuidStringStringBoolean.md) | Wires up MMS field to the specified term set.
| [WireUpTaxonomyField(List, Field, Taxonomy.TermSet, Boolean)](Microsoft.SharePoint.Client.TaxonomyExtensions.WireUpTaxonomyFieldListFieldTaxonomy.TermSetBoolean.md) | Wires up MMS field to the specified term set.
| [WireUpTaxonomyField(List, Field, Taxonomy.Term, Boolean)](Microsoft.SharePoint.Client.TaxonomyExtensions.WireUpTaxonomyFieldListFieldTaxonomy.TermBoolean.md) | Wires up MMS field to the specified term.
| [WireUpTaxonomyField(List, Field, String, String, Boolean)](Microsoft.SharePoint.Client.TaxonomyExtensions.WireUpTaxonomyFieldListFieldStringStringBoolean.md) | Wires up MMS field to the specified term set.
| [WireUpTaxonomyField(List, Guid, String, String, Boolean)](Microsoft.SharePoint.Client.TaxonomyExtensions.WireUpTaxonomyFieldListGuidStringStringBoolean.md) | Wires up MMS field to the specified term set.
| [WireUpTaxonomyFieldInternal(Field, Taxonomy.TaxonomyItem, Boolean)](Microsoft.SharePoint.Client.TaxonomyExtensions.WireUpTaxonomyFieldInternalFieldTaxonomy.TaxonomyItemBoolean.md) | Wires up MMS field to the specified term set or term.
| [GetWssIdForTerm(Web, Taxonomy.Term)](Microsoft.SharePoint.Client.TaxonomyExtensions.GetWssIdForTermWebTaxonomy.Term.md) | Returns the Id for a term if present in the TaxonomyHiddenList. Otherwise returns -1;
| [SetTaxonomyFieldDefaultValue(Field, Taxonomy.TaxonomyItem, String, Boolean)](Microsoft.SharePoint.Client.TaxonomyExtensions.SetTaxonomyFieldDefaultValueFieldTaxonomy.TaxonomyItemStringBoolean.md) | Sets the default value for a managed metadata field
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
