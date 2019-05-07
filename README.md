# ![LOGO](logo.png) PostgreSQLManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the PostgreSQLManagementClient API (version 2017-12-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/postgresql/2017-12-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:38:36+03:00

## API Description

The Microsoft Azure management API provides create, read, update, and delete functionality for Azure PostgreSQL resources including servers, databases, firewall rules, log files and configurations with new business model.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the available REST API operations.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.

### Check the availability of name for resource

*Tags:* `CheckNameAvailability`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.

### List all the performance tiers at specified location in a given subscription.

*Tags:* `LocationBasedPerformanceTier`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `locationName` - _required_ - The name of the location.

### List all the servers in a given subscription.

*Tags:* `Servers`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.

### List all the servers in a given resource group.

*Tags:* `Servers`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.

### Deletes a server.

*Tags:* `Servers`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.

### Gets information about a server.

*Tags:* `Servers`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.

### Updates an existing server. The request body can contain one to many of the properties present in the normal server definition.

*Tags:* `Servers`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.

### Creates a new server, or will overwrite an existing server.

*Tags:* `Servers`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.

### List all the replicas for a given server.

*Tags:* `Replicas`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.

### List all the configurations in a given server.

*Tags:* `Configurations`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.

### Gets information about a configuration of server.

*Tags:* `Configurations`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `configurationName` - _required_ - The name of the server configuration.

### Updates a configuration of a server.

*Tags:* `Configurations`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `configurationName` - _required_ - The name of the server configuration.

### List all the databases in a given server.

*Tags:* `Databases`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.

### Deletes a database.

*Tags:* `Databases`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `databaseName` - _required_ - The name of the database.

### Gets information about a database.

*Tags:* `Databases`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `databaseName` - _required_ - The name of the database.

### Creates a new database or updates an existing database.

*Tags:* `Databases`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `databaseName` - _required_ - The name of the database.

### List all the firewall rules in a given server.

*Tags:* `FirewallRules`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.

### Deletes a server firewall rule.

*Tags:* `FirewallRules`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `firewallRuleName` - _required_ - The name of the server firewall rule.

### Gets information about a server firewall rule.

*Tags:* `FirewallRules`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `firewallRuleName` - _required_ - The name of the server firewall rule.

### Creates a new firewall rule or updates an existing firewall rule.

*Tags:* `FirewallRules`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `firewallRuleName` - _required_ - The name of the server firewall rule.

### List all the log files in a given server.

*Tags:* `LogFiles`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.

## License

**flow**ground :- Telekom iPaaS / azure-com-postgresql-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
