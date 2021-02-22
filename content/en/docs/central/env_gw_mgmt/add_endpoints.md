---
title: Add an endpoint to API service
linkTitle: Add an endpoint to API service
weight: 30
date: 2021-02-22
description: Learn how add endponts to an api service.
---

## Add an endpoint to API service

Before adding an endpoint, you need to [add a service](/docs/central/env_gw_mgmt/add_api_service).

1. From the details page of your service, click the (+ Add Endpoint) button located at the top right of the **Endpoints** tab.
2. Fill the information about your API service endpoint:
    * **Protocol**: The transfer protocol used by the API service.
    * **Host**: The domain name or IP address of the API service.
    * **Port**: The port number where the API service is exposed.
    * **Basepath**: The path relative to the host where the API service is deployed.
3. Click **Save**.

> If you want to add an endpoint to an API service using the Amplify Central CLI, please refer to these [docs](/docs/central/cli_central/cli_publish) instead.
  
### Errors and debugging

In the event, there is an error while publishing to catalog. The form page will have a large error box explaining what caused the error. The error may contain references to objects only found when using the CLI or API directly. In this case please refer to the [Amplify CLI](/docs/central/cli_central/cli_publish) documentation for further guidance.