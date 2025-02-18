---
external help file:
Module Name: Microsoft.Graph.Devices.CorporateManagement
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devices.corporatemanagement/new-mgdeviceappmgtiosmanagedappprotection
schema: 2.0.0
---

# New-MgDeviceAppMgtiOSManagedAppProtection

## SYNOPSIS
Create new navigation property to iosManagedAppProtections for deviceAppManagement

## SYNTAX

### CreateExpanded1 (Default)
```
New-MgDeviceAppMgtiOSManagedAppProtection [-AdditionalProperties <Hashtable>]
 [-AllowedDataIngestionLocations <ManagedAppDataIngestionLocation[]>]
 [-AllowedDataStorageLocations <ManagedAppDataStorageLocation[]>]
 [-AllowedInboundDataTransferSources <ManagedAppDataTransferLevel>] [-AllowedIosDeviceModels <String>]
 [-AllowedOutboundClipboardSharingExceptionLength <Int32>]
 [-AllowedOutboundClipboardSharingLevel <ManagedAppClipboardSharingLevel>]
 [-AllowedOutboundDataTransferDestinations <ManagedAppDataTransferLevel>]
 [-AppActionIfDeviceComplianceRequired <ManagedAppRemediationAction>]
 [-AppActionIfIosDeviceModelNotAllowed <ManagedAppRemediationAction>]
 [-AppActionIfMaximumPinRetriesExceeded <ManagedAppRemediationAction>]
 [-AppActionIfUnableToAuthenticateUser <ManagedAppRemediationAction>]
 [-AppDataEncryptionType <ManagedAppDataEncryptionType>] [-AppGroupType <TargetedManagedAppGroupType>]
 [-Apps <IMicrosoftGraphManagedMobileApp[]>]
 [-Assignments <IMicrosoftGraphTargetedManagedAppPolicyAssignment[]>]
 [-BlockDataIngestionIntoOrganizationDocuments] [-ContactSyncBlocked] [-CreatedDateTime <DateTime>]
 [-CustomBrowserProtocol <String>] [-CustomDialerAppProtocol <String>] [-DataBackupBlocked]
 [-DeployedAppCount <Int32>] [-DeploymentSummary <IMicrosoftGraphManagedAppPolicyDeploymentSummary>]
 [-Description <String>] [-DeviceComplianceRequired]
 [-DialerRestrictionLevel <ManagedAppPhoneNumberRedirectLevel>] [-DisableAppPinIfDevicePinIsSet]
 [-DisableProtectionOfManagedOutboundOpenInData] [-DisplayName <String>]
 [-ExemptedAppProtocols <IMicrosoftGraphKeyValuePair[]>] [-ExemptedUniversalLinks <String[]>] [-FaceIdBlocked]
 [-FilterOpenInToOnlyManagedApps] [-FingerprintBlocked]
 [-GracePeriodToBlockAppsDuringOffClockHours <TimeSpan>] [-Id <String>] [-IsAssigned]
 [-LastModifiedDateTime <DateTime>] [-ManagedBrowser <ManagedBrowserType>]
 [-ManagedBrowserToOpenLinksRequired] [-ManagedUniversalLinks <String[]>]
 [-MaximumAllowedDeviceThreatLevel <ManagedAppDeviceThreatLevel>] [-MaximumPinRetries <Int32>]
 [-MaximumRequiredOSVersion <String>] [-MaximumWarningOSVersion <String>] [-MaximumWipeOSVersion <String>]
 [-MinimumPinLength <Int32>] [-MinimumRequiredAppVersion <String>] [-MinimumRequiredOSVersion <String>]
 [-MinimumRequiredSdkVersion <String>] [-MinimumWarningAppVersion <String>]
 [-MinimumWarningOSVersion <String>] [-MinimumWipeAppVersion <String>] [-MinimumWipeOSVersion <String>]
 [-MinimumWipeSdkVersion <String>] [-MobileThreatDefenseRemediationAction <ManagedAppRemediationAction>]
 [-NotificationRestriction <ManagedAppNotificationRestriction>] [-OrganizationalCredentialsRequired]
 [-PeriodBeforePinReset <TimeSpan>] [-PeriodOfflineBeforeAccessCheck <TimeSpan>]
 [-PeriodOfflineBeforeWipeIsEnforced <TimeSpan>] [-PeriodOnlineBeforeAccessCheck <TimeSpan>]
 [-PinCharacterSet <ManagedAppPinCharacterSet>] [-PinRequired]
 [-PinRequiredInsteadOfBiometricTimeout <TimeSpan>] [-PreviousPinBlockCount <Int32>] [-PrintBlocked]
 [-ProtectInboundDataFromUnknownSources] [-RoleScopeTagIds <String[]>] [-SaveAsBlocked] [-SimplePinBlocked]
 [-TargetedAppManagementLevels <AppManagementLevel>] [-ThirdPartyKeyboardsBlocked] [-Version <String>]
 [-Confirm] [-WhatIf] [<CommonParameters>]
```

