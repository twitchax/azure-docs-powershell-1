---
external help file: Microsoft.Azure.Commands.ApiManagement.ServiceManagement.dll-Help.xml
online version: 
schema: 2.0.0
ms.assetid: 7DA940A7-6CE1-4282-BF43-1CC881B2E011
---

# Set-AzureRmApiManagementCertificate

## SYNOPSIS
Modifies an API Management certificate which is configured for authentication with backend.

## SYNTAX

### Load from file (Default)
```
Set-AzureRmApiManagementCertificate -Context <PsApiManagementContext> -CertificateId <String>
 -PfxFilePath <String> -PfxPassword <String> [-PassThru] [<CommonParameters>]
```

### Raw
```
Set-AzureRmApiManagementCertificate -Context <PsApiManagementContext> -CertificateId <String>
 -PfxBytes <Byte[]> -PfxPassword <String> [-PassThru] [<CommonParameters>]
```

## DESCRIPTION
The **Set-AzureRmApiManagementCertificate** cmdlet modifies an Azure API Management certificate which is configured for authentication with backend.

## EXAMPLES

### Example 1: Modify a certificate
```
PS C:\> Set-AzureRmApiManagementCertificate -Context $ApiMgmtContext -CertificateId "0123456789" -PfxFilePath "C:\contoso\certificates\apimanagementnew.pfx" -PfxPassword "2222"
```

This command modifies the specified API Management certificate.

## PARAMETERS

### -Context
Specifies a **PsApiManagementContext** object.

```yaml
Type: PsApiManagementContext
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -CertificateId
Specifies the ID of the certificate to modify.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -PfxFilePath
Specifies the path to the certificate file in .pfx format to create and upload.
This parameter is required if you do not specify the *PfxBytes* parameter.

```yaml
Type: String
Parameter Sets: Load from file
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -PfxPassword
Specifies the password for the certificate.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -PassThru
Returns an object representing the item with which you are working.
By default, this cmdlet does not generate any output.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -PfxBytes
Specifies an array of bytes of the certificate file in .pfx format.
This parameter is required if you do not specify the *PfxFilePath* parameter.

```yaml
Type: Byte[]
Parameter Sets: Raw
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

### Microsoft.Azure.Commands.ApiManagement.ServiceManagement.Models.PsApiManagementCertificate

## NOTES

## RELATED LINKS

[Get-AzureRmApiManagementCertificate](./Get-AzureRmApiManagementCertificate.md)

[New-AzureRmApiManagementCertificate](./New-AzureRmApiManagementCertificate.md)

[Remove-AzureRmApiManagementCertificate](./Remove-AzureRmApiManagementCertificate.md)
