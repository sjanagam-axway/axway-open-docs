---
title: Publish an endpoint to Catalog
linkTitle: Publish an endpoint to catalog
weight: 40
date: 2021-02-11
description: How to publish and endpoint to catalog
---

## Publish an endpoint to Catalog

An endpoint can be published to catalog in two ways.

1. After an endpoint has been created from the Add an API Service Wizard, select the **Publish to Catalog** button on the confirmation popup.  
2. From the service details page, go to endpoints table and select the **Publish** button from the actions menu of the endpoint you want to publish.

> If you want to publish and endpoint to catalog using the amplify Central CLI, please refer to these [docs](/docs/central/cli_central/cli_publish) instead.

### Publish to Catalog

* **Title** represents a friendly name for the catalog item. The title will be displayed first and is searchable but does not need to be unique.
* **Logical Name** represents the unique id for the catalog item and must be unique within the scope of the environment. The logical name is referenced in any dependencies of the Catalog item.
* **Description** is limited to 1000 characters.
* **State** Published endpoints will be available for developers and consumers, where as Unpublished endpoints are only available for developers.
* **Visibility** Public endpoints will be visible to the entire organization, where as Restricted endpoints will be visible only to the owning team.  
* **Version Name** Name of the version being to which endpoint belongs to.
* **Endpoint Name** Name of the endpoint being published.


### Errors and debugging

In the event, there is an error while publishing to catalog. The form page will have a large error box explaining what caused the error. The error may contain references to objects only found when using the CLI or API directly. In this case please refer to the [amplify CLI](/docs/central/cli_central/cli_publish) documentation for further guidance.

