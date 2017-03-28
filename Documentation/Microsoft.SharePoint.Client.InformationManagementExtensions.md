# InformationManagementExtensions
Class that holds deprecated information management extension methods  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Classes
System.Object  
## Syntax
```C#
public class InformationManagementExtensions
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [HasSitePolicyApplied(Web)](InformationManagementExtensionsHasSitePolicyAppliedWeb.md) | Does this web have a site policy applied?
| [GetSiteExpirationDate(Web)](InformationManagementExtensionsGetSiteExpirationDateWeb.md) | Gets the site expiration date
| [GetSiteCloseDate(Web)](InformationManagementExtensionsGetSiteCloseDateWeb.md) | Gets the site closure date
| [GetSitePolicies(Web)](InformationManagementExtensionsGetSitePoliciesWeb.md) | Gets a list of the available site policies
| [GetAppliedSitePolicy(Web)](InformationManagementExtensionsGetAppliedSitePolicyWeb.md) | Gets the site policy that currently is applied
| [GetSitePolicyByName(Web, String)](InformationManagementExtensionsGetSitePolicyByNameWebString.md) | Gets the site policy with the given name
| [ApplySitePolicy(Web, String)](InformationManagementExtensionsApplySitePolicyWebString.md) | Apply a policy to a site
| [IsClosedBySitePolicy(Web)](InformationManagementExtensionsIsClosedBySitePolicyWeb.md) | Check if a site is closed
| [SetClosedBySitePolicy(Web)](InformationManagementExtensionsSetClosedBySitePolicyWeb.md) | Close a site, if it has a site policy applied and is currently not closed
| [SetOpenBySitePolicy(Web)](InformationManagementExtensionsSetOpenBySitePolicyWeb.md) | Open a site, if it has a site policy applied and is currently closed
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
