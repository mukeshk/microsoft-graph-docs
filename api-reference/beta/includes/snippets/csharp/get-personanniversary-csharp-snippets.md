---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var personAnnualEvent = await graphClient.Me.Profile.Anniversaries["{id}"]
	.Request()
	.GetAsync();

```