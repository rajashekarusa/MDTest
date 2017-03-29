# InformationManagementExtensions
Class that holds deprecated information management extension methods  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Inheritance Hierarchy
System.Object  
## Syntax
```C#
public static class InformationManagementExtensions
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [HasSitePolicyApplied(Web)](Microsoft.SharePoint.Client.InformationManagementExtensions.HasSitePolicyAppliedWeb.md) | Does this web have a site policy applied?
| [GetSiteExpirationDate(Web)](Microsoft.SharePoint.Client.InformationManagementExtensions.GetSiteExpirationDateWeb.md) | Gets the site expiration date
| [GetSiteCloseDate(Web)](Microsoft.SharePoint.Client.InformationManagementExtensions.GetSiteCloseDateWeb.md) | Gets the site closure date
| [GetSitePolicies(Web)](Microsoft.SharePoint.Client.InformationManagementExtensions.GetSitePoliciesWeb.md) | Gets a list of the available site policies
| [GetAppliedSitePolicy(Web)](Microsoft.SharePoint.Client.InformationManagementExtensions.GetAppliedSitePolicyWeb.md) | Gets the site policy that currently is applied
| [GetSitePolicyByName(Web, String)](Microsoft.SharePoint.Client.InformationManagementExtensions.GetSitePolicyByNameWebString.md) | Gets the site policy with the given name
| [ApplySitePolicy(Web, String)](Microsoft.SharePoint.Client.InformationManagementExtensions.ApplySitePolicyWebString.md) | Apply a policy to a site
| [IsClosedBySitePolicy(Web)](Microsoft.SharePoint.Client.InformationManagementExtensions.IsClosedBySitePolicyWeb.md) | Check if a site is closed
| [SetClosedBySitePolicy(Web)](Microsoft.SharePoint.Client.InformationManagementExtensions.SetClosedBySitePolicyWeb.md) | Close a site, if it has a site policy applied and is currently not closed
| [SetOpenBySitePolicy(Web)](Microsoft.SharePoint.Client.InformationManagementExtensions.SetOpenBySitePolicyWeb.md) | Open a site, if it has a site policy applied and is currently closed
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
