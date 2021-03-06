---
title: "windows10AssociatedApps resource type"
description: "Windows 10 Associated Application definition."
localization_priority: Normal
author: "tfitzmac"
ms.prod: "Intune"
---

# windows10AssociatedApps resource type

> **Important:** APIs under the /beta version in Microsoft Graph are subject to change. Use of these APIs in production applications is not supported.

> **Note:** The Microsoft Graph API for Intune requires an [active Intune license](https://go.microsoft.com/fwlink/?linkid=839381) for the tenant.

Windows 10 Associated Application definition.

## Properties
|Property|Type|Description|
|:---|:---|:---|
|appType|[windows10AppType](../resources/intune-deviceconfig-windows10apptype.md)|Application type. Possible values are: `desktop`, `universal`.|
|identifier|String|Identifier.|

## Relationships
None

## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.windows10AssociatedApps"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.windows10AssociatedApps",
  "appType": "String",
  "identifier": "String"
}
```




