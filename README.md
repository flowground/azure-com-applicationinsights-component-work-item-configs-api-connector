# ![LOGO](logo.png) ApplicationInsightsManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the ApplicationInsightsManagementClient API (version 2015-05-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/applicationinsights-componentWorkItemConfigs_API/2015-05-01/swagger.json<br/>
Generated at: 2019-05-07T17:37:14+03:00

## API Description

Azure Application Insights client for work item configurations for a component.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Gets default work item configurations that exist for the application

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription ID.
* `resourceName` - _required_ - The name of the Application Insights component resource.

### Gets the list work item configurations that exist for the application

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription ID.
* `resourceName` - _required_ - The name of the Application Insights component resource.

### Create a work item configuration for an Application Insights component.

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription ID.
* `resourceName` - _required_ - The name of the Application Insights component resource.

### Delete a work item configuration of an Application Insights component.

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription ID.
* `resourceName` - _required_ - The name of the Application Insights component resource.
* `workItemConfigId` - _required_ - The unique work item configuration Id. This can be either friendly name of connector as defined in connector configuration

## License

**flow**ground :- Telekom iPaaS / azure-com-applicationinsights-component-work-item-configs-api-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
