---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

// Code snippets are only available for the latest version. Current version is 5.x

var graphClient = new GraphServiceClient(requestAdapter);

var result = await graphClient.IdentityGovernance.EntitlementManagement.Catalogs["{accessPackageCatalog-id}"].Resources.GetAsync((requestConfiguration) =>
{
	requestConfiguration.QueryParameters.Expand = new string []{ "roles","scopes" };
	requestConfiguration.QueryParameters.Filter = "originId eq '0282e19d-bf41-435d-92a4-99bab93af305'";
});


```