### Create1
```
New-MgDeviceAppMgtiOSManagedAppProtection -BodyParameter <IMicrosoftGraphIosManagedAppProtection> [-Confirm]
 [-WhatIf] [<CommonParameters>]
```

## DESCRIPTION
Create new navigation property to iosManagedAppProtections for deviceAppManagement

## EXAMPLES

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: System.Collections.Hashtable
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AllowedDataIngestionLocations
Data storage locations where a user may store managed data.

```yaml
Type: Microsoft.Graph.PowerShell.Support.ManagedAppDataIngestionLocation[]
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AllowedDataStorageLocations
Data storage locations where a user may store managed data.

```yaml
Type: Microsoft.Graph.PowerShell.Support.ManagedAppDataStorageLocation[]
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AllowedInboundDataTransferSources
Data can be transferred from/to these classes of apps

```yaml
Type: Microsoft.Graph.PowerShell.Support.ManagedAppDataTransferLevel
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AllowedIosDeviceModels
Semicolon seperated list of device models allowed, as a string, for the managed app to work.

```yaml
Type: System.String
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AllowedOutboundClipboardSharingExceptionLength
Specify the number of characters that may be cut or copied from Org data and accounts to any application.
This setting overrides the AllowedOutboundClipboardSharingLevel restriction.
Default value of '0' means no exception is allowed.

```yaml
Type: System.Int32
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AllowedOutboundClipboardSharingLevel
Represents the level to which the device's clipboard may be shared between apps

```yaml
Type: Microsoft.Graph.PowerShell.Support.ManagedAppClipboardSharingLevel
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AllowedOutboundDataTransferDestinations
Data can be transferred from/to these classes of apps

```yaml
Type: Microsoft.Graph.PowerShell.Support.ManagedAppDataTransferLevel
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AppActionIfDeviceComplianceRequired
An admin initiated action to be applied on a managed app.

```yaml
Type: Microsoft.Graph.PowerShell.Support.ManagedAppRemediationAction
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AppActionIfIosDeviceModelNotAllowed
An admin initiated action to be applied on a managed app.

```yaml
Type: Microsoft.Graph.PowerShell.Support.ManagedAppRemediationAction
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AppActionIfMaximumPinRetriesExceeded
An admin initiated action to be applied on a managed app.

```yaml
Type: Microsoft.Graph.PowerShell.Support.ManagedAppRemediationAction
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AppActionIfUnableToAuthenticateUser
An admin initiated action to be applied on a managed app.

```yaml
Type: Microsoft.Graph.PowerShell.Support.ManagedAppRemediationAction
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AppDataEncryptionType
Represents the level to which app data is encrypted for managed apps

```yaml
Type: Microsoft.Graph.PowerShell.Support.ManagedAppDataEncryptionType
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AppGroupType
Indicates a collection of apps to target which can be one of several pre-defined lists of apps or a manually selected list of apps

