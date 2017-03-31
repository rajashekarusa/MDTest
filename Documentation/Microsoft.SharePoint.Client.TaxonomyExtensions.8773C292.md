Site, String, Guid, String# TaxonomyExtensions.EnsureTermGroup members
Ensures the named group exists, returning a reference to the group, and creating or updating as necessary.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  EnsureTermGroup(Site, String, Guid, String)
```
### Parameters
#### site
Type: [Microsoft.SharePoint.Client.Site](Microsoft.SharePoint.Client.Site.md) 
#### 
#### groupName
Type: [System.String](System.String.md) 
#### 
#### (optional) groupId
Type: [System.Guid](System.Guid.md) 
#### 
#### (optional) groupDescription
Type: [System.String](System.String.md) 
#### 
### Return Value
Type: [Microsoft.SharePoint.Client.Taxonomy.TermGroup](Microsoft.SharePoint.Client.Taxonomy.TermGroup.md)The required term group
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
