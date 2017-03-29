# ClientContextExtensions
Class that holds the deprecated clientcontext methods  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Inheritance Hierarchy
System.Object  
## Syntax
```C#
public static class ClientContextExtensions
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [Clone(ClientRuntimeContext, String)](Microsoft.SharePoint.Client.ClientContextExtensions.CloneClientRuntimeContextString.md) | Clones a ClientContext object while "taking over" the security context of the existing ClientContext instance
| [ExecuteQueryRetry(ClientRuntimeContext, Int32, Int32)](Microsoft.SharePoint.Client.ClientContextExtensions.ExecuteQueryRetryClientRuntimeContextInt32Int32.md) | 
| [ExecuteQueryImplementation(ClientRuntimeContext, Int32, Int32)](Microsoft.SharePoint.Client.ClientContextExtensions.ExecuteQueryImplementationClientRuntimeContextInt32Int32.md) | 
| [Clone(ClientRuntimeContext, Uri)](Microsoft.SharePoint.Client.ClientContextExtensions.CloneClientRuntimeContextUri.md) | Clones a ClientContext object while "taking over" the security context of the existing ClientContext instance
| [GetSiteCollectionContext(ClientRuntimeContext)](Microsoft.SharePoint.Client.ClientContextExtensions.GetSiteCollectionContextClientRuntimeContext.md) | Gets a site collection context for the passed web. This site collection client context uses the same credentials as the passed client context
| [IsAppOnly(ClientRuntimeContext)](Microsoft.SharePoint.Client.ClientContextExtensions.IsAppOnlyClientRuntimeContext.md) | Checks if the used ClientContext is app-only
| [HasMinimalServerLibraryVersion(ClientRuntimeContext, String)](Microsoft.SharePoint.Client.ClientContextExtensions.HasMinimalServerLibraryVersionClientRuntimeContextString.md) | Checks the server library version of the context for a minimally required version
| [HasMinimalServerLibraryVersion(ClientRuntimeContext, Version)](Microsoft.SharePoint.Client.ClientContextExtensions.HasMinimalServerLibraryVersionClientRuntimeContextVersion.md) | 
| [GetCallingPnPMethod()](Microsoft.SharePoint.Client.ClientContextExtensions.GetCallingPnPMethod.md) | 
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
