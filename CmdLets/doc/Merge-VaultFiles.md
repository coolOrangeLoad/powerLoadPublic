---
external help file: MergeVaultFiles.dll-Help.xml
Module Name: powerLoad
online version:
schema: 2.0.0
---

# Merge-VaultFiles

## SYNOPSIS
Imports files checksums from Vault

## SYNTAX

```
Merge-VaultFiles [[-Server] <String>] [[-Vault] <String>] [[-User] <String>] [[-Password] <String>]
 [<CommonParameters>]
```

## DESCRIPTION
Imports files checksums from Vault

## EXAMPLES

### Example 1
```powershell
PS C:\> Merge-VaultFiles -Server 'localhost' -Vault 'Vault' -User 'Administrator' -Password ''
```

Imports files checksums from Vault, using all parameters

## PARAMETERS

### -Server
Defines the Vault server for the connection. Default is 'localhost'

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 0
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Vault
Defines the Vault name for the connection. Default is 'Vault'

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 0
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -User
Defines the Vault user name for the connection

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 0
Default value: "Administrator"
Accept pipeline input: False
Accept wildcard characters: False
```

### -Password
Defines the Vault password for the connection. Default is empty.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 0
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### None

## OUTPUTS

### System.Object
## NOTES

## RELATED LINKS
