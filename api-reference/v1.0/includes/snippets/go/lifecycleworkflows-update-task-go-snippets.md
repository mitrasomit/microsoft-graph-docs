---
description: "Automatically generated file. DO NOT MODIFY"
---

```go


import (
	  "context"
	  msgraphsdk "github.com/microsoftgraph/msgraph-sdk-go"
	  graphmodelsidentitygovernance "github.com/microsoftgraph/msgraph-sdk-go/models/identitygovernance"
	  //other-imports
)

graphClient := msgraphsdk.NewGraphServiceClientWithCredentials(cred, scopes)


requestBody := graphmodelsidentitygovernance.NewTask()
description := "Add user to selected groups"
requestBody.SetDescription(&description) 
displayName := "Update marketing day 1 add users to Group set up"
requestBody.SetDisplayName(&displayName) 

result, err := graphClient.IdentityGovernance().LifecycleWorkflows().Workflows().ByWorkflowId("workflow-id").Tasks().ByTaskId("task-id").Patch(context.Background(), requestBody, nil)


```