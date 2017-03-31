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
| [CreateTermGroup(TermStore, String, Guid, String)](Microsoft.SharePoint.Client.TaxonomyExtensions.AE88E0A9.md) | Creates a new term group, in the specified term store.
| [EnsureTermGroup(Site, String, Guid, String)](Microsoft.SharePoint.Client.TaxonomyExtensions.8773C292.md) | Ensures the named group exists, returning a reference to the group, and creating or updating as necessary.
| [EnsureTermSet(TermGroup, String, Guid, Nullable<Int32>, String, Nullable<Boolean>, String, String)](Microsoft.SharePoint.Client.TaxonomyExtensions.DE7DFC70.md) | 
| [GetDefaultTermStore(Web)](Microsoft.SharePoint.Client.TaxonomyExtensions.BB04149A.md) | Private method used for resolving taxonomy term set for taxonomy field
| [GetTaxonomySession(Site)](Microsoft.SharePoint.Client.TaxonomyExtensions.A8117943.md) | Returns a new taxonomy session for the current site
| [GetDefaultKeywordsTermStore(Site)](Microsoft.SharePoint.Client.TaxonomyExtensions.88B3540.md) | Returns the default keywords termstore for the current site
| [GetDefaultSiteCollectionTermStore(Site)](Microsoft.SharePoint.Client.TaxonomyExtensions.DACE4AC5.md) | Returns the default site collection termstore
| [GetTermSetsByName(Site, String, Int32)](Microsoft.SharePoint.Client.TaxonomyExtensions.CB9A8E23.md) | Finds a termset by name
| [GetTermGroupByName(Site, String)](Microsoft.SharePoint.Client.TaxonomyExtensions.E33279E7.md) | Finds a termgroup by name
| [GetTermGroupByName(TermStore, String)](Microsoft.SharePoint.Client.TaxonomyExtensions.F08E91AC.md) | Gets the named term group, if it exists in the term store.
| [GetTermGroupById(Site, Guid)](Microsoft.SharePoint.Client.TaxonomyExtensions.3CD146F5.md) | Finds a termgroup by its ID
| [GetTermByName(Site, Guid, String)](Microsoft.SharePoint.Client.TaxonomyExtensions.950B00C9.md) | Gets a Taxonomy Term by Name
| [AddTermToTermset(Site, Guid, String)](Microsoft.SharePoint.Client.TaxonomyExtensions.8C1FBBAF.md) | Adds a term to a given termset
| [AddTermToTermset(Site, Guid, String, Guid)](Microsoft.SharePoint.Client.TaxonomyExtensions.3589B8AC.md) | Adds a term to a given termset
| [ImportTerms(Site, String[], Int32, String, Boolean)](Microsoft.SharePoint.Client.TaxonomyExtensions.767CE9A0.md) | Imports an array of | delimited strings into the deafult site collection termstore. Specify strings in this format: TermGroup|TermSet|Term E.g. "Locations|Nordics|Sweden"
| [ImportTerms(Site, String[], Int32, TermStore, String, Boolean)](Microsoft.SharePoint.Client.TaxonomyExtensions.DCEDEC05.md) | Imports an array of | delimited strings into the deafult site collection termstore. Specify strings in this format: TermGroup|TermSet|Term E.g. "Locations|Nordics|Sweden"
| [AddTermToTerm(Term, Int32, String, Guid)](Microsoft.SharePoint.Client.TaxonomyExtensions.6F676823.md) | 
| [ImportTermSet(TermGroup, String, Guid, Boolean, Nullable<Boolean>, String, String)](Microsoft.SharePoint.Client.TaxonomyExtensions.3BB4401A.md) | 
| [ImportTermSet(TermGroup, Stream, Guid, Boolean, Nullable<Boolean>, String, String)](Microsoft.SharePoint.Client.TaxonomyExtensions.DEA02E42.md) | 
| [ImportTermSetImplementation(TermGroup, TextReader, Guid, IDictionary<Guid, Object>, Nullable<Boolean>, String, String, Boolean&)](Microsoft.SharePoint.Client.TaxonomyExtensions.B664369D.md) | 
| [ImportTermSetLineImport(IList<String>, TermSet, Int32, Int32, IDictionary<Guid, Object>)](Microsoft.SharePoint.Client.TaxonomyExtensions.D1585E0D.md) | 
| [ImportTermSetLineParse(String)](Microsoft.SharePoint.Client.TaxonomyExtensions.70840563.md) | 
| [ImportTermSetRemoveExtraTerms(TermSet, IDictionary<Guid, Object>)](Microsoft.SharePoint.Client.TaxonomyExtensions.404DF77E.md) | 
| [ExportTermSet(Site, Guid, Boolean, String)](Microsoft.SharePoint.Client.TaxonomyExtensions.A25B0591.md) | Exports the full list of terms from all termsets in all termstores.
| [ExportTermSet(Site, Guid, Boolean, TermStore, String)](Microsoft.SharePoint.Client.TaxonomyExtensions.ECBDE79A.md) | Exports the full list of terms from all termsets in all termstores.
| [ExportAllTerms(Site, Boolean, String)](Microsoft.SharePoint.Client.TaxonomyExtensions.EB0EBF3C.md) | Exports the full list of terms from all termsets in all termstores.
| [ParseSubTerms(String, Term, Boolean, String, ClientRuntimeContext)](Microsoft.SharePoint.Client.TaxonomyExtensions.4A03EA98.md) | 
| [NormalizeName(String)](Microsoft.SharePoint.Client.TaxonomyExtensions.980773B1.md) | 
| [DenormalizeName(String)](Microsoft.SharePoint.Client.TaxonomyExtensions.FCE4464C.md) | 
| [GetTaxonomyItemByPath(Site, String, String)](Microsoft.SharePoint.Client.TaxonomyExtensions.C526145C.md) | Returns a taxonomy item by it's path, e.g. Group|Set|Term
| [ValidateDescription(String, String)](Microsoft.SharePoint.Client.TaxonomyExtensions.AD17341.md) | 
| [ValidateName(String, String)](Microsoft.SharePoint.Client.TaxonomyExtensions.82F4DBA.md) | 
| [SetTaxonomyFieldValueByTermPath(ListItem, String, Guid)](Microsoft.SharePoint.Client.TaxonomyExtensions.5A80EB78.md) | Sets a value in a taxonomy field
| [SetTaxonomyFieldValue(ListItem, Guid, String, Guid)](Microsoft.SharePoint.Client.TaxonomyExtensions.F79BDCAB.md) | Sets a value of a taxonomy field
| [SetTaxonomyFieldValues(ListItem, Guid, IEnumerable<KeyValuePair<Guid, String>>)](Microsoft.SharePoint.Client.TaxonomyExtensions.927E70C0.md) | 
| [CleanupTaxonomyHiddenField(Web, FieldCollection, TaxonomyFieldCreationInformation)](Microsoft.SharePoint.Client.TaxonomyExtensions.6BC8233F.md) | 
| [CreateTaxonomyField(Web, TaxonomyFieldCreationInformation)](Microsoft.SharePoint.Client.TaxonomyExtensions.6008C17A.md) | Can be used to create taxonomy field remotely to web.
| [RemoveTaxonomyFieldByInternalName(Web, String)](Microsoft.SharePoint.Client.TaxonomyExtensions.9F4BB750.md) | Removes a taxonomy field (site column) and its associated hidden field by internal name
| [RemoveTaxonomyFieldById(Web, Guid)](Microsoft.SharePoint.Client.TaxonomyExtensions.20D5705F.md) | Removes a taxonomy field (site column) and its associated hidden field by id
| [CreateTaxonomyField(List, TaxonomyFieldCreationInformation)](Microsoft.SharePoint.Client.TaxonomyExtensions.61031B4.md) | Can be used to create taxonomy field remotely in a list.
| [WireUpTaxonomyField(Web, Field, String, String, Boolean)](Microsoft.SharePoint.Client.TaxonomyExtensions.298466CF.md) | Wires up MMS field to the specified term set.
| [WireUpTaxonomyField(Web, Field, TermSet, Boolean)](Microsoft.SharePoint.Client.TaxonomyExtensions.F35778B0.md) | Wires up MMS field to the specified term set.
| [WireUpTaxonomyField(Web, Field, Term, Boolean)](Microsoft.SharePoint.Client.TaxonomyExtensions.A589D5C2.md) | Wires up MMS field to the specified term.
| [WireUpTaxonomyField(Web, Guid, String, String, Boolean)](Microsoft.SharePoint.Client.TaxonomyExtensions.C812B6C0.md) | Wires up MMS field to the specified term set.
| [WireUpTaxonomyField(List, Field, TermSet, Boolean)](Microsoft.SharePoint.Client.TaxonomyExtensions.1A55B0C7.md) | Wires up MMS field to the specified term set.
| [WireUpTaxonomyField(List, Field, Term, Boolean)](Microsoft.SharePoint.Client.TaxonomyExtensions.5A4045B7.md) | Wires up MMS field to the specified term.
| [WireUpTaxonomyField(List, Field, String, String, Boolean)](Microsoft.SharePoint.Client.TaxonomyExtensions.985CC78B.md) | Wires up MMS field to the specified term set.
| [WireUpTaxonomyField(List, Guid, String, String, Boolean)](Microsoft.SharePoint.Client.TaxonomyExtensions.A5F7F2D0.md) | Wires up MMS field to the specified term set.
| [WireUpTaxonomyFieldInternal(Field, TaxonomyItem, Boolean)](Microsoft.SharePoint.Client.TaxonomyExtensions.C3E90809.md) | Wires up MMS field to the specified term set or term.
| [GetWssIdForTerm(Web, Term)](Microsoft.SharePoint.Client.TaxonomyExtensions.32328193.md) | Returns the Id for a term if present in the TaxonomyHiddenList. Otherwise returns -1;
| [SetTaxonomyFieldDefaultValue(Field, TaxonomyItem, String, Boolean)](Microsoft.SharePoint.Client.TaxonomyExtensions.8F744F2E.md) | Sets the default value for a managed metadata field
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
