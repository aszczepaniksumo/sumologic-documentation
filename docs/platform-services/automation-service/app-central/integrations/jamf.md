---
title: Jamf
description: ''
tags: []
---

![](/img/platform-services/automation-service/app-central/logos/jamf.png)

Version: 1.3  
Updated: Jun 28, 2023

**Jamf** creates IT software that manages Apple devices.

## Actions

* **Get Computer Details** *(Enrichment)* - Return a computer general details
* **Get macOs Managed Software Updates** *(Enrichment)* - Retrieves available macOs managed software updates
* **List Computer Groups** *(Enrichment)* - Returns a list of computer groups
* **List Computers** *(Enrichment)* - Returns a list of computers
* **List Config Profiles** *(Enrichment)* - Search for config profiles linked to Jamf Connect
* **Remove Computer** *(Containment)* - Remove specified Computer record
* **Send macOs Managed Software Updates** *(Containment)* - Apply major update to macOs managed software updates

## Jamf in Automation Service and Cloud SOAR

1. To configure the integration, log into the application, expand the configuration menu in the top right corner by hovering over the gear icon and click Automation. <br/>![](/img/platform-services/automation-service/app-central/integrations/jamf/jamf-1.png)

1. In the Automation section, on the left menu, click Integrations. <br/>![](/img/platform-services/automation-service/app-central/integrations/jamf/jamf-2.png)

1. After the list of the integrations appears, search for the integration and click on the row.

1. The integration details will appear. Click on the "+" button to add new Resource. <br/>![](/img/platform-services/automation-service/app-central/integrations/jamf/jamf-3.png)

1. Populate all the required fields (\*) and then click Save.
   * URL: jamf url
   * Username
   * Password <br/>![](/img/platform-services/automation-service/app-central/integrations/jamf/jamf-4.png)

1. To make sure the resource is working, hover over the resource and then click the pencil icon that appears on the right. <br/>![](/img/platform-services/automation-service/app-central/integrations/jamf/jamf-5.png)

1. Click Test. <br/>![](/img/platform-services/automation-service/app-central/integrations/jamf/jamf-6.png)  

1. You should receive a successful notification in the bottom right corner. <br/>![](/img/platform-services/automation-service/app-central/integrations/jamf/jamf-7.png)

  
 

## Change Log

* November 23, 2022 - First upload
* June 15, 2023 (v1.2) - Updated the integration with Environmental Variables
* June 28, 2023 (v1.3) - Updated **List Computers** Action