```yaml
Type: Microsoft.Graph.PowerShell.Support.TargetedManagedAppGroupType
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Apps
List of apps to which the policy is deployed.
To construct, please use Get-Help -Online and see NOTES section for APPS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphManagedMobileApp[]
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Assignments
Navigation property to list of inclusion and exclusion groups to which the policy is deployed.
To construct, please use Get-Help -Online and see NOTES section for ASSIGNMENTS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphTargetedManagedAppPolicyAssignment[]
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BlockDataIngestionIntoOrganizationDocuments
Indicates whether a user can bring data into org documents.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
Policy used to configure detailed management settings targeted to specific security groups and for a specified set of apps on an iOS device
To construct, please use Get-Help -Online and see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphIosManagedAppProtection
Parameter Sets: Create1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -ContactSyncBlocked
Indicates whether contacts can be synced to the user's device.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -CreatedDateTime
The date and time the policy was created.

```yaml
Type: System.DateTime
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -CustomBrowserProtocol
A custom browser protocol to open weblink on iOS.

```yaml
Type: System.String
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -CustomDialerAppProtocol
Protocol of a custom dialer app to click-to-open a phone number on iOS, for example, skype:.

```yaml
Type: System.String
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DataBackupBlocked
Indicates whether the backup of a managed app's data is blocked.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DeployedAppCount
Count of apps to which the current policy is deployed.

```yaml
Type: System.Int32
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DeploymentSummary
The ManagedAppEntity is the base entity type for all other entity types under app management workflow.
To construct, please use Get-Help -Online and see NOTES section for DEPLOYMENTSUMMARY properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphManagedAppPolicyDeploymentSummary
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Description
The policy's description.

```yaml
Type: System.String
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DeviceComplianceRequired
Indicates whether device compliance is required.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DialerRestrictionLevel
The classes of apps that are allowed to click-to-open a phone number, for making phone calls or sending text messages.

```yaml
Type: Microsoft.Graph.PowerShell.Support.ManagedAppPhoneNumberRedirectLevel
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DisableAppPinIfDevicePinIsSet
Indicates whether use of the app pin is required if the device pin is set.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DisableProtectionOfManagedOutboundOpenInData
Disable protection of data transferred to other apps through IOS OpenIn option.
This setting is only allowed to be True when AllowedOutboundDataTransferDestinations is set to ManagedApps.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DisplayName
Policy display name.

```yaml
Type: System.String
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ExemptedAppProtocols
Apps in this list will be exempt from the policy and will be able to receive data from managed apps.
To construct, please use Get-Help -Online and see NOTES section for EXEMPTEDAPPPROTOCOLS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphKeyValuePair[]
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ExemptedUniversalLinks
A list of custom urls that are allowed to invocate an unmanaged app

```yaml
Type: System.String[]
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -FaceIdBlocked
Indicates whether use of the FaceID is allowed in place of a pin if PinRequired is set to True.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -FilterOpenInToOnlyManagedApps
Defines if open-in operation is supported from the managed app to the filesharing locations selected.
This setting only applies when AllowedOutboundDataTransferDestinations is set to ManagedApps and DisableProtectionOfManagedOutboundOpenInData is set to False.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -FingerprintBlocked
Indicates whether use of the fingerprint reader is allowed in place of a pin if PinRequired is set to True.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -GracePeriodToBlockAppsDuringOffClockHours
A grace period before blocking app access during off clock hours.

```yaml
Type: System.TimeSpan
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Id
.

```yaml
Type: System.String
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsAssigned
Indicates if the policy is deployed to any inclusion groups or not.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -LastModifiedDateTime
Last time the policy was modified.

```yaml
Type: System.DateTime
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ManagedBrowser
Type of managed browser

```yaml
Type: Microsoft.Graph.PowerShell.Support.ManagedBrowserType
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ManagedBrowserToOpenLinksRequired
Indicates whether internet links should be opened in the managed browser app, or any custom browser specified by CustomBrowserProtocol (for iOS) or CustomBrowserPackageId/CustomBrowserDisplayName (for Android)

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ManagedUniversalLinks
A list of custom urls that are allowed to invocate a managed app

```yaml
Type: System.String[]
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -MaximumAllowedDeviceThreatLevel
The maxium threat level allowed for an app to be compliant.

```yaml
Type: Microsoft.Graph.PowerShell.Support.ManagedAppDeviceThreatLevel
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -MaximumPinRetries
Maximum number of incorrect pin retry attempts before the managed app is either blocked or wiped.

```yaml
Type: System.Int32
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -MaximumRequiredOSVersion
Versions bigger than the specified version will block the managed app from accessing company data.

```yaml
Type: System.String
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -MaximumWarningOSVersion
Versions bigger than the specified version will block the managed app from accessing company data.

```yaml
Type: System.String
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -MaximumWipeOSVersion
Versions bigger than the specified version will block the managed app from accessing company data.

```yaml
Type: System.String
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -MinimumPinLength
Minimum pin length required for an app-level pin if PinRequired is set to True

```yaml
Type: System.Int32
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -MinimumRequiredAppVersion
Versions less than the specified version will block the managed app from accessing company data.

```yaml
Type: System.String
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -MinimumRequiredOSVersion
Versions less than the specified version will block the managed app from accessing company data.

```yaml
Type: System.String
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -MinimumRequiredSdkVersion
Versions less than the specified version will block the managed app from accessing company data.

```yaml
Type: System.String
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -MinimumWarningAppVersion
Versions less than the specified version will result in warning message on the managed app.

```yaml
Type: System.String
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -MinimumWarningOSVersion
Versions less than the specified version will result in warning message on the managed app from accessing company data.

```yaml
Type: System.String
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -MinimumWipeAppVersion
Versions less than or equal to the specified version will wipe the managed app and the associated company data.

```yaml
Type: System.String
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -MinimumWipeOSVersion
Versions less than or equal to the specified version will wipe the managed app and the associated company data.

```yaml
Type: System.String
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -MinimumWipeSdkVersion
Versions less than the specified version will block the managed app from accessing company data.

```yaml
Type: System.String
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -MobileThreatDefenseRemediationAction
An admin initiated action to be applied on a managed app.

```yaml
Type: Microsoft.Graph.PowerShell.Support.ManagedAppRemediationAction
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -NotificationRestriction
Restrict managed app notification

```yaml
Type: Microsoft.Graph.PowerShell.Support.ManagedAppNotificationRestriction
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -OrganizationalCredentialsRequired
Indicates whether organizational credentials are required for app use.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PeriodBeforePinReset
TimePeriod before the all-level pin must be reset if PinRequired is set to True.

```yaml
Type: System.TimeSpan
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PeriodOfflineBeforeAccessCheck
The period after which access is checked when the device is not connected to the internet.

```yaml
Type: System.TimeSpan
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PeriodOfflineBeforeWipeIsEnforced
The amount of time an app is allowed to remain disconnected from the internet before all managed data it is wiped.

```yaml
Type: System.TimeSpan
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PeriodOnlineBeforeAccessCheck
The period after which access is checked when the device is connected to the internet.

```yaml
Type: System.TimeSpan
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PinCharacterSet
Character set which is to be used for a user's app PIN

```yaml
Type: Microsoft.Graph.PowerShell.Support.ManagedAppPinCharacterSet
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PinRequired
Indicates whether an app-level pin is required.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PinRequiredInsteadOfBiometricTimeout
Timeout in minutes for an app pin instead of non biometrics passcode

```yaml
Type: System.TimeSpan
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PreviousPinBlockCount
Requires a pin to be unique from the number specified in this property.

```yaml
Type: System.Int32
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PrintBlocked
Indicates whether printing is allowed from managed apps.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ProtectInboundDataFromUnknownSources
Protect incoming data from unknown source.
This setting is only allowed to be True when AllowedInboundDataTransferSources is set to AllApps.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -RoleScopeTagIds
List of Scope Tags for this Entity instance.

```yaml
Type: System.String[]
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SaveAsBlocked
Indicates whether users may use the 'Save As' menu item to save a copy of protected files.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SimplePinBlocked
Indicates whether simplePin is blocked.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -TargetedAppManagementLevels
Management levels for apps

