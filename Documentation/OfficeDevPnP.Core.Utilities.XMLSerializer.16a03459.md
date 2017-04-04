# XMLSerializer.SerializeToStream Method  
Serializes an object instance to a stream, providing custom namespace prefixes.  

**Namespace:** [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static stream SerializeToStream(T objectToSerialize, XmlSerializerNamespaces ns)
```
### Parameters
*objectToSerialize*  
&emsp;&emsp;Type: T  
&emsp;&emsp;  
  
*ns*  
&emsp;&emsp;Type: System.Xml.Serialization.XmlSerializerNamespaces  
&emsp;&emsp;  
  
### Return Value
Type: System.IO.Stream  
An string that represents the serialized object.

## See also
- [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)
