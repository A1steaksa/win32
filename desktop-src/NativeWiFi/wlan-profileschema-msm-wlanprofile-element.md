---
title: MSM (WLANProfile) element
description: Contains various media-specific module (MSM) settings.
ms.topic: reference
ms.date: 05/25/2023
ms.assetid: 31f98af8-a577-4f6a-9a0a-b182b5a89cc3
topic_type: 
- APIRef
- kbSyntax
api_name: 
- MSM
api_type: 
- Schema
api_location: 
---

# MSM (WLANProfile) element

The MSM (WLANProfile) element contains various media-specific module (MSM) settings.

``` syntax
<xs:element name="MSM"
    minOccurs="0"
>
    <xs:complexType>
        <xs:sequence>
            <xs:element name="connectivity"
                minOccurs="0"
                ...
            />
            <xs:element name="security"
                minOccurs="0"
                ...
            />
        </xs:sequence>
    </xs:complexType>
</xs:element>
```

## Parent elements

* [**WLANProfile**](wlan-profileschema-wlanprofile-element.md)

## Child elements

| Element | Type | Description |
|-|-|-|
| [**connectivity**](wlan-profileschema-connectivity-msm-element.md) | | Contains various connectivity settings. This element is optional. |
| [**security**](wlan-profileschema-security-msm-element.md) | | Contains various security settings. This element is optional. |

## Examples

To view sample profiles that use the **MSM** element, see [Wireless profile samples](wireless-profile-samples.md).

## Requirements

| Requirement | Value |
|-|-|
| Minimum supported client | Windows Vista, Windows XP with SP3 \[desktop apps only\] |
| Minimum supported server | Windows Server 2008 \[desktop apps only\] |
| Redistributable | Wireless LAN API for Windows XP with SP2 |