```yaml
Type: Microsoft.Graph.PowerShell.Support.AppManagementLevel
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ThirdPartyKeyboardsBlocked
Defines if third party keyboards are allowed while accessing a managed app

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Version
Version of the entity.

```yaml
Type: System.String
Parameter Sets: CreateExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases: cf

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
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphIosManagedAppProtection

## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphIosManagedAppProtection

## NOTES

ALIASES

### New-MgDeviceAppManagementiOSManagedAppProtection

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


APPS <IMicrosoftGraphManagedMobileApp[]>: List of apps to which the policy is deployed.
  - `[Id <String>]`: 
  - `[MobileAppIdentifier <IMicrosoftGraphMobileAppIdentifier>]`: The identifier for a mobile app.
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Version <String>]`: Version of the entity.

ASSIGNMENTS <IMicrosoftGraphTargetedManagedAppPolicyAssignment[]>: Navigation property to list of inclusion and exclusion groups to which the policy is deployed.
  - `[Id <String>]`: 
  - `[Source <DeviceAndAppManagementAssignmentSource?>]`: Represents source of assignment.
  - `[SourceId <String>]`: Identifier for resource used for deployment to a group
  - `[Target <IMicrosoftGraphDeviceAndAppManagementAssignmentTarget>]`: Base type for assignment targets.
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[DeviceAndAppManagementAssignmentFilterId <String>]`: The Id of the filter for the target assignment.
    - `[DeviceAndAppManagementAssignmentFilterType <DeviceAndAppManagementAssignmentFilterType?>]`: Represents type of the assignment filter.

