---
title: "refresh (Client API reference) in Dynamics 365 Customer Engagement| MicrosoftDocs"
ms.date: 10/31/2017
ms.service: "crm-online"
ms.topic: "reference"
applies_to: "Dynamics 365 (online)"
ms.assetid: 03e970ee-7ed3-4df2-9670-222d76a479fd
author: "KumarVivek"
ms.author: "kvivek"
manager: "amyla"
search.audienceType: 
  - developer
search.app: 
  - D365CE
---
# refresh (Client API reference)

[!INCLUDE[](../../../../includes/cc_applies_to_update_9_0_0.md)]

[!INCLUDE[./includes/refresh-description.md](./includes/refresh-description.md)]

## Syntax

`formContext.data.refresh(save).then(successCallback, errorCallback);`

## Parameter

|Name|Type|Required|Description|
|--|--|--|--|
|save|Boolean|No|true if the data should be saved after it is refreshed, otherwise false.|
|successCallback|Function|No|A function to call when the operation succeeds.|
|errorCallback|Function|No|A function to call when the operation fails.|

### Related topics

[formContext](../../clientapi-form-context.md)

