# ITemplateProviderExtension
Interface for extending the XMLTemplateProvider while retrieving a template  

**Namespace:** [OfficeDevPnP.Core.Framework.Provisioning.Providers](OfficeDevPnP.Core.Framework.Provisioning.Providers.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public interface ITemplateProviderExtension
```
## Properties
|**Name**|**Description**|
|:-----|:-----|
| [SupportsGetTemplatePreProcessing](OfficeDevPnP.Core.Framework.Provisioning.Providers.ITemplateProviderExtension.SupportsGetTemplatePreProcessing.md) | Declares whether the object supports pre-processing during GetTemplate
| [SupportsGetTemplatePostProcessing](OfficeDevPnP.Core.Framework.Provisioning.Providers.ITemplateProviderExtension.SupportsGetTemplatePostProcessing.md) | Declares whether the object supports post-processing during GetTemplate
| [SupportsSaveTemplatePreProcessing](OfficeDevPnP.Core.Framework.Provisioning.Providers.ITemplateProviderExtension.SupportsSaveTemplatePreProcessing.md) | Declares whether the object supports pre-processing during SaveTemplate
| [SupportsSaveTemplatePostProcessing](OfficeDevPnP.Core.Framework.Provisioning.Providers.ITemplateProviderExtension.SupportsSaveTemplatePostProcessing.md) | Declares whether the object supports post-processing during SaveTemplate
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [Initialize(Object)](OfficeDevPnP.Core.Framework.Provisioning.Providers.ITemplateProviderExtension.InitializeObject.md) | Initialization method to setup the extension object
| [PreProcessGetTemplate(Stream)](OfficeDevPnP.Core.Framework.Provisioning.Providers.ITemplateProviderExtension.PreProcessGetTemplateStream.md) | Method invoked before deserializing the template from the source repository
| [PostProcessGetTemplate(ProvisioningTemplate)](OfficeDevPnP.Core.Framework.Provisioning.Providers.ITemplateProviderExtension.PostProcessGetTemplateProvisioningTemplate.md) | Method invoked after deserializing the template from the source repository
| [PreProcessSaveTemplate(ProvisioningTemplate)](OfficeDevPnP.Core.Framework.Provisioning.Providers.ITemplateProviderExtension.PreProcessSaveTemplateProvisioningTemplate.md) | Method invoked before serializing the template and before it is saved onto the target repository
| [PostProcessSaveTemplate(Stream)](OfficeDevPnP.Core.Framework.Provisioning.Providers.ITemplateProviderExtension.PostProcessSaveTemplateStream.md) | Method invoked after serializing the template and before it is saved onto the target repository
## See also
- [OfficeDevPnP.Core.Framework.Provisioning.Providers](OfficeDevPnP.Core.Framework.Provisioning.Providers.md)
