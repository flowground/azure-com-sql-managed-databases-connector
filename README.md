# ![LOGO](logo.png) SqlManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the SqlManagementClient API (version 2017-03-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/sql-managedDatabases/2017-03-01-preview/swagger.json<br/>
Generated at: 2019-06-11T18:14:24+03:00

## API Description

The Azure SQL Database management API provides a RESTful set of web APIs that interact with Azure SQL Database services to manage your databases. The API enables users to create, retrieve, update, and delete databases, servers, and other entities.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Completes the restore operation on a managed database.

*Tags:* `ManagedDatabases`

#### Input Parameters
* `locationName` - _required_ - The name of the region where the resource is located.
* `operationId` - _required_ - Management operation id that this request tries to complete.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Gets a list of managed databases.

*Tags:* `ManagedDatabases`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `managedInstanceName` - _required_ - The name of the managed instance.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Deletes a managed database.

*Tags:* `ManagedDatabases`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `managedInstanceName` - _required_ - The name of the managed instance.
* `databaseName` - _required_ - The name of the database.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Gets a managed database.

*Tags:* `ManagedDatabases`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `managedInstanceName` - _required_ - The name of the managed instance.
* `databaseName` - _required_ - The name of the database.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Updates an existing database.

*Tags:* `ManagedDatabases`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `managedInstanceName` - _required_ - The name of the managed instance.
* `databaseName` - _required_ - The name of the database.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Creates a new database or updates an existing database.

*Tags:* `ManagedDatabases`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `managedInstanceName` - _required_ - The name of the managed instance.
* `databaseName` - _required_ - The name of the database.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

## License

**flow**ground :- Telekom iPaaS / azure-com-sql-managed-databases-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
