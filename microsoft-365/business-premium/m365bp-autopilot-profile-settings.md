---
title: "About AutoPilot Profile settings"
ms.author: efrene
author: efrene
manager: scotv
audience: Admin
ms.topic: conceptual
f1.keywords:
- 'ZTDProfileSettings'
- 'O365E_ZTDProfileSettings'
- 'BCS365_ZTDProfileSettings'
ms.service: o365-administration
ms.localizationpriority: high
ms.collection: 
- Adm_O365
- M365-subscription-management 
- M365-identity-device-management
- Adm_TOC
ms.custom:
- Adm_O365
- Core_O365Admin_Migration
- MiniMaven
- MSB365
- OKR_SMB_M365
- AdminSurgePortfolio
search.appverid:
- BCS160
- MET150
- MOE150
ms.assetid: 99bfbf81-e719-4630-9b0f-c187edfa1f8a
description: "AutoPilot profiles help you control how Windows gets installed on user devices. The profiles contain default and optional settings like skip Cortana installation."
---

# About AutoPilot Profile settings

## AutoPilot profile settings

> [!NOTE]
> Microsoft Defender for Business is rolling out to Microsoft 365 Business Premium customers, beginning March 1, 2022. This offering provides additional security features for devices. [Learn more about Defender for Business](../security/defender-business/mdb-overview.md).

You can use AutoPilot profiles to control how Windows is installed on user devices. The profiles contain the following settings.
  
## AutoPilot default features (required) that are set automatically
  
| Setting | Description |
|:-----|:-----|
|Skip Cortana, OneDrive, and OEM registration  |Skips the installation of consumer apps like Cortana and personal OneDrive. The device user can install these later as long as the user is a local admin on the device. The original manufacturer registration is skipped because the device will be managed by Microsoft 365 Business Premium.  |
|Sign in experience with your company brand  |If your company has a [Add your company branding to Microsoft 365 Sign In page](../admin/setup/customize-sign-in-page.md), the device user will get that experience when signing in.  |
|MDM auto-enrollment with configured AAD accounts.  |The user identity will be managed by Azure Active Directory, and users will sign in to Windows and Microsoft 365 with their Microsoft 365 Business Premium credentials.  |

## Optional settings
  
| Setting | Description |
|:-----|:-----|
|Skip privacy settings (Off by default)  |If this option is set to **On**, the device user will not see the license agreement for the device and Windows when he or she first signs in.  |
|Don't allow the user to become the local admin  |If this option is set to **On**, the device user will not be able to install any personal apps, such as Cortana.|

## See also

[Best practices for securing Microsoft 365 for business plans](../admin/security-and-compliance/secure-your-business-data.md)