---
external help file: Microsoft.Rtc.Management.Hosted.dll-help.xml
online version: https://docs.microsoft.com/powershell/module/skype/grant-csteamsmeetingbroadcastpolicy
applicable: Microsoft Teams, Skype for Business Online
title: Grant-CsTeamsMeetingBroadcastPolicy
schema: 2.0.0
manager: bulenteg
author: tomkau
ms.author: tomkau
ms.reviewer:
---


# Grant-CsTeamsMeetingBroadcastPolicy

## SYNOPSIS
Grant-CsTeamsMeetingBroadcastPolicy \[\[-Identity\] \<UserIdParameter\>\] \[-PolicyName\] \<string\> \[-Tenant \<guid\>\] \[-DomainController \<Fqdn\>\] \[-PassThru\] \[-WhatIf\] \[-Confirm\] \[\<CommonParameters\>\]

Grant-CsTeamsMeetingBroadcastPolicy \[-PolicyName\] \<string\> \[-Tenant \<guid\>\] \[-DomainController \<Fqdn\>\] \[-PassThru\] \[-Global\] \[-WhatIf\] \[-Confirm\] \[\<CommonParameters\>\]

## SYNTAX

### Identity (Default)
```
Grant-CsTeamsMeetingBroadcastPolicy [[-Identity] <UserIdParameter>] [-PolicyName] <String>
 [-Tenant <Guid>] [-DomainController <Fqdn>] [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### GrantToTenant
```
Grant-CsTeamsMeetingBroadcastPolicy [-PolicyName] <String> [-Tenant <Guid>] [-DomainController <Fqdn>]
 [-PassThru] [-Global] [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
User-level policy for tenant admin to configure meeting broadcast behavior for the broadcast event organizer.  Use this cmdlet to assign a policy to a user.

## EXAMPLES


## PARAMETERS

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DomainController
Not applicable to online service. 

```yaml
Type: Fqdn
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Global

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Identity
Indicates the Identity of the user account the policy should be assigned to. User Identities can be specified using one of four formats: 1) the user's SIP address; 2) the user principal name (UPN); 3) the user's domain name and logon name, in the form domain\logon (for example, litwareinc\kenmyer); and, 4) the user's Active Directory display name (for example, Ken Myer). User Identities can also be referenced by using the user's Active Directory distinguished name.

```yaml
Type: UserIdParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: 0
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PassThru

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PolicyName
The name of the custom policy that is being assigned to the user. To remove a specific assignment and fall back to the default tenant policy, you can assign to $Null.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Tenant

```yaml
Type: Guid
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
Shows what would happen if the cmdlet runs.
The cmdlet is not run.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable.
For more information, see about_CommonParameters (https://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Microsoft.Rtc.Management.AD.UserIdParameter
## OUTPUTS

### System.Object
## NOTES

## RELATED LINKS
