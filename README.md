# ![LOGO](logo.png) IoTSpacesClient **flow**ground Connector

## Description

A generated **flow**ground connector for the IoTSpacesClient API (version 2017-10-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/iotspaces/2017-10-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:38:15+03:00

## API Description

Use this API to manage the IoTSpaces service instances in your Azure subscription.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the available IoTSpaces service REST API operations.

*Tags:* `Proxy`

#### Input Parameters
* `api-version` - _required_ - The version of the API.
    Possible values: 2017-10-01-preview.

### Get all the IoTSpaces instances in a subscription.

*Tags:* `Collection`

#### Input Parameters
* `api-version` - _required_ - The version of the API.
    Possible values: 2017-10-01-preview.
* `subscriptionId` - _required_ - The subscription identifier.

### Check if an IoTSpaces instance name is available.

*Tags:* `Proxy`

#### Input Parameters
* `api-version` - _required_ - The version of the API.
    Possible values: 2017-10-01-preview.
* `subscriptionId` - _required_ - The subscription identifier.

### Get all the IoTSpaces instances in a resource group.

*Tags:* `Collection`

#### Input Parameters
* `api-version` - _required_ - The version of the API.
    Possible values: 2017-10-01-preview.
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The name of the resource group that contains the IoTSpaces instance.

### Delete an IoTSpaces instance.

*Tags:* `Resource`

#### Input Parameters
* `api-version` - _required_ - The version of the API.
    Possible values: 2017-10-01-preview.
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The name of the resource group that contains the IoTSpaces instance.
* `resourceName` - _required_ - The name of the IoTSpaces instance.

### Get the metadata of a IoTSpaces instance.

*Tags:* `Resource`

#### Input Parameters
* `api-version` - _required_ - The version of the API.
    Possible values: 2017-10-01-preview.
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The name of the resource group that contains the IoTSpaces instance.
* `resourceName` - _required_ - The name of the IoTSpaces instance.

### Update the metadata of a IoTSpaces instance.

*Tags:* `Resource`

#### Input Parameters
* `api-version` - _required_ - The version of the API.
    Possible values: 2017-10-01-preview.
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The name of the resource group that contains the IoTSpaces instance.
* `resourceName` - _required_ - The name of the IoTSpaces instance.

### Create or update the metadata of an IoTSpaces instance. The usual pattern to modify a property is to retrieve the IoTSpaces instance metadata and security metadata, and then combine them with the modified values in a new body to update the IoTSpaces instance.

*Tags:* `Resource`

#### Input Parameters
* `api-version` - _required_ - The version of the API.
    Possible values: 2017-10-01-preview.
* `subscriptionId` - _required_ - The subscription identifier.
* `resourceGroupName` - _required_ - The name of the resource group that contains the IoTSpaces instance.
* `resourceName` - _required_ - The name of the IoTSpaces instance.

## License

**flow**ground :- Telekom iPaaS / azure-com-iotspaces-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
