---

title: "Working with Graph Explorer Teams App"
description: "Find out how to use some of the important features in the Graph Explorer Teams app."
localization_priority: Normal
author: anneguo3

---

# Working with Graph Explorer Microsoft Teams App

The [Graph Explorer](#TODO) app in Microsoft Teams empowers you to conveniently make Microsoft Graph REST API requests and view corresponding responses.

## Connected Resource
To make Microsoft Graph REST API requests in a Teams instance, there must be an identified resource upon which the requests will query against. These permissions are known as resource-specific consent, and this **Connected Resource** section identifies the resource (chat or team channel) ths app is installed against, else it will note that there is no identified resource. 

![Screenshot of Graph Explorer with the Connected Resource section highlighted](./images/connected-resource-teams-app.png)

## Query Runner
This query runner parallels the behavior of the existing Graph Explorer web application query runner, which includes the following elements:

1. HTTP verb drop-down list
2. API version drop-down list
3. Request query address bar
4. Request body
5. Request headers

![Screenshot of the Graph Explorer Teams app user interface](./images/query-runner-teams-app.png)

The response data shows up with:
1. HTTP response code
2. Response from Microsoft Graph API with data
3. Response headers

![Screenshot of a sample request in Graph Explorer](./images/making-a-get-request-teams-app.png)

## Granted resource-specific consent
The list of granted resource-specific consent allows you to understand what permissions have been granted to the app. This is an easy to reference list when unsure about if the app has sufficient permissions to execute on a given request. app has access to and how they map to the required permissions for a given request you are trying to make.
