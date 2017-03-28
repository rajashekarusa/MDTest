# TimerJob
Abstract base class for creating timer jobs (background processes) that operate against SharePoint sites. These timer jobs 
            are designed to use the CSOM API and thus can run on any server that can communicate with SharePoint.  

**Namespace:** [OfficeDevPnP.Core.Framework.TimerJobs](OfficeDevPnP.Core.Framework.TimerJobs.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Classes
System.Object  
## Syntax
```C#
public class TimerJob
```
## Constructors
|**Name**|**Description**|
|:-----|:-----|
| [TimerJob(String)](TimerJobconstructor1details.md) | 
| [TimerJob(String, String)](TimerJobconstructor1details.md) | 
| [TimerJob(String, String, String)](TimerJobconstructor1details.md) | 
## Properties
|**Name**|**Description**|
|:-----|:-----|
| [Name](TimerJob.Name.md) | Gets the name of this timer job
| [Version](TimerJob.Version.md) | Gets the version of this timer job
| [ConfigurationData](TimerJob.ConfigurationData.md) | Gets or sets additional timer job configuration data
| [ManageState](TimerJob.ManageState.md) | Gets and sets the state management value: when true the timer job will automatically handle state by 
            storing a json serialized class as a web property bag entry. Default value is false
| [IsRunning](TimerJob.IsRunning.md) | Is this timer job running?
| [UseThreading](TimerJob.UseThreading.md) | Can this timer job use multiple threads. Defaults to true
| [MaximumThreads](TimerJob.MaximumThreads.md) | How many threads can be used by this timer job. Default value is 5.
| [AuthenticationType](TimerJob.AuthenticationType.md) | Gets the authentication type that the timer job will use. This will be set as part 
            of the UseOffice365Authentication and UseNetworkCredentialsAuthentication methods
| [SharePointVersion](TimerJob.SharePointVersion.md) | Gets or sets the SharePoint version. Default value is detected based on the laoded CSOM assembly version, but can be overriden
            in case you want to for example use v16 assemblies in v15 (on-premises)
| [Realm](TimerJob.Realm.md) | Realm will be automatically defined, but there's an option to manually specify it which may 
            be needed when did an override of ResolveAddedSites and specify your sites.
| [TenantAdminSite](TimerJob.TenantAdminSite.md) | Option to specify the tenant admin site. For MT this typically is not needed since we can detect the tenant admin site, but for on premises and DvNext this is needed
| [ExpandSubSites](TimerJob.ExpandSubSites.md) | Does the timerjob need to fire as well for every sub site in the site?
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [add_TimerJobRun(TimerJobRunHandler)](TimerJobadd_TimerJobRunTimerJobRunHandler.md) | 
| [remove_TimerJobRun(TimerJobRunHandler)](TimerJobremove_TimerJobRunTimerJobRunHandler.md) | 
| [Run()](TimerJobRun.md) | Triggers the timer job to start running
| [DoWorkBatch(Collections.Generic.List1<String>)](TimerJobDoWorkBatchCollections.Generic.List1<String>.md) | 
| [DoWork(String)](TimerJobDoWorkString.md) | Processes the amount of work that will be done for a single site/web
| [OnTimerJobRun(TimerJobRunEventArgs)](TimerJobOnTimerJobRunTimerJobRunEventArgs.md) | Triggers the event to fire and deals with all the pre/post processing needed to automatically manage state
| [CreateWorkBatches()](TimerJobCreateWorkBatches.md) | Creates batches of sites to process. Batch size is based on max number of threads
| [UseOffice365Authentication(String, String)](TimerJobUseOffice365AuthenticationStringString.md) | Prepares the timerjob to operate against Office 365 with user and password credentials. Sets AuthenticationType to AuthenticationType.Office365
| [UseOffice365Authentication(String, Security.SecureString)](TimerJobUseOffice365AuthenticationStringSecurity.SecureString.md) | Prepares the timerjob to operate against Office 365 with user and password credentials. Sets AuthenticationType to AuthenticationType.Office365
| [UseOffice365Authentication(String)](TimerJobUseOffice365AuthenticationString.md) | Prepares the timerjob to operate against Office 365 with user and password credentials which are retrieved via the windows Credential Manager. Also sets AuthenticationType to AuthenticationType.Office365
| [UseNetworkCredentialsAuthentication(String, String, String)](TimerJobUseNetworkCredentialsAuthenticationStringStringString.md) | Prepares the timerjob to operate against SharePoint on-premises with user name password credentials. Sets AuthenticationType to AuthenticationType.NetworkCredentials
| [UseNetworkCredentialsAuthentication(String, Security.SecureString, String)](TimerJobUseNetworkCredentialsAuthenticationStringSecurity.SecureStringString.md) | Prepares the timerjob to operate against SharePoint on-premises with user name password credentials. Sets AuthenticationType to AuthenticationType.NetworkCredentials
| [UseNetworkCredentialsAuthentication(String)](TimerJobUseNetworkCredentialsAuthenticationString.md) | Prepares the timerjob to operate against SharePoint on-premises with user name password credentials which are retrieved via the windows Credential Manager. Sets AuthenticationType to AuthenticationType.NetworkCredentials
| [UseAppOnlyAuthentication(String, String)](TimerJobUseAppOnlyAuthenticationStringString.md) | Prepares the timerjob to operate against SharePoint on-premises with app-only credentials. Sets AuthenticationType to AuthenticationType.AppOnly
| [UseAzureADAppOnlyAuthentication(String, String, String, String)](TimerJobUseAzureADAppOnlyAuthenticationStringStringStringString.md) | Prepares the timerjob to operate against SharePoint Only with Azure AD app-only credentials. Sets AuthenticationType to AuthenticationType.AzureADAppOnly
| [UseAzureADAppOnlyAuthentication(String, String, String, Security.SecureString)](TimerJobUseAzureADAppOnlyAuthenticationStringStringStringSecurity.SecureString.md) | Prepares the timerjob to operate against SharePoint Only with Azure AD app-only credentials. Sets AuthenticationType to AuthenticationType.AzureADAppOnly
| [UseAzureADAppOnlyAuthentication(String, String, Security.Cryptography.X509Certificates.X509Certificate2)](TimerJobUseAzureADAppOnlyAuthenticationStringStringSecurity.Cryptography.X509Certificates.X509Certificate2.md) | Prepares the timerjob to operate against SharePoint Only with Azure AD app-only credentials. Sets AuthenticationType to AuthenticationType.AzureADAppOnly
| [Clone(TimerJob)](TimerJobCloneTimerJob.md) | Takes over the settings from the passed timer job. Is useful when you run multiple jobs in a row or chain job execution. Settings that are taken over are all the authentication, enumeration settings and SharePointVersion
| [GetAuthenticationManager(String)](TimerJobGetAuthenticationManagerString.md) | Get an AuthenticationManager instance per host Url. Needed to make this work properly, else we're getting access denied because of Invalid audience Uri
| [SetEnumerationCredentials(String, String)](TimerJobSetEnumerationCredentialsStringString.md) | Provides the timer job with the enumeration credentials. For Office 365 username and password is sufficient
| [SetEnumerationCredentials(String, Security.SecureString)](TimerJobSetEnumerationCredentialsStringSecurity.SecureString.md) | Provides the timer job with the enumeration credentials. For Office 365 username and password is sufficient
| [SetEnumerationCredentials(String, String, String)](TimerJobSetEnumerationCredentialsStringStringString.md) | Provides the timer job with the enumeration credentials. For SharePoint on-premises username, password and domain are needed
| [SetEnumerationCredentials(String, Security.SecureString, String)](TimerJobSetEnumerationCredentialsStringSecurity.SecureStringString.md) | Provides the timer job with the enumeration credentials. For SharePoint on-premises username, password and domain are needed
| [SetEnumerationCredentials(String)](TimerJobSetEnumerationCredentialsString.md) | Provides the timer job with the enumeration credentials. For SharePoint on-premises username, password and domain are needed
| [AddSite(String)](TimerJobAddSiteString.md) | Adds a site Url or wildcard site Url to the collection of sites that the timer job will process
| [ClearAddedSites()](TimerJobClearAddedSites.md) | Clears the list of added site Url's and/or wildcard site Url's
| [UpdateAddedSites(Collections.Generic.List1<String>)](TimerJobUpdateAddedSitesCollections.Generic.List1<String>.md) | 
| [ResolveAddedSites(Collections.Generic.List1<String>)](TimerJobResolveAddedSitesCollections.Generic.List1<String>.md) | 
| [DoExpandBatch(Collections.Generic.List1<String>, Collections.Generic.List1<String>)](TimerJobDoExpandBatchCollections.Generic.List1<String>Collections.Generic.List1<String>.md) | 
| [CreateExpandBatches(Collections.Generic.List1<String>)](TimerJobCreateExpandBatchesCollections.Generic.List1<String>.md) | 
| [ExpandSite(Collections.Generic.List1<String>, String)](TimerJobExpandSiteCollections.Generic.List1<String>String.md) | 
| [CreateClientContext(String)](TimerJobCreateClientContextString.md) | Creates a ClientContext object based on the set AuthenticationType and the used version of SharePoint
| [ResolveSite(String, Collections.Generic.List1<String>)](TimerJobResolveSiteStringCollections.Generic.List1<String>.md) | 
| [GetAllSubSites(Microsoft.SharePoint.Client.Site)](TimerJobGetAllSubSitesMicrosoft.SharePoint.Client.Site.md) | Gets all sub sites for a given site
| [IsValidUrl(String)](TimerJobIsValidUrlString.md) | Verifies if the passed Url has a valid structure
| [GetSharePointVersion()](TimerJobGetSharePointVersion.md) | Gets the current SharePoint version based on the loaded assembly
| [GetTenantAdminSite(String)](TimerJobGetTenantAdminSiteString.md) | Gets the tenant admin site based on the tenant name provided when setting the authentication details
| [GetTopLevelSite(String)](TimerJobGetTopLevelSiteString.md) | Gets the top level site for the given url
| [GetRootSite(String)](TimerJobGetRootSiteString.md) | Gets the root site for a given site Url
| [NormalizedTimerJobName(String)](TimerJobNormalizedTimerJobNameString.md) | Normalizes the timer job name
| [IsInternalServerErrorException(Exception)](TimerJobIsInternalServerErrorExceptionException.md) | Returns true if the exception was a "The remote server returned an error: (500) Internal Server Error"
| [IsNotFoundException(Exception)](TimerJobIsNotFoundExceptionException.md) | Returns true if the exception was a "The remote server returned an error: (404) Not Found"
## See also
- [OfficeDevPnP.Core.Framework.TimerJobs](OfficeDevPnP.Core.Framework.TimerJobs.md)
