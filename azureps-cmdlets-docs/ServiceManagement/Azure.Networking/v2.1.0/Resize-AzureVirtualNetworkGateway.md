---
external help file: Microsoft.WindowsAzure.Commands.ServiceManagement.Network.dll-Help.xml
online version: 
schema: 2.0.0
ms.assetid: 8233A181-C445-48F9-880F-261B0EA5F444
---

# Resize-AzureVirtualNetworkGateway

## SYNOPSIS
Resizes a virtual network gateway.

## SYNTAX

```
Resize-AzureVirtualNetworkGateway [-GatewayId] <String> [-GatewaySKU] <String> [-Profile <AzureSMProfile>]
 [<CommonParameters>]
```

## DESCRIPTION
The Resize-AzureVirtualNetworkGateway cmdlet resizes a virtual network gateway.

## EXAMPLES



## PARAMETERS

### -GatewayId
Specifies the ID of a gateway.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: 0
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -GatewaySKU
```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Profile
Specifies the Azure profile from which this cmdlet reads.
If you do not specify a profile, this cmdlet reads from the local default profile.

```yaml
Type: AzureSMProfile
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Get-AzureVirtualNetworkGateway](./Get-AzureVirtualNetworkGateway.md)

[New-AzureVirtualNetworkGateway](./New-AzureVirtualNetworkGateway.md)

[Remove-AzureVirtualNetworkGateway](./Remove-AzureVirtualNetworkGateway.md)

[Reset-AzureVirtualNetworkGateway](./Reset-AzureVirtualNetworkGateway.md)
