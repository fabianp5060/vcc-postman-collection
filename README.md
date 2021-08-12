# Published API Postman Collection 
This postman collection covers all the published APIs within the Vonage Contact Centre Platform. It allows you to configure many environment files that represent a an account.

You can watch a [video overview here](https://drive.google.com/file/d/1H25sBkLZjTnKkJFvrIR7DQxjrG48Ty8l/view?usp=sharing).

## Getting Started

To get started complete these steps:
* Download and import the collection into Postman
* Download and upload the template environment file into Postman
* Generate and note API Credentials for next gen APIs - note Client Id and Secret
* Generate Legacy V0 Credentials - note Account key and Secret
* Make a copy of the Template Environment file and populate as detailed below:

### Environment File

| Key        | Example           | Description  |
| ------------- |-------------| -----|
| `accountkey`	| lmccg0ujju4 | The account key detailed within the System Settings area of the portal. |
| `legacySecret`		| 4arKnS5GfGYLFLp2oTouY0Y2MLEWQi4xERm451zYBTQ=     | This is the secret generated within the System Settings area of the portal. |
| `apiGatewayUrl`	| https://emea.api.newvoicemedia.com      | The api url should match the region that the account is hosted at; emea, apac, nam.|
| `regionUrl`		| https://emea.newvoicemedia.com     | The contact centre url should match the region that the account is hosted at; emea, apac, nam.|
| `clientId`		| 83a5ca63-5c3b-4dbc-bcda-30de689fbace     | This is the client Id generated within the API Admin area of the portal. |
| `secret`		| wJL3tMtVNHkOI6OryFgUeHaoUagZkix9BdW1456     | This is the secret generated within the API Admin area of the portal. |

The following environment entries are used as varaibales within the collection, and do not need to be pre configured

* `startDate` - This can be used to store a Start Date for future requests.
* `endDate` - This can be used to store a End Date for future requests.
* `interactionGuid` - This can be used to store an Interaction Guid for future requests.
* `agentId` - This can be used to store a agent display Id for future requests.
* `username` - This can be used to store a username for future requests.
* `random` - This is automatically managed do not edit.
* `random3` - This is automatically managed do not edit.
* `legacyToken` - This is automatically managed do not edit.
* `token` - This is automatically managed do not edit.
