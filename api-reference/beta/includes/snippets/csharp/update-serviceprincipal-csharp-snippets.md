---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var servicePrincipal = new ServicePrincipal
{
	AppRoleAssignmentRequired = true
};

await graphClient.ServicePrincipals["{id}"]
	.Request()
	.UpdateAsync(servicePrincipal);

```