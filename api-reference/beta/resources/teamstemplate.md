---
title: "teamsTemplate resource type"
description: "Describes the teamsTemplate entity."
author: "nkramer"
localization_priority: Normal
ms.prod: "microsoft-teams"
---

# teamsTemplate resource type

> **Important:** APIs under the /beta version in Microsoft Graph are in preview and are subject to change. Use of these APIs in production applications is not supported.

A team template is a blueprint for creating a [team](../resources/team.md) in Microsoft Teams. A template specifies the structure, settings, and even content that should be provisioned in a new team created using the template. Microsoft provides a suite of base templates and customers can save their own custom templates.

## Properties

| Property            | Type     | Description |
|:------------------- |:-------- |:----------- |
| id                  | String   | Unique identifier of the template. Cannot be null. |

## JSON representation

<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.teamsTemplate",
  "baseType": "microsoft.graph.entity"
}-->

```json
{
  "id": "string"
}
```

# See also

- [team](team.md)
