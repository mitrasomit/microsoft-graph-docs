---
description: "Automatically generated file. DO NOT MODIFY"
---

```bash

mgc users calendars events create --user-id {user-id} --calendar-id {calendar-id} --body '{\
  "subject": "Let's go for lunch",\
  "body": {\
    "contentType": "HTML",\
    "content": "Does mid month work for you?"\
  },\
  "start": {\
      "dateTime": "2019-03-15T12:00:00",\
      "timeZone": "Pacific Standard Time"\
  },\
  "end": {\
      "dateTime": "2019-03-15T14:00:00",\
      "timeZone": "Pacific Standard Time"\
  },\
  "location":{\
      "displayName":"Harry's Bar"\
  },\
  "attendees": [\
    {\
      "emailAddress": {\
        "address":"adelev@contoso.onmicrosoft.com",\
        "name": "Adele Vance"\
      },\
      "type": "required"\
    }\
  ],\
  "transactionId":"7E163156-7762-4BEB-A1C6-729EA81755A7"\
}\
'

```