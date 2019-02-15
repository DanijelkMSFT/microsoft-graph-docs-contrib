---
title: "diagnosticDataSubmissionMode enum type"
description: "Allow the device to send diagnostic and usage telemetry data, such as Watson."
localization_priority: Normal
author: "tfitzmac"
ms.prod: "Intune"
---

# diagnosticDataSubmissionMode enum type

> **Important:** APIs under the /beta version in Microsoft Graph are subject to change. Use of these APIs in production applications is not supported.

> **Note:** The Microsoft Graph API for Intune requires an [active Intune license](https://go.microsoft.com/fwlink/?linkid=839381) for the tenant.

Allow the device to send diagnostic and usage telemetry data, such as Watson.

## Members
|Member|Value|Description|
|:---|:---|:---|
|userDefined|0|Allow the user to set.|
|none|1|No telemetry data is sent from OS components. Note: This value is only applicable to enterprise and server devices. Using this setting on other devices is equivalent to setting the value of 1.|
|basic|2|Sends basic telemetry data.|
|enhanced|3|Sends enhanced telemetry data including usage and insights data.|
|full|4|Sends full telemetry data including diagnostic data, such as system state.|



