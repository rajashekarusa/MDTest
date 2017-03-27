# WebAPIContext
This class holds the information that's passed from the SharePoint app to the "Register" WebAPI service call
**Namespace:** [OfficeDevPnP.Core.WebAPI](OfficeDevPnP.Core.WebAPI.md)
**Assembly:** OfficeDevPnP.Core.dll
## Classes
System.Object
## Syntax
```C#
public class WebAPIContext```
## Constructors
|**Name**|**Description**|
|:-----|:-----|
| [WebAPIContext()](WebAPIContextconstructor1details.md) | 
## Properties
|**Name**|**Description**|
|:-----|:-----|
| [CacheKey](WebAPIContext.CacheKey.md) | The cacheKey that will be used. The cache key is unique for each combination of user name, user name issuer, application, and farm.
| [Token](WebAPIContext.Token.md) | The SharePoint context token. This will be used at the WebAPI level to obtain an access token
| [HostWebUrl](WebAPIContext.HostWebUrl.md) | Url of the SharePoint host web. Needed to obtain an access token
| [AppWebUrl](WebAPIContext.AppWebUrl.md) | Url if the SharePoint app web. Needed to obtain an access token
| [ClientId](WebAPIContext.ClientId.md) | ClientId of the SharePoint app that's being registered. Needed to obtain an access token
| [ClientSecret](WebAPIContext.ClientSecret.md) | ClientSecret of the SharePoint app that's being registered. Needed to obtain an access token
| [HostedAppHostName](WebAPIContext.HostedAppHostName.md) | If the AppWebUrl is null then this value will be used. Needed to obtain an access token
## See also
- [OfficeDevPnP.Core.WebAPI](OfficeDevPnP.Core.WebAPI.md)
