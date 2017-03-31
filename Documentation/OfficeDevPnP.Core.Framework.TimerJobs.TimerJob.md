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
| [TimerJob(String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.ctor1.md) | 
| [TimerJob(String, String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.ctor2.md) | 
| [TimerJob(String, String, String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.ctor3.md) | 
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
| [add_TimerJobRun(TimerJobRunHandler)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.FD4EE791.md) | 
| [remove_TimerJobRun(TimerJobRunHandler)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.C2EAF49.md) | 
| [Run()](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.F2C99142.md) | Triggers the timer job to start running
| [DoWorkBatch(List<String>)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.62F103D7.md) | 
| [DoWork(String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.4729686.md) | Processes the amount of work that will be done for a single site/web
| [OnTimerJobRun(TimerJobRunEventArgs)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.41FD93D5.md) | Triggers the event to fire and deals with all the pre/post processing needed to automatically manage state
| [CreateWorkBatches()](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.27524470.md) | Creates batches of sites to process. Batch size is based on max number of threads
| [UseOffice365Authentication(String, String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.5642EA13.md) | Prepares the timerjob to operate against Office 365 with user and password credentials. Sets AuthenticationType to AuthenticationType.Office365
| [UseOffice365Authentication(String, SecureString)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.A0893D75.md) | Prepares the timerjob to operate against Office 365 with user and password credentials. Sets AuthenticationType to AuthenticationType.Office365
| [UseOffice365Authentication(String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.AA62EC03.md) | Prepares the timerjob to operate against Office 365 with user and password credentials which are retrieved via the windows Credential Manager. Also sets AuthenticationType to AuthenticationType.Office365
| [UseNetworkCredentialsAuthentication(String, String, String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.BCF4E9F6.md) | Prepares the timerjob to operate against SharePoint on-premises with user name password credentials. Sets AuthenticationType to AuthenticationType.NetworkCredentials
| [UseNetworkCredentialsAuthentication(String, SecureString, String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.66B99329.md) | Prepares the timerjob to operate against SharePoint on-premises with user name password credentials. Sets AuthenticationType to AuthenticationType.NetworkCredentials
| [UseNetworkCredentialsAuthentication(String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.413FA6C7.md) | Prepares the timerjob to operate against SharePoint on-premises with user name password credentials which are retrieved via the windows Credential Manager. Sets AuthenticationType to AuthenticationType.NetworkCredentials
| [UseAppOnlyAuthentication(String, String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.913E50EB.md) | Prepares the timerjob to operate against SharePoint on-premises with app-only credentials. Sets AuthenticationType to AuthenticationType.AppOnly
| [UseAzureADAppOnlyAuthentication(String, String, String, String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.9437A92D.md) | Prepares the timerjob to operate against SharePoint Only with Azure AD app-only credentials. Sets AuthenticationType to AuthenticationType.AzureADAppOnly
| [UseAzureADAppOnlyAuthentication(String, String, String, SecureString)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.E55B0812.md) | Prepares the timerjob to operate against SharePoint Only with Azure AD app-only credentials. Sets AuthenticationType to AuthenticationType.AzureADAppOnly
| [UseAzureADAppOnlyAuthentication(String, String, X509Certificate2)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.D6643E5D.md) | Prepares the timerjob to operate against SharePoint Only with Azure AD app-only credentials. Sets AuthenticationType to AuthenticationType.AzureADAppOnly
| [Clone(TimerJob)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.660F2217.md) | Takes over the settings from the passed timer job. Is useful when you run multiple jobs in a row or chain job execution. Settings that are taken over are all the authentication, enumeration settings and SharePointVersion
| [GetAuthenticationManager(String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.16777985.md) | Get an AuthenticationManager instance per host Url. Needed to make this work properly, else we're getting access denied because of Invalid audience Uri
| [SetEnumerationCredentials(String, String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.99EA514B.md) | Provides the timer job with the enumeration credentials. For Office 365 username and password is sufficient
| [SetEnumerationCredentials(String, SecureString)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.A5806529.md) | Provides the timer job with the enumeration credentials. For Office 365 username and password is sufficient
| [SetEnumerationCredentials(String, String, String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.58034B34.md) | Provides the timer job with the enumeration credentials. For SharePoint on-premises username, password and domain are needed
| [SetEnumerationCredentials(String, SecureString, String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.E62AEC94.md) | Provides the timer job with the enumeration credentials. For SharePoint on-premises username, password and domain are needed
| [SetEnumerationCredentials(String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.B1B2B33A.md) | Provides the timer job with the enumeration credentials. For SharePoint on-premises username, password and domain are needed
| [AddSite(String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.C9F16B09.md) | Adds a site Url or wildcard site Url to the collection of sites that the timer job will process
| [ClearAddedSites()](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.4F33069D.md) | Clears the list of added site Url's and/or wildcard site Url's
| [UpdateAddedSites(List<String>)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.1AD1D570.md) | 
| [ResolveAddedSites(List<String>)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.F0D1233.md) | 
| [DoExpandBatch(List<String>, List<String>)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.A6B3E7B1.md) | 
| [CreateExpandBatches(List<String>)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.8A6FCD53.md) | 
| [ExpandSite(List<String>, String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.D1C76BF3.md) | 
| [CreateClientContext(String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.ECEA7641.md) | Creates a ClientContext object based on the set AuthenticationType and the used version of SharePoint
| [ResolveSite(String, List<String>)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.D7B68099.md) | 
| [GetAllSubSites(Site)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.6810E1DF.md) | Gets all sub sites for a given site
| [IsValidUrl(String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.9EDE3CB9.md) | Verifies if the passed Url has a valid structure
| [GetSharePointVersion()](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.907A52ED.md) | Gets the current SharePoint version based on the loaded assembly
| [GetTenantAdminSite(String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.9BCD1EC3.md) | Gets the tenant admin site based on the tenant name provided when setting the authentication details
| [GetTopLevelSite(String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.E91D1D5A.md) | Gets the top level site for the given url
| [GetRootSite(String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.7C96276.md) | Gets the root site for a given site Url
| [NormalizedTimerJobName(String)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.222278EB.md) | Normalizes the timer job name
| [IsInternalServerErrorException(Exception)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.248E29AE.md) | Returns true if the exception was a "The remote server returned an error: (500) Internal Server Error"
| [IsNotFoundException(Exception)](OfficeDevPnP.Core.Framework.TimerJobs.TimerJob.D9F476EE.md) | Returns true if the exception was a "The remote server returned an error: (404) Not Found"
## See also
- [OfficeDevPnP.Core.Framework.TimerJobs](OfficeDevPnP.Core.Framework.TimerJobs.md)
