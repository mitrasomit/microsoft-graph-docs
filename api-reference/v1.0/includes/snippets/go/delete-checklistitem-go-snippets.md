---
description: "Automatically generated file. DO NOT MODIFY"
---

```go


import (
	  "context"
	  msgraphsdk "github.com/microsoftgraph/msgraph-sdk-go"
	  //other-imports
)

graphClient := msgraphsdk.NewGraphServiceClientWithCredentials(cred, scopes)



graphClient.Me().Todo().Lists().ByListId("todoTaskList-id").Tasks().ByTaskId("todoTask-id").ChecklistItems().ByChecklistItemId("checklistItem-id").Delete(context.Background(), nil)


```