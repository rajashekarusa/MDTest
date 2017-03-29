# TimerJob
Abstract base class for creating timer jobs (background processes) that operate against SharePoint sites. These timer jobs 
            are designed to use the CSOM API and thus can run on any server that can communicate with SharePoint.  

**Namespace:** [OfficeDevPnP.Core.Framework.TimerJobs](OfficeDevPnP.Core.Framework.TimerJobs.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Inheritance Hierarchy
System.Object  
## Syntax
```C#
public class TimerJob
```
## Constructors
|**Name**|**Description**|
|:-----|:-----|
| [TimerJob(String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.Constructor1details.md) | 
| [TimerJob(String, String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.Constructor2details.md) | 
| [TimerJob(String, String, String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.Constructor3details.md) | 
## Properties
|**Name**|**Description**|
|:-----|:-----|
| [Name](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.Name.md) | Gets the name of this timer job
| [Version](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.Version.md) | Gets the version of this timer job
| [ConfigurationData](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.ConfigurationData.md) | Gets or sets additional timer job configuration data
| [ManageState](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.ManageState.md) | Gets and sets the state management value: when true the timer job will automatically handle state by storing a json serialized class as a web property bag entry. Default value is false
| [IsRunning](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.IsRunning.md) | Is this timer job running?
| [UseThreading](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.UseThreading.md) | Can this timer job use multiple threads. Defaults to true
| [MaximumThreads](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.MaximumThreads.md) | How many threads can be used by this timer job. Default value is 5.
| [AuthenticationType](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.AuthenticationType.md) | Gets the authentication type that the timer job will use. This will be set as part of the UseOffice365Authentication and UseNetworkCredentialsAuthentication methods
| [SharePointVersion](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.SharePointVersion.md) | Gets or sets the SharePoint version. Default value is detected based on the laoded CSOM assembly version, but can be overriden in case you want to for example use v16 assemblies in v15 (on-premises)
| [Realm](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.Realm.md) | Realm will be automatically defined, but there's an option to manually specify it which may be needed when did an override of ResolveAddedSites and specify your sites.
| [TenantAdminSite](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.TenantAdminSite.md) | Option to specify the tenant admin site. For MT this typically is not needed since we can detect the tenant admin site, but for on premises and DvNext this is needed
| [ExpandSubSites](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.ExpandSubSites.md) | Does the timerjob need to fire as well for every sub site in the site?
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [add_TimerJobRun(TimerJobRunHandler)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.add_TimerJobRunTimerJobRunHandler.md) | 
| [remove_TimerJobRun(TimerJobRunHandler)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.remove_TimerJobRunTimerJobRunHandler.md) | 
| [Run()](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.Run.md) | Triggers the timer job to start running
| [DoWorkBatch(Collections.Generic.List<String>)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.DoWorkBatchCollections.Generic.List<String>.md) | 
| [DoWork(String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.DoWorkString.md) | Processes the amount of work that will be done for a single site/web
| [OnTimerJobRun(TimerJobRunEventArgs)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.OnTimerJobRunTimerJobRunEventArgs.md) | Triggers the event to fire and deals with all the pre/post processing needed to automatically manage state
| [CreateWorkBatches()](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.CreateWorkBatches.md) | Creates batches of sites to process. Batch size is based on max number of threads
| [UseOffice365Authentication(String, String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.UseOffice365AuthenticationStringString.md) | Prepares the timerjob to operate against Office 365 with user and password credentials. Sets AuthenticationType to AuthenticationType.Office365
| [UseOffice365Authentication(String, Security.SecureString)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.UseOffice365AuthenticationStringSecurity.SecureString.md) | Prepares the timerjob to operate against Office 365 with user and password credentials. Sets AuthenticationType to AuthenticationType.Office365
| [UseOffice365Authentication(String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.UseOffice365AuthenticationString.md) | Prepares the timerjob to operate against Office 365 with user and password credentials which are retrieved via the windows Credential Manager. Also sets AuthenticationType to AuthenticationType.Office365
| [UseNetworkCredentialsAuthentication(String, String, String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.UseNetworkCredentialsAuthenticationStringStringString.md) | Prepares the timerjob to operate against SharePoint on-premises with user name password credentials. Sets AuthenticationType to AuthenticationType.NetworkCredentials
| [UseNetworkCredentialsAuthentication(String, Security.SecureString, String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.UseNetworkCredentialsAuthenticationStringSecurity.SecureStringString.md) | Prepares the timerjob to operate against SharePoint on-premises with user name password credentials. Sets AuthenticationType to AuthenticationType.NetworkCredentials
| [UseNetworkCredentialsAuthentication(String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.UseNetworkCredentialsAuthenticationString.md) | Prepares the timerjob to operate against SharePoint on-premises with user name password credentials which are retrieved via the windows Credential Manager. Sets AuthenticationType to AuthenticationType.NetworkCredentials
| [UseAppOnlyAuthentication(String, String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.UseAppOnlyAuthenticationStringString.md) | Prepares the timerjob to operate against SharePoint on-premises with app-only credentials. Sets AuthenticationType to AuthenticationType.AppOnly
| [UseAzureADAppOnlyAuthentication(String, String, String, String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.UseAzureADAppOnlyAuthenticationStringStringStringString.md) | Prepares the timerjob to operate against SharePoint Only with Azure AD app-only credentials. Sets AuthenticationType to AuthenticationType.AzureADAppOnly
| [UseAzureADAppOnlyAuthentication(String, String, String, Security.SecureString)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.UseAzureADAppOnlyAuthenticationStringStringStringSecurity.SecureString.md) | Prepares the timerjob to operate against SharePoint Only with Azure AD app-only credentials. Sets AuthenticationType to AuthenticationType.AzureADAppOnly
| [UseAzureADAppOnlyAuthentication(String, String, Security.Cryptography.X509Certificates.X509Certificate2)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.UseAzureADAppOnlyAuthenticationStringStringSecurity.Cryptography.X509Certificates.X509Certificate2.md) | Prepares the timerjob to operate against SharePoint Only with Azure AD app-only credentials. Sets AuthenticationType to AuthenticationType.AzureADAppOnly
| [Clone(TimerJob)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.CloneTimerJob.md) | Takes over the settings from the passed timer job. Is useful when you run multiple jobs in a row or chain job execution. Settings that are taken over are all the authentication, enumeration settings and SharePointVersion
| [GetAuthenticationManager(String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.GetAuthenticationManagerString.md) | Get an AuthenticationManager instance per host Url. Needed to make this work properly, else we're getting access denied because of Invalid audience Uri
| [SetEnumerationCredentials(String, String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.SetEnumerationCredentialsStringString.md) | Provides the timer job with the enumeration credentials. For Office 365 username and password is sufficient
| [SetEnumerationCredentials(String, Security.SecureString)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.SetEnumerationCredentialsStringSecurity.SecureString.md) | Provides the timer job with the enumeration credentials. For Office 365 username and password is sufficient
| [SetEnumerationCredentials(String, String, String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.SetEnumerationCredentialsStringStringString.md) | Provides the timer job with the enumeration credentials. For SharePoint on-premises username, password and domain are needed
| [SetEnumerationCredentials(String, Security.SecureString, String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.SetEnumerationCredentialsStringSecurity.SecureStringString.md) | Provides the timer job with the enumeration credentials. For SharePoint on-premises username, password and domain are needed
| [SetEnumerationCredentials(String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.SetEnumerationCredentialsString.md) | Provides the timer job with the enumeration credentials. For SharePoint on-premises username, password and domain are needed
| [AddSite(String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.AddSiteString.md) | Adds a site Url or wildcard site Url to the collection of sites that the timer job will process
| [ClearAddedSites()](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.ClearAddedSites.md) | Clears the list of added site Url's and/or wildcard site Url's
| [UpdateAddedSites(Collections.Generic.List<String>)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.UpdateAddedSitesCollections.Generic.List<String>.md) | 
| [ResolveAddedSites(Collections.Generic.List<String>)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.ResolveAddedSitesCollections.Generic.List<String>.md) | 
| [DoExpandBatch(Collections.Generic.List<String>, Collections.Generic.List<String>)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.DoExpandBatchCollections.Generic.List<String>Collections.Generic.List<String>.md) | 
| [CreateExpandBatches(Collections.Generic.List<String>)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.CreateExpandBatchesCollections.Generic.List<String>.md) | 
| [ExpandSite(Collections.Generic.List<String>, String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.ExpandSiteCollections.Generic.List<String>String.md) | 
| [CreateClientContext(String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.CreateClientContextString.md) | Creates a ClientContext object based on the set AuthenticationType and the used version of SharePoint
| [ResolveSite(String, Collections.Generic.List<String>)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.ResolveSiteStringCollections.Generic.List<String>.md) | 
| [GetAllSubSites(Microsoft.SharePoint.Client.Site)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.GetAllSubSitesMicrosoft.SharePoint.Client.Site.md) | Gets all sub sites for a given site
| [IsValidUrl(String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.IsValidUrlString.md) | Verifies if the passed Url has a valid structure
| [GetSharePointVersion()](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.GetSharePointVersion.md) | Gets the current SharePoint version based on the loaded assembly
| [GetTenantAdminSite(String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.GetTenantAdminSiteString.md) | Gets the tenant admin site based on the tenant name provided when setting the authentication details
| [GetTopLevelSite(String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.GetTopLevelSiteString.md) | Gets the top level site for the given url
| [GetRootSite(String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.GetRootSiteString.md) | Gets the root site for a given site Url
| [NormalizedTimerJobName(String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.NormalizedTimerJobNameString.md) | Normalizes the timer job name
| [IsInternalServerErrorException(Exception)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.IsInternalServerErrorExceptionException.md) | Returns true if the exception was a "The remote server returned an error: (500) Internal Server Error"
| [IsNotFoundException(Exception)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.IsNotFoundExceptionException.md) | Returns true if the exception was a "The remote server returned an error: (404) Not Found"
## See also
- [OfficeDevPnP.Core.Framework.TimerJobs](OfficeDevPnP.Core.Framework.TimerJobs.md)
