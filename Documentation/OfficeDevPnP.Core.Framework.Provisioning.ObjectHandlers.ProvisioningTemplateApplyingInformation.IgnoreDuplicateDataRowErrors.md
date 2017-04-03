# ProvisioningTemplateApplyingInformation.Properties IgnoreDuplicateDataRowErrors
If true then duplicate id errors when the same importing datarows simply generate a warning don't stop the engine. Reason for this is being able to apply the same template multiple times (Delta handling)
            without that failing cause the same record is being added twice  

**Namespace:** [OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers](OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public boolean IgnoreDuplicateDataRowErrors { get; }
public boolean IgnoreDuplicateDataRowErrors { set; }
```

### Property Value
Type: [System.Boolean] 

## See also
- [ProvisioningTemplateApplyingInformation](ProvisioningTemplateApplyingInformation.md) 

- [OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers](OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.md)