BODYPARAMETER <IMicrosoftGraphIosManagedAppProtection>: Policy used to configure detailed management settings targeted to specific security groups and for a specified set of apps on an iOS device
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[AppGroupType <TargetedManagedAppGroupType?>]`: Indicates a collection of apps to target which can be one of several pre-defined lists of apps or a manually selected list of apps
  - `[Assignments <IMicrosoftGraphTargetedManagedAppPolicyAssignment[]>]`: Navigation property to list of inclusion and exclusion groups to which the policy is deployed.
    - `[Id <String>]`: 
    - `[Source <DeviceAndAppManagementAssignmentSource?>]`: Represents source of assignment.
    - `[SourceId <String>]`: Identifier for resource used for deployment to a group
    - `[Target <IMicrosoftGraphDeviceAndAppManagementAssignmentTarget>]`: Base type for assignment targets.
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[DeviceAndAppManagementAssignmentFilterId <String>]`: The Id of the filter for the target assignment.
      - `[DeviceAndAppManagementAssignmentFilterType <DeviceAndAppManagementAssignmentFilterType?>]`: Represents type of the assignment filter.
  - `[IsAssigned <Boolean?>]`: Indicates if the policy is deployed to any inclusion groups or not.
  - `[TargetedAppManagementLevels <AppManagementLevel?>]`: Management levels for apps
  - `[AllowedDataIngestionLocations <ManagedAppDataIngestionLocation[]>]`: Data storage locations where a user may store managed data.
  - `[AllowedDataStorageLocations <ManagedAppDataStorageLocation[]>]`: Data storage locations where a user may store managed data.
  - `[AllowedInboundDataTransferSources <ManagedAppDataTransferLevel?>]`: Data can be transferred from/to these classes of apps
  - `[AllowedOutboundClipboardSharingExceptionLength <Int32?>]`: Specify the number of characters that may be cut or copied from Org data and accounts to any application. This setting overrides the AllowedOutboundClipboardSharingLevel restriction. Default value of '0' means no exception is allowed.
  - `[AllowedOutboundClipboardSharingLevel <ManagedAppClipboardSharingLevel?>]`: Represents the level to which the device's clipboard may be shared between apps
  - `[AllowedOutboundDataTransferDestinations <ManagedAppDataTransferLevel?>]`: Data can be transferred from/to these classes of apps
  - `[AppActionIfDeviceComplianceRequired <ManagedAppRemediationAction?>]`: An admin initiated action to be applied on a managed app.
  - `[AppActionIfMaximumPinRetriesExceeded <ManagedAppRemediationAction?>]`: An admin initiated action to be applied on a managed app.
  - `[AppActionIfUnableToAuthenticateUser <ManagedAppRemediationAction?>]`: An admin initiated action to be applied on a managed app.
  - `[BlockDataIngestionIntoOrganizationDocuments <Boolean?>]`: Indicates whether a user can bring data into org documents.
  - `[ContactSyncBlocked <Boolean?>]`: Indicates whether contacts can be synced to the user's device.
  - `[DataBackupBlocked <Boolean?>]`: Indicates whether the backup of a managed app's data is blocked.
  - `[DeviceComplianceRequired <Boolean?>]`: Indicates whether device compliance is required.
  - `[DialerRestrictionLevel <ManagedAppPhoneNumberRedirectLevel?>]`: The classes of apps that are allowed to click-to-open a phone number, for making phone calls or sending text messages.
  - `[DisableAppPinIfDevicePinIsSet <Boolean?>]`: Indicates whether use of the app pin is required if the device pin is set.
  - `[FingerprintBlocked <Boolean?>]`: Indicates whether use of the fingerprint reader is allowed in place of a pin if PinRequired is set to True.
  - `[GracePeriodToBlockAppsDuringOffClockHours <TimeSpan?>]`: A grace period before blocking app access during off clock hours.
  - `[ManagedBrowser <ManagedBrowserType?>]`: Type of managed browser
  - `[ManagedBrowserToOpenLinksRequired <Boolean?>]`: Indicates whether internet links should be opened in the managed browser app, or any custom browser specified by CustomBrowserProtocol (for iOS) or CustomBrowserPackageId/CustomBrowserDisplayName (for Android)
  - `[MaximumAllowedDeviceThreatLevel <ManagedAppDeviceThreatLevel?>]`: The maxium threat level allowed for an app to be compliant.
  - `[MaximumPinRetries <Int32?>]`: Maximum number of incorrect pin retry attempts before the managed app is either blocked or wiped.
  - `[MaximumRequiredOSVersion <String>]`: Versions bigger than the specified version will block the managed app from accessing company data.
  - `[MaximumWarningOSVersion <String>]`: Versions bigger than the specified version will block the managed app from accessing company data.
  - `[MaximumWipeOSVersion <String>]`: Versions bigger than the specified version will block the managed app from accessing company data.
  - `[MinimumPinLength <Int32?>]`: Minimum pin length required for an app-level pin if PinRequired is set to True
  - `[MinimumRequiredAppVersion <String>]`: Versions less than the specified version will block the managed app from accessing company data.
  - `[MinimumRequiredOSVersion <String>]`: Versions less than the specified version will block the managed app from accessing company data.
  - `[MinimumWarningAppVersion <String>]`: Versions less than the specified version will result in warning message on the managed app.
  - `[MinimumWarningOSVersion <String>]`: Versions less than the specified version will result in warning message on the managed app from accessing company data.
  - `[MinimumWipeAppVersion <String>]`: Versions less than or equal to the specified version will wipe the managed app and the associated company data.
  - `[MinimumWipeOSVersion <String>]`: Versions less than or equal to the specified version will wipe the managed app and the associated company data.
  - `[MobileThreatDefenseRemediationAction <ManagedAppRemediationAction?>]`: An admin initiated action to be applied on a managed app.
  - `[NotificationRestriction <ManagedAppNotificationRestriction?>]`: Restrict managed app notification
  - `[OrganizationalCredentialsRequired <Boolean?>]`: Indicates whether organizational credentials are required for app use.
  - `[PeriodBeforePinReset <TimeSpan?>]`: TimePeriod before the all-level pin must be reset if PinRequired is set to True.
  - `[PeriodOfflineBeforeAccessCheck <TimeSpan?>]`: The period after which access is checked when the device is not connected to the internet.
  - `[PeriodOfflineBeforeWipeIsEnforced <TimeSpan?>]`: The amount of time an app is allowed to remain disconnected from the internet before all managed data it is wiped.
  - `[PeriodOnlineBeforeAccessCheck <TimeSpan?>]`: The period after which access is checked when the device is connected to the internet.
  - `[PinCharacterSet <ManagedAppPinCharacterSet?>]`: Character set which is to be used for a user's app PIN
  - `[PinRequired <Boolean?>]`: Indicates whether an app-level pin is required.
  - `[PinRequiredInsteadOfBiometricTimeout <TimeSpan?>]`: Timeout in minutes for an app pin instead of non biometrics passcode
  - `[PreviousPinBlockCount <Int32?>]`: Requires a pin to be unique from the number specified in this property.
  - `[PrintBlocked <Boolean?>]`: Indicates whether printing is allowed from managed apps.
  - `[SaveAsBlocked <Boolean?>]`: Indicates whether users may use the 'Save As' menu item to save a copy of protected files.
  - `[SimplePinBlocked <Boolean?>]`: Indicates whether simplePin is blocked.
  - `[CreatedDateTime <DateTime?>]`: The date and time the policy was created.
  - `[Description <String>]`: The policy's description.
  - `[DisplayName <String>]`: Policy display name.
  - `[LastModifiedDateTime <DateTime?>]`: Last time the policy was modified.
  - `[RoleScopeTagIds <String[]>]`: List of Scope Tags for this Entity instance.
  - `[Version <String>]`: Version of the entity.
  - `[Id <String>]`: 
  - `[AllowedIosDeviceModels <String>]`: Semicolon seperated list of device models allowed, as a string, for the managed app to work.
  - `[AppActionIfIosDeviceModelNotAllowed <ManagedAppRemediationAction?>]`: An admin initiated action to be applied on a managed app.
  - `[AppDataEncryptionType <ManagedAppDataEncryptionType?>]`: Represents the level to which app data is encrypted for managed apps
  - `[Apps <IMicrosoftGraphManagedMobileApp[]>]`: List of apps to which the policy is deployed.
    - `[Id <String>]`: 
    - `[MobileAppIdentifier <IMicrosoftGraphMobileAppIdentifier>]`: The identifier for a mobile app.
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Version <String>]`: Version of the entity.
  - `[CustomBrowserProtocol <String>]`: A custom browser protocol to open weblink on iOS.
  - `[CustomDialerAppProtocol <String>]`: Protocol of a custom dialer app to click-to-open a phone number on iOS, for example, skype:.
  - `[DeployedAppCount <Int32?>]`: Count of apps to which the current policy is deployed.
  - `[DeploymentSummary <IMicrosoftGraphManagedAppPolicyDeploymentSummary>]`: The ManagedAppEntity is the base entity type for all other entity types under app management workflow.
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: 
    - `[ConfigurationDeployedUserCount <Int32?>]`: Not yet documented
    - `[ConfigurationDeploymentSummaryPerApp <IMicrosoftGraphManagedAppPolicyDeploymentSummaryPerApp[]>]`: Not yet documented
      - `[ConfigurationAppliedUserCount <Int32?>]`: Number of users the policy is applied.
      - `[MobileAppIdentifier <IMicrosoftGraphMobileAppIdentifier>]`: The identifier for a mobile app.
    - `[DisplayName <String>]`: Not yet documented
    - `[LastRefreshTime <DateTime?>]`: Not yet documented
    - `[Version <String>]`: Version of the entity.
  - `[DisableProtectionOfManagedOutboundOpenInData <Boolean?>]`: Disable protection of data transferred to other apps through IOS OpenIn option. This setting is only allowed to be True when AllowedOutboundDataTransferDestinations is set to ManagedApps.
  - `[ExemptedAppProtocols <IMicrosoftGraphKeyValuePair[]>]`: Apps in this list will be exempt from the policy and will be able to receive data from managed apps.
    - `[Name <String>]`: Name for this key-value pair. Possible names are: AdditionalWSFedEndpointCheckResult,  AllowedAuthenticationClassReferencesCheckResult, AlwaysRequireAuthenticationCheckResult,   AutoUpdateEnabledCheckResult, ClaimsProviderNameCheckResult, EncryptClaimsCheckResult,  EncryptedNameIdRequiredCheckResult, MonitoringEnabledCheckResult,NotBeforeSkewCheckResult,  RequestMFAFromClaimsProvidersCheckResult, SignedSamlRequestsRequiredCheckResult, AdditionalAuthenticationRulesCheckResult, TokenLifetimeCheckResult,  DelegationAuthorizationRulesCheckResult, IssuanceAuthorizationRulesCheckResult, IssuanceTransformRulesCheckResult.
    - `[Value <String>]`: Value for this key-value pair. Possible result values are 0 (when the validation check passed), 1 (when the validation check failed), or 2 (when the validation check is a warning).
  - `[ExemptedUniversalLinks <String[]>]`: A list of custom urls that are allowed to invocate an unmanaged app
  - `[FaceIdBlocked <Boolean?>]`: Indicates whether use of the FaceID is allowed in place of a pin if PinRequired is set to True.
  - `[FilterOpenInToOnlyManagedApps <Boolean?>]`: Defines if open-in operation is supported from the managed app to the filesharing locations selected. This setting only applies when AllowedOutboundDataTransferDestinations is set to ManagedApps and DisableProtectionOfManagedOutboundOpenInData is set to False.
  - `[ManagedUniversalLinks <String[]>]`: A list of custom urls that are allowed to invocate a managed app
  - `[MinimumRequiredSdkVersion <String>]`: Versions less than the specified version will block the managed app from accessing company data.
  - `[MinimumWipeSdkVersion <String>]`: Versions less than the specified version will block the managed app from accessing company data.
  - `[ProtectInboundDataFromUnknownSources <Boolean?>]`: Protect incoming data from unknown source. This setting is only allowed to be True when AllowedInboundDataTransferSources is set to AllApps.
  - `[ThirdPartyKeyboardsBlocked <Boolean?>]`: Defines if third party keyboards are allowed while accessing a managed app

DEPLOYMENTSUMMARY <IMicrosoftGraphManagedAppPolicyDeploymentSummary>: The ManagedAppEntity is the base entity type for all other entity types under app management workflow.
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: 
  - `[ConfigurationDeployedUserCount <Int32?>]`: Not yet documented
  - `[ConfigurationDeploymentSummaryPerApp <IMicrosoftGraphManagedAppPolicyDeploymentSummaryPerApp[]>]`: Not yet documented
    - `[ConfigurationAppliedUserCount <Int32?>]`: Number of users the policy is applied.
    - `[MobileAppIdentifier <IMicrosoftGraphMobileAppIdentifier>]`: The identifier for a mobile app.
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[DisplayName <String>]`: Not yet documented
  - `[LastRefreshTime <DateTime?>]`: Not yet documented
  - `[Version <String>]`: Version of the entity.

EXEMPTEDAPPPROTOCOLS <IMicrosoftGraphKeyValuePair[]>: Apps in this list will be exempt from the policy and will be able to receive data from managed apps.
  - `[Name <String>]`: Name for this key-value pair. Possible names are: AdditionalWSFedEndpointCheckResult,  AllowedAuthenticationClassReferencesCheckResult, AlwaysRequireAuthenticationCheckResult,   AutoUpdateEnabledCheckResult, ClaimsProviderNameCheckResult, EncryptClaimsCheckResult,  EncryptedNameIdRequiredCheckResult, MonitoringEnabledCheckResult,NotBeforeSkewCheckResult,  RequestMFAFromClaimsProvidersCheckResult, SignedSamlRequestsRequiredCheckResult, AdditionalAuthenticationRulesCheckResult, TokenLifetimeCheckResult,  DelegationAuthorizationRulesCheckResult, IssuanceAuthorizationRulesCheckResult, IssuanceTransformRulesCheckResult.
  - `[Value <String>]`: Value for this key-value pair. Possible result values are 0 (when the validation check passed), 1 (when the validation check failed), or 2 (when the validation check is a warning).

## RELATED LINKS